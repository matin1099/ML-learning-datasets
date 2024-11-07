Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Intermediate <br/>
**Recommended Use:** Regression Models<br/>
**Domain:** Social<br/> 

## Bike Sharing Data Set 

### Predict bike rental count (hourly/daily) based on the environmental & seasonal settings

---
![](411.jpg)
---

This *intermediate* level dataset contains the hourly and daily count of rental bikes between years 2011 and 2012 in Capital bikeshare system with the corresponding weather and seasonal information.
Bike-sharing rental process is highly correlated to the environmental and seasonal settings. For instance, weather conditions, precipitation, day of week, season, hour of the day, etc. can affect the rental behaviors.
This contains 2 files: Bike sharing counts aggregated on hourly basis (hour.csv - 17379 rows, 17 columns) & bike sharing counts aggregated on daily basis (day.csv - 731 rows, 16 columns)

This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, and **regression modelling techniques**.
This data set could also be used to discover important trends and relationships.
Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. The Following data dictionary gives more details on this data set. All columns (except hr) are similar in both the data sets:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name 	| Definition                                                                                                                                                                                                                                                                                                 	| Data Type    	| Example                            	| % Null Ratios 	|
|-------------------	|----------------	|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|--------------	|------------------------------------	|---------------	|
| 1                 	| instant        	| Record Index                                                                                                                                                                                                                                                                                               	| Quantitative 	| 190, 7, 17180                      	| 0             	|
| 2                 	| dteday         	| Date (Format: YYYY-MM-DD)                                                                                                                                                                                                                                                                                  	| Quantitative 	| 2012-12-23, 2012-01-01, 2012-06-24 	| 0             	|
| 3                 	| season         	| Season (1:   springer, 2: summer, 3: fall, 4: winter)                                                                                                                                                                                                                                                      	| Quantitative 	| 1, 2, 4                            	| 0             	|
| 4                 	| yr             	| Year (0: 2011,   1:2012)                                                                                                                                                                                                                                                                                   	| Quantitative 	| 0, 1                               	| 0             	|
| 5                 	| mnth           	| Month (1 to 12)                                                                                                                                                                                                                                                                                            	| Quantitative 	| 1, 6, 12                           	| 0             	|
| 6                 	| hr             	| Hour (0 to 23) - Not in day.csv dataset                                                                                                                                                                                                                                                                    	| Quantitative 	| 4, 6, 14                           	| 0             	|
| 7                 	| holiday        	| Weather day is   holiday or not                                                                                                                                                                                                                                                                            	| Quantitative 	| 0, 1                               	| 0             	|
| 8                 	| weekday        	| Day of the   week                                                                                                                                                                                                                                                                                          	| Quantitative 	| 0, 6, 3                            	| 0             	|
| 9                 	| workingday     	| Working Day: If day is neither weekend nor holiday is 1, otherwise is 0                                                                                                                                                                                                                                    	| Quantitative 	| 0, 1                               	| 0             	|
| 10                	| weathersit     	| Weather Situation (1: Clear, Few   clouds, Partly cloudy, Partly cloudy; 2: Mist + Cloudy, Mist + Broken clouds,   Mist + Few clouds, Mist; 3: Light Snow, Light Rain + Thunderstorm + Scattered   clouds, Light Rain + Scattered clouds, 4: Heavy Rain + Ice Pallets +   Thunderstorm + Mist, Snow + Fog) 	| Quantitative 	| 1, 2, 3                            	| 0             	|
| 11                	| temp           	| Normalized   temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min),   t_min=-8, t_max=+39 (only in hourly scale)                                                                                                                                                                      	| Quantitative 	| 0.08, 0.22, 0.34                   	| 0             	|
| 12                	| atemp          	| Normalized   feeling temperature in Celsius. The values are derived via   (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)                                                                                                                                                             	| Quantitative 	| 0.0909, 0.2727, 0.303              	| 0             	|
| 13                	| hum            	| Normalized humidity. The values are divided to 100 (max)                                                                                                                                                                                                                                                   	| Quantitative 	| 0.53, 0.8, 0.31                    	| 0             	|
| 14                	| windspeed      	| Normalized wind speed. The values are divided to 67 (max)                                                                                                                                                                                                                                                  	| Quantitative 	| 0.194, 0, 0.2985                   	| 0             	|
| 15                	| casual         	| Count of casual users                                                                                                                                                                                                                                                                                      	| Quantitative 	| 0, 2, 57                           	| 0             	|
| 16                	| registered     	| Count of   registered users                                                                                                                                                                                                                                                                                	| Quantitative 	| 1, 0, 118                          	| 0             	|
| 17                	| cnt            	| Count of total rental bikes including both casual and registered                                                                                                                                                                                                                                           	| Quantitative 	| 1, 2, 175                          	| 0             	|
---

### Acknowledgement


This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Bike Sharing Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset). 
The UCI page mentions the following publication as the original source of the data set:

*Fanaee-T, Hadi, and Gama, Joao, 'Event labeling combining ensemble detectors and background knowledge', Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg*