Author: Maria Stahl
Date created: 2/10/2023
Readme updated: 2/21/2023

Welcome to Criollo_RDS, a repository for all things Criollo!

In the main folder, you will find a diagram of a database structure for this project.

One of the main subfolder here is titled 'cattle', which is devided into four other folders: 'code', 'outputs', 'processed data', and 'raw data'. This was where I originally started to write the code to combine and organize my cattle-related data, but once I started building my website I copied the .Rmd files over to the 'criollo_RDS_website' subfolder.

Subfolder: code
01_combine ats and lotek collar data.Rmd -- reads in csv files from multiple collar sources and combines into one spreadsheet
02_create_cattle_db.Rmd -- combines multiple spreadsheets with cattle-related data into one database, called cattle.db
03_full-year-heat-map2022 -- visualizes collar data by creating interactive maps

Subfolder: outputs
currently empty (besides test figure)

Subfolder: processed data
currently empty

Subfolder: raw data
fecal sample ID.csv -- dates, tube numbers, and cow IDs for all fecal samples
tag-breed-info.csv -- all the info for each cow in this study, including old ear tag number, new ear tag number, and breed
Subfolder: collar data
Subfolder 2021-11_collarData -- data downloaded from Lotek collars in Nov 2021
Subfolder 2022-03_collarData -- data downloaded from Lotek collars in Mar 2022
Subfolder 2022-06_collarData -- data downloaded from Lotek collars in Jun 2022
Subfolder ats -- all data downloaded from ATS collars
Subfolder CollarData_1120_0521: shapefile of subset of collar data, too big for remote repository so included in .gitignore


