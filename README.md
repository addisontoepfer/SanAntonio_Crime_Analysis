# SanAntonio_Crime_Analysis
Exploratory and Spatial analysis of San Antonio Arrest Data (2023-2025)

This project analyzes public crime/arrest data from the San Antonio Police Depratment

## Data
Source-SAPD Arrest Data CSV (2023-2025)
Spatial- US Census ZCTA shapefiles for San Antonio zip codes

## Data Cleaning
-Removed duplicate rows
-Filled missing "Person" values as "Unknown"
-Filtered out "Wanted Person" (as they dominated dataset) values to focus on active crime trends
-Identified add-on or companion offenses and adjusted accordingly

## Analysis Highlights
#Top Offenses- Wanted Person, Public Intoxication, Criminal Trespass, Drug Possession
#Multiple Offense Analysis- Average offenses per incident = 1.31 (filtered)
#Time Period Analysis- Seasonal patterns from June-> December and notable spike Feb->March in 2025

## Tools
Python- pandas, geopandas, seaborn, matplotlib, numpy

