# Precipitation in Seattle and New York
Repository for DATA 3320 Project 1

# Project Description
This project will compare precipitation in the Seattle with precipitation in New York. The goal is to determine which city experiences more rain and by how much. Precipitation amounts and the frequency distribution of rain classes (based on precipitation amounts) were used to measure how much rain a city recieved. The monthly and seasonal measures of these metrics were also considered. Overall, Seattle can be argued to have less rain if a resident values the presence of sunny days more, whereas New York can be argued to have less rain if a resident values the absence of rainy days more.

# Requirements
This project uses jupyter notebook environments and the python libraries of pandas, matplotlib, seaborn, altair, numpy, and missingno for various data cleaning, manipulation, analysis, and visualization functions. Google Colab was used as the compiler for the jupyter notebooks.

# Data
Data is sourced from the National Oceanic and Atmospheric Administration (NOAA), and is filtered to include data from select weather stations in the Seattle and New York areas from 01/01/2020 to 01/01/2024.

Seattle data: https://github.com/joeyuy/Seattle-Weather/blob/def98215246c1d0546b333c2e7d61dcb9d7345c0/seattle_rain.csv

New York data: https://github.com/joeyuy/Seattle-Weather/blob/def98215246c1d0546b333c2e7d61dcb9d7345c0/ny_rain.csv

# Data Preparation
Precipitation data is extracted and grouped by Date and City. NaN values are filled via interpolation. New categorical variables based on date (month and season) and precipitation (class) were created.

Data preparation process can be viewed at DataPrep.ipynb

Cleaned data set can be viewed at cleaned_sea_ny_rain.csv

# Author
Joel Stockton Uy
https://www.linkedin.com/in/joel-uy/

# License
This project is licensed under the terms of Open Software License 3.0

License Keyword: OSL-3.0

