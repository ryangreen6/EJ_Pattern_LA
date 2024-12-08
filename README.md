# Exploring Patterns of Environmental Justice in Los Angeles County

During the 1930s, the Home Owners’ Loan Corporation (HOLC) rated neighborhoods based on their safety for real estate investment, using a system of (A (green), B (blue), C (yellow), D (red)) to restrict access to loans. This practice, known as “redlining,” has had profound and lasting effects on community wealth and health. Lower rated Redlined neighborhoods tend to have less greenery and are generally hotter than other neighborhoods. A recent study by Soto et al. revealed that redlining has also impacted biodiversity, and that redlined neighborhoods remain the most undersampled areas, across the study sample size of 195 US cities. This disparity is concerning because conservation decisions are based on this data.

The purpose of this repository is to compare these redlined districts with a dataset of biodiversity observations across Los Angeles County. 

## Within this repository:
- EJ_Pattern_LA.qmd
- EJ_Pattern_LA.rproj
- README.md
- .gitignore

## Techniques

This repository mainly involves map making using the package `tmap`, and manipulation of dataframes. It also includes the basic use of `if-else` statements, and the creation of tables using the package `kableExtra`. 

## Data
The data for this project is not housed in this repository. Here are the three datasets used:
- EJScreen - This is a national dataset available from the US EPA at the tract level, containing a wealth of data such as demographic information, air quality measurements, and cancer risk, as well as spatial data for each tract. The data can be downloaded as a geodatabase here: https://www.epa.gov/ejscreen/download-ejscreen-data

- HOLC Redlined Districts - This is a geopackage available from the Mapping Inequality Project, containing data on the redlined districts in Los Angeles and their HOLC grades. The data can be downloaded here: https://dsl.richmond.edu/panorama/redlining/data

Mapping Inequality Project: https://dsl.richmond.edu/panorama/redlining

- Biodiversity Observations - This is a dataset from the Global Biodiversity Information Facility of biodiversity obserations nationally. Observations include location, time, and species observed. The data can be downloaded here: https://www.gbif.org/dataset/search?q=

## Acknowledgements
This project was a part of my learning process in the Bren School's MEDS program at UCSB. I'd like to recognize any and all professors and teacher's assistants who guided me along the way. 

MEDS Program, UCSB: https://bren.ucsb.edu/masters-programs/master-environmental-data-science

## References

Ellis-Soto, D., Chapman, M., & Locke, D. H. (2023). Historical redlining is associated with increasing geographical disparities in bird biodiversity sampling in the United States. Nature Human Behaviour, 1-9.
