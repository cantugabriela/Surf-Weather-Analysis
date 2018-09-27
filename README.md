
# Background 

The Jupyter Notebook contains the climate analysis for precipitation and temperature in Honolulu, HI from 08-23-2017 to 08-23-2017 (last twelve months of data). It also looks at specific trip dates from 07-01-2017 to 07-14-2017 to model the climate temperature normals and precipitation based on historical weather data. 

Also included an Flask API Application to query: 

* Precipitatoins from last year 
* Weather stations
* Temperature Observations (tobs) for the previous year
* Minimum temperature, the average temperature, and the max temperature for a given start and/or start-end range inlcusive.


# Dataset Information 

* Dataset date range from 01-01-2010 to 08-23-2017
* SQLite Database Schema: 

![Database Schema](https://github.com/cantugabriela/Surf-Weather-Analysis/blob/master/Images/dbschema.PNG?raw=true)



# Observable Trends 
* Honolulu, Hawaii had up to 7 inches of rain in last twelve months. Months with more than 3 inches of rain include: September, October, February, April, and July. 
* The most active station indicates the lowest temperature (54.0°F), highest temperature (85.0°F), and average (71.7°F) of the last twelve months. 
* The aggregate weather data helps us find the daily normals for the trip dates (07-01-2017 to 07-14-2017). The visualization labeled 'Aggregate Daily Normals for Trip Dates' shows the temperature extremes for the trip (low 60°F and high 88°F) while the average predicted temperatures stay in the mid 70's.





# Exploratory Climate Analysis (1 year) 

![Precipitation](https://github.com/cantugabriela/Surf-Weather-Analysis/blob/master/Images/Precipitation.png?raw=true)

![Temperature vs. Frquency Histogram](https://github.com/cantugabriela/Surf-Weather-Analysis/blob/master/Images/TemperaturevsFrequency.png?raw=true)

# Trip Climate Analysis 
![Trip Average Temperature](https://github.com/cantugabriela/Surf-Weather-Analysis/blob/master/Images/TripAvgTemp.png?raw=true)

![Daily Normals](https://github.com/cantugabriela/Surf-Weather-Analysis/blob/master/Images/DailyNormals.png?raw=true)
