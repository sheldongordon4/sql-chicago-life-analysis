# SQL Project: Understanding Life in Chicago 

## Project Overview

### Dataset Used

1. Socioeconomic Indicators in Chicago: This dataset contains a selection of six socioeconomic indicators of public health significance and a “hardship index,” for each Chicago community area, for the years 2008 – 2012.
* https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2

2. Chicago Public Schools: This dataset shows all school level performance data used to create CPS School Report Cards for the 2011-2012 school year. This dataset is provided by the city of Chicago's Data Portal.
* https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t

3. Chicago Crime Data: This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days.
* https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2


### Tools
* JupyterLab notebook
* SQLite

## Exploratory Data Analysis
- Find the total number of crimes recorded in the CRIME table.
- List community area names and numbers with per capita income less than 11000.
- List all case numbers for crimes involving minors?(children are not considered minors for the purposes of crime analysis)
- List all kidnapping crimes involving a child?
- List the kind of crimes that were recorded at schools. (No repetitions)
- List the type of schools along with the average safety score for each type.
- List 5 community areas with highest % of households below poverty line
- Which community area is most crime prone? Display the coumminty area number only.
- Use a sub-query to find the name of the community area with highest hardship index
- Use a sub-query to determine the Community Area Name with most number of crimes?
