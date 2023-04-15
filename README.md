# Seattle/St-Louis Weather

# Description
This project compares the rainfall of Seattle and St. Louis to determine which of the two cities is generally rainier. It uses clean precipitation data of both cities to come to the conclusion that Seattle is generally rainier than St. Louis.

# Authors
Stephen Yang

# Requirements
Written in Jupyter Notebook through Google Colab

# Data
Taken from National Centers for Environmental Information
NOAA Climate Data search tool: https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND

Raw data is in /weather-data directory.

# Data Processing
## Data Cleaning
The Data Cleaning was performed using the file: data_cleaning/DATA_3320_Seattle_St_Louis_Data_Preparation_Stephen_Yang.ipynb.
It joins the two datasets, filters out the unnecessary values, and fills out missing data when necessary.

The clean dataset is named data_cleaning/clean_seattle_stl_weather.csv.

## Data Analysis
Data Analysis was done using the file: data_analysis/DATA_3320_Seattle_St_Louis_Analysis_Stephen_Yang.ipynb
It makes a few graphs examining number of days with amounts of rain, number of rainy days, and amount of rain when it does rain.

# License
All datasets in this repository, including cleaned datasets, are free to use.
