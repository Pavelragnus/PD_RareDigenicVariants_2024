 **It is an investigational progect, which had the aim to find rare pathogenic digenic variants in patients with PD. The source of data  - AMPPD.**
1. The input data were plink binary tables (bed, fam, bim files) with whole-genome data.
2. The primary steps of the project were implemented with help of docker images and scripts, which have been already described:
- https://github.com/mshumilova/BED_VEP_Annotation 
- https://hub.docker.com/repository/docker/mshumilova/vcftocsv_vep_sample/general 
- https://hub.docker.com/repository/docker/mshumilova/compounds_filtration/general    
From this step we have folder with files, every of which contain annotated genome data for every participant separately. 
3. The next step of the project - filtration of variants with special positions according Clin Var annotation tool, gnomAD AF. The notebook 'Filtration' contains the script. 
4. 