[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10052146.svg)](https://doi.org/10.5281/zenodo.10052146)

This repository contains data and analysis scripts for the manuscript:

## Coral reef carbonate chemistry reveals interannual, seasonal, and spatial impacts on ocean acidification off Florida
#### Journal: _Global Biogeochemical Cycles_ [doi:10.1029/2023GB007789](http://dx.doi.org/10.1029/2023GB007789)  

-----

### Description:
We characterized the carbonate chemistry at 38 permanent stations located along 10 inshore-offshore transects spanning 250 km of the Florida Coral Reef (FCR), 
which encompass four major biogeographic regions (Biscayne Bay, Upper Keys, Middle Keys, and Lower Keys) and four shelf zones (inshore, mid-channel, offshore, and oceanic). 
Data have been collected since 2010, with approximately bi-monthly periodicity starting in 2015. We used these data to asses

* Spatial differences
* Seasonlaity
* Interannual trends

### Contents:
#### Scripts:
* **1.CarbChem_expploreNewDatabase.Rmd:** R script that explores all data and look for potential outlayers
* **2.Seasonality_and_trends.Rmd** R script with statistical analysis 


#### Data:
* **Data/ws-mysql-v3.csv:** Bottle data 

* **Data/FLKLocations.csv:** Data set containing the average lat and lon of the sampling stations, as well as the Region and Zone they are assigned to

##### FLK_results:
* **FLK_results/**: Directory containing the files produced by the analysis (script "2.Seasonality_and_trends.Rmd")
