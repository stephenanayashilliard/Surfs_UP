# Surfs_UP

## Overview
Weather analysis using VS Code, Jupyter Notebook, SQLlite, Flask and SQLAlchemy

### Purpose
To pursue funding from possible investors for a surfing/ice cream shop weather data from the Hawaiian island of O'ahu was analysized and compared for the months of June and December.  Weather data between the years 2010 and 2017 were  used.

### Resources
- Data Source: hawaii.sqlite
- Software:
  - Python 3.6.1
  - VS Code
  - Jupyter Notebook
- Modules:
  - SQLite
  - Flask
  - SQLAlchemy
 
## Results of Analyis
Using SQLAlchemy and SQlite, a series of queries were run for the months of June and December for the years 2010 to 2017.  From those queries a summary of statistics were generated.

### June Temperatures       
![June temps](https://github.com/stephenanayashilliard/Surfs_UP/blob/main/Resources/June_temps.png)

### December Temperatures
![December temps](https://github.com/stephenanayashilliard/Surfs_UP/blob/main/Resources/Dec_temps.png)

### Results
- There was a discrepency between the number of sites measured.   Over 1700 sites provided Temperature data in June but only 1517 sites in 
December.  This may have some effect on what are the exact statistics for the month of December.  
- Not a marked difference in degrees between the two months at the higher temperature ranges.
- Much greater difference in degrees beteewn the two months at the lower temperature readings.  This is especially signifcant when you compare the minimum temperatures for both months and the temperatures at the 25th percentile.

## Summary
    
### Recommendations
  - To make sure that the data for December temperatures is complete, it is recommended that if possible the weather data from the 183 missing sites be added for December.
  - Although the numbers were not included in this report.  The addition of tourism numbers as well as surfing statistics could provide a clearer picture of the risk of opening a business in this category.
  - In addition to the above queries,  I have also provided below two additional queries based on precipitation for June and December for the years 2010 to 2017.  

#### June Precipitation
![June Precipitation](https://github.com/stephenanayashilliard/Surfs_UP/blob/main/Resources/June_prcp.png)  

#### December Precipitation
![Dec Precipitation](https://github.com/stephenanayashilliard/Surfs_UP/blob/main/Resources/Dec_Prcp.png)

