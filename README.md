# GEOG5995M_Final_Project
### Student id : 201578497
### Module     : Programming for Social Science - Final Project - 70% Assignment


## Context

The UK recently legislated to become net-zero by 2050, by which time the aim is to end the country's contribution to global warming (Masoud Sajjadian, 2023). According to the department for transport, around 24% of the UKs total greenhouse gas emissions come from transport, with 99 MtCO2e (million tonnes of carbon dioxide equivalent) coming from private transport (Department of Transport, 2022). A reduction in this figure would therefore play a major role in reaching the 2050 target of becoming the first major economy to reach net-zero.

The Consumer Data Research Centre (CDRC) provides Access to Healthy Assets and Hazards (AHAH) data, which contains a multi-domensional index of neiighbourhood health, and includes data on air quality amongst other measures. Air quality data is based on the amount of particulate matter in the air of a size that is 10µm (10 microns) or less (pm10).

CDRC also provides data on retail centres, so by looking at the air quality of these, it could provide a starting point in the drive to reach net-zero, and to clean up environments that all of us have a relationship of some kind with, such as those in which we shop.

This work will look at particulate matter around retail centres in the Yorkshire and The Humber region of England.

## Github

This repository contains: -

•	The GEOG5995M_201578497_Final_Assignment.ipynb file containing the code and markdown for the analysis of the data, including the final two visualisations (Fig.1. and Fig.2.).

All the data required for the analysis: -

•	AHAH_V3_0.csv

•	LSOA_21_Boundaries.gpkg

•	LSOA11_to_LSOA21.csv

•	README.md

•	Retail_Boundaries_UK.gpkg

•	spatial_environment.yml (The environment needed in which to run the code)

•	yh_lsoa_2021.shp (including the additional files required by the .shp file: -

  •	yh_lsoa_2021.dbf
  
  •	yh_lsoa_2021.prj
  
  •	yh_lsoa_2021.shx


## The aims of the code

The code in the Jupyter notebook aims to follow the data science process to help understand the air quality of the physical retail environment in Yorkshire and The Humber and is aimed at policy makers so that they may be able to start to understand where policy interventions may be best placed. These policy interventions should be aimed at providing cleaner air quality in retail locations so that shoppers are not unnecessarily. The notebook is annotated throughout in markdown to explain / justify the aim or results of the next/previous section, and the code itself is commented throughout and should explain the function of each line of code.

The data is loaded at various points throughout the process, cleaned and joined together in various ways, so that there is a clear communication of the sorts of retail classification types, and the average quality of the air in each. There is a calculation of a mean value (particulate matter) that provides the main result of the study, which is plotted bot non-spatially and spatially, which should provide a snapshot of the entire retail environment in the study area and a picture of the data, so that differences and similarities between locations can be seen, and should provide policy makers enough data and information to focus efforts in certain places to improve the conditions.


## Additional information

So that the code can be run, the following packages will be required. Some of which may need to be installed prior to running the code: -

•	pandas

•	geopandas

•	shapely

•	statsmodels

•	matplotlib

•	seaborn

•	contextily

To run the code, please activate the environment called “spatial_env”

## References

Department of Transport 2022. Transport and environment statistics 2022. GOV.UK. [Online]. [Accessed 22 November 2023]. Available from: https://www.gov.uk/government/statistics/transport-and-environment-statistics-2022/transport-and-environment-statistics-2022.

Masoud Sajjadian, S. 2023. A critique on the UK’s net zero strategy. Sustainable Energy Technologies and Assessments. 56, p.103003.

