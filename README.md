[![DOI](https://zenodo.org/badge/412336868.svg)](https://zenodo.org/badge/latestdoi/412336868)

Project: SM_machine_learning_animals  

Title: "Rapid literature mapping on the recent use of machine learning for wildlife imagery"  

Aim: systematic survey or machine/deep-learning methods for species/individual/behaviour recognition for animals - identifying gaps and trends.   

Format: Rapid systematic review/map   

Scope: image data (computer vision), wild or semi-wild (include zoo) animals, analyses focus on animal/species individual recognition or behaviour recognition, published inlast 5 years (2017-2021).   

Files:  
- data/mapping_dataset_reconciled.xlsx - raw data and (sheet1) and meta-data (sheet2)  
- data/mapping_dataset_reconciled_2021_new - updated raw data with complete 2021 year records and (sheet1) and meta-data (sheet2)   
- data/species.tree - phylogenetic tree of species from the data set, created using rotl package    
- data/species_tree_new.tre - phylogenetic tree of species from the updated data set (with complete 2021 year records), created using rotl package   
- data/scopus_2021_new_screen.csv - deduplicated bibliographic records from 2021 used for screening update in Rayyan. 
- data/scopus_2021_new.csv - bibliographic records from 2021 used for screening update in Rayyan. 
- data/scopus_AI_1and2.bib - bibliographic records of articles downloaded from Scopus, used for bibliometric analyses   
- data/scopus_2021.bib - bibliographic records from the updated search covering only 2021, used to update original literature search. 
- data/scopus_included_records_2021_updated.bib - updated bibliographic records of articles downloaded from Scopus, with conmplete 2021 records, used for bibliometric analyses. 
- source/screening_update_2021.Rmd - code for deduplicating bibliographic records from the updated search covering only 2021, used to update original literature search. 
- source/mapping_main_figures.Rmd - self-contained code for recreating figures presented in the main manuscript text  
- source/Supplementary_File_1.Rmd - self-contained code for recreating Supplementary File 1, available alongside the main manuscript. The file contans additional mehods, tables and figures  
