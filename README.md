# Weather Analysis for Oahu, Hawaii

## Project Overview of the Weather Analysis
#### The goal of this project was to determine the key differences in weather between June and December, measured from a total of 9 weather stations on the island of Oahu.  
This was in order to evaluate the viability of a business plan for a surfing and ice cream shop on the island.  Investors were interested in the weather findings to ensure that the business would be ideally located for optimal weather conditions.

#### Resources
- Data Source:  hawaii.sqlite
- Software:  SQAlchemy, SQLite, Jupyter Notebook, Microsoft Visual Studio Code, Python, Pandas

## Results of the Analysis
The image below shows the summary statistics for the months of June and December on the island between the dates of June 1, 2010 and June 30, 2017.  For this time period, a total of **3,217** readings were collected across the 9 weather stations.

1. The average temperature as seen below for the month of June was *74.9°F* and the average temperature for the month of December was *71°F*. 
2. The minimum recorded temperature was *56°F* (during December).
3. The maximum recorded temperature was *85°F* (during June). 

![Temperature_chart.png](https://github.com/frostbrosracing/surfs_up/blob/main/Temperature_chart.png)

## Summary of the Analysis
 
These mild temperatures are favorable for a business focused on the enjoyment of outside activity in ideal weather conditions.  In addition to the temperature data that was collected for this analysis, two additional queries could be written to go along with this analysis.

1. The June precipitation totals could be reported by substituting the temperature column in the query for the ***'prcp'*** column.  
2. The December precipitation totals could be reported by substituting the temperature column in the query for the ***'prcp'*** column.

A Pandas DataFrame could then be generated from which summary statistics could be reported.  This DataFrame would show the daily totals reported at each of the 9 weather stations.  

![Precipitation_chart.png](https://github.com/frostbrosracing/surfs_up/blob/main/Precipitation_chart.png)