Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Intermediate <br/>
**Recommended Use:** Regression Models<br/>
**Domain:** Environment<br/> 

## Beijing PM2.5 Data Set 

### Pollution Level Forecasting
 
---
![](454.jpg)
---

This *intermediate* level data set has 43824 rows and 13 columns.
This hourly data set contains the PM2.5 data of US Embassy in Beijing. Meanwhile, meteorological data from Beijing Capital International Airport are also included.
The data seet could be used for pollution level forecasting using the Air quality attributes provided.
This data set will offer experience in Multi-variate Time Series Forecasting.


This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, and **regression modelling techniques**. 
Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name 	| Definition                             	| Data Type    	| Example                              	| % Null Ratios 	|
|-------------------	|----------------	|----------------------------------------	|--------------	|--------------------------------------	|---------------	|
| 1                 	| No             	| No: row   number                       	| Quantitative 	| 22, 35, 48                           	| 0             	|
| 2                 	| Year           	| Year: year of   data in this row       	| Quantitative 	| 2012, 2013, 2014                     	| 0             	|
| 3                 	| Month          	| Month: month   of data in this row     	| Quantitative 	| 2, 4, 5                              	| 0             	|
| 4                 	| Day            	| Day: day of   data in this row         	| Quantitative 	| 11, 20, 31                           	| 0             	|
| 5                 	| Hour           	| Hour: hour of   data in this row       	| Quantitative 	| 22, 3, 4                             	| 0             	|
| 6                 	| PM2.5          	| PM2.5: PM2.5   concentration (ug/m^3)  	| Quantitative 	| 16.0, 12.0, 5.0                      	| 5             	|
| 7                 	| DEWP           	| DEWP: Dew   Point (â„ƒ)                	| Quantitative 	| 0, -11, 8                            	| 0             	|
| 8                 	| TEMP           	| TEMP:   Temperature (â„ƒ)              	| Quantitative 	| 27.000000, -3.000000, 2.000000       	| 0             	|
| 9                 	| PRES           	| PRES: Pressure   (hPa)                 	| Quantitative 	| 1025.000000, 997.000000, 1044.000000 	| 0             	|
| 10                	| cbwd           	| cbwd: Combined   wind direction        	| Quantitative 	| SE, NW, NE                           	| 0             	|
| 11                	| Iws            	| Iws: Cumulated   wind speed (m/s)      	| Quantitative 	| 24.15, 27.28, 16.10                  	| 0             	|
| 12                	| Ir             	| Is: Cumulated   hours of snow          	| Quantitative 	| 5, 10, 22                            	| 0             	|
| 13                	| Is             	| Ir: Cumulated   hours of rain          	| Quantitative 	| 11, 19, 17                           	| 0             	|

---

### Acknowledgement

This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Beijing PM2.5 Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data). 
The UCI page mentions the following publication as the original source of the data set:

*Liang, X., Zou, T., Guo, B., Li, S., Zhang, H., Zhang, S., Huang, H. and Chen, S. X. (2015). Assessing Beijing's PM2.5 pollution: severity, weather impact, APEC and winter heating. Proceedings of the Royal Society A, 471, 20150257*

