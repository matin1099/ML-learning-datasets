Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Beginner <br/>
**Recommended Use:** Regression Models<br/>
**Domain:** Real Estate<br/> 

## Real Estate Valuation Data Set 

### Can you predict the price of a house? 


---
![](310.jpg)
---

This *beginner* level data set has 414 rows and 7 columns. 
It provides the market historical data set of real estate valuations which are collected from Sindian Dist., New Taipei City, Taiwan.
This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, and **regression modelling techniques**. 
Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. 
The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name                         	| Definition                                                                                                                                                                 	| Data Type    	| Example                         	| % Null Ratios 	|
|-------------------	|----------------------------------------	|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|--------------	|---------------------------------	|---------------	|
| 1                 	| X1 transaction date                    	| The   transaction date (for example, 2013.250=2013 March, 2013.500=2013 June, etc.)                                                                                        	| Qualitative  	| 2013.500,   2013.500, 2013.333  	| 0             	|
| 2                 	| X2 house age                           	| The house age   (unit: year)                                                                                                                                               	| Quantitative 	| 19.5, 13.3, 5.0                 	| 0             	|
| 3                 	| X3 distance to the nearest MRT station 	| The distance   to the nearest MRT station (unit: meter)                                                                                                                    	| Quantitative 	| 390.5684, 405.21340, 23.38284   	| 0             	|
| 4                 	| X4 number of convenience stores        	| The number of   convenience stores in the living circle on foot                                                                                                            	| Quantitative 	| 6, 8, 1                         	| 0             	|
| 5                 	| X5 latitude                            	| The geographic   coordinate, latitude (unit: degree)                                                                                                                       	| Quantitative 	| 24.97937,   24.97544, 24.94925  	| 0             	|
| 6                 	| X6 longtitude                          	| The geographic   coordinate, longitude (unit: degree)                                                                                                                      	| Quantitative 	| 121.54243, 121.49587, 121.51151	 	| 0             	|
| 7                 	| Y house price of unit area             	| The house price of unit   area (10000 New Taiwan Dollar/Ping, where Ping is a local unit, 1 Ping = 3.3   meter squared) for example, 29.3 = 293,000 New Taiwan Dollar/Ping 	| Quantitative 	| 29.3, 33.6, 47.7                	| 0             	|

### Acknowledgement


This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Real Estate Valuation Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Real+estate+valuation+data+set).<br/> 
The UCI page mentions the following as the original source of the data set:<br/> 
*Yeh, I. C., & Hsu, T. K. (2018). Building real estate valuation models with comparative approach through case-based reasoning. Applied Soft Computing, 65, 260-271*  