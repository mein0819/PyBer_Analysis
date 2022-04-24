# PyBer_Analysis

## Project Overview
The purpose of this project is to create a summary DataFrame that aggregates metrics of ride-sharing data by the 
type of city and to create a visualization showing the total weekly fares for each city type from January-April of 
2019. This information will be presented to help management make key decisions in where resources should be 
allocated to improve access to ride services, ride affordability, and profit for the company.

## Resources
- Data Sources: city_data.csv, ride_data.csv
- Software: Python 3.7.6, Pandas 1.3.4, Jupyter Notebook 6.4.5

## Analysis

I created a summary DataFrame based on city type from data pulled from a merged DataFrame created from the city_data
and ride_data CSV files. The data includes the total driver count, total ride count, total fares, average fare per ride,
and average fare per driver, for each city type. 

![summary dataframe](https://github.com/mein0819/PyBer_Analysis/blob/main/readMe_Images/dataFrame_summary.png)

From this DataFrame we can conclude the following:
- Urban rides were 13x higher than Rural rides and 2.5x higher than Suburban rides
- The total drivers in urban cities was 30x higher than in Rural cities and almost 5x higher than Suburban cities
- The total fares for Rural cities only accounts for approximately 15% of combined fares
