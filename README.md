# Massachusetts Environmental Justice Neighborhoods and Water Quality Analysis
This repository contains the code and ArcGISPro geoprocessing pipeline used to conduct preliminary analysis of water quality metrics and demographics near Environmental Justice (EJ) neighborhoods in Massachusetts. This project integrates demographic data from the 2019 U.S. Census Bureau with discrete water quality probe data gathered between 2005 and 2020 by the Massachusetts Department of Environmental Protection (MassDEP). 

## Project Overview 
Water quality disparities disproportionately affecting minority populations are a major environmental and public health concern in the United States, shaped by environmental, policy, and anthropogenic factors. This project explores associations between key water quality metrics—dissolved oxygen, water temperature, specific conductance, and pH—and proximity to EJ neighborhoods. Publicly available demographic data, compiled for EJ neighborhood classification, were analyzed alongside MassDEP water quality data from up to 1,086 sampling sites across Massachusetts.

Using a GIS pipeline, water monitoring sites were classified into four proximity categories:

    Inside EJ neighborhoods
    Within 1 mile of EJ neighborhoods
    Within 3 miles of EJ neighborhoods
    Greater than 3 miles from EJ neighborhoods

Additionally, a focused analysis of water monitoring sites located directly inside EJ neighborhoods (n=152 sites) examined associations between water quality metrics and key demographic variables, including:

    Median household income
    Percent minority population
    Percentage of households with limited English proficiency


## Contents

code/: Scripts for water quality data pre-processing, exploratory analyses, statistical modeling, and geospatial data processing.

results/: Example maps, model summaries, and visualizations of findings.

## Data Sources

- MassDEP Water Quality discrete probe data, 2005-2020: https://www.mass.gov/guides/water-quality-monitoring-program-data
- MassGIS Data: 2020 Environmental Justice Populations: https://www.mass.gov/info-details/massgis-data-2020-environmental-justice-populations
