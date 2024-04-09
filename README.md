# Precipitation in Seattle and New York
Repository for DATA 3320 Project 1

# Project Information
This project will compare precipitation in the Seattle with precipitation in New York. The goal is to determine which city experiences more rain and by how much.

# Data
Data is sourced from the National Oceanic and Atmospheric Administration (NOAA), and is filtered to include data from select weather stations in the Seattle and New York areas from 01/01/2020 to 01/01/2024.


Seattle data: https://github.com/joeyuy/Seattle-Weather/blob/def98215246c1d0546b333c2e7d61dcb9d7345c0/seattle_rain.csv

New York data: https://github.com/joeyuy/Seattle-Weather/blob/def98215246c1d0546b333c2e7d61dcb9d7345c0/ny_rain.csv

# Data Preparation
Precipitation data is extracted and grouped by Date and City. NaN values are filled via interpolation. New categorical variables based on date (month and season) and precipitation (class) were created.

Data preparation process can be viewed at DataPrep.ipynb

Cleaned data set can be viewed at cleaned_sea_ny_rain.csv
