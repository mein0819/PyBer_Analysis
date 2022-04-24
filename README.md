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
- The total fares for Rural cities only accounts for approximately 15% of combined fares for all city types yet 
  averages $10 more per ride than Urban city rides and over 3x the avererage fare per driver than Urban city rides
- Only Urban cities had a higher ratio of drivers to rides, resulting in the lowest average fare per ride and 
  average fare per driver of the city types
  
Supporting these findings further is the Total Fare by City Type line chart that shows total fares for each city type 
from January through April of 2019

![line chart](https://github.com/mein0819/PyBer_Analysis/blob/main/readMe_Images/line_graph.png)

We can see that Urban rides consistently had the most fares over this time frame, and Suburban rides firmly in the middle with Rural rides accounting for the lowest amount of fares. Also noticable is a peak around the 3rd week of February amongst all city types. 

## Summary

Based on this analysis the following recommendations are offered to helpe improve services, affordability and profits:
- Increase the amount of drivers in Rural cities. The high fare average per ride and per driver suggests that the distance
  for these rides is greater and longer trips leave less available time for the available drivers to pick up new riders.
  Having more drivers at a given time improves access to PyBer's services and may help encourage more ride orders from 
  customers in these areas
- Further analysis exploring distance per ride for each city type and how that correlates to the number of rides and 
  total fares in order to see where improvements can be had in affordabilty for customers and incentives for drivers.
- Further analysis into peaks in business over time, such as the common spike in total fares at the end of February
  and how resources can be allocated to take advantage to the surge in demand

