Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Intermediate <br/>
**Recommended Use:** Regression Models<br/>
**Domain:** Business<br/> 

## Daily Demand Forecasting Orders Data Set 

### Predict total number of demand of orders

---
![](294036-P6YS7U-202.jpg)
---

This *intermediate* level data set has 60 rows and 13 columns.
The dataset was collected during 60 days, this is a real database of a brazilian logistics company. 
The dataset has twelve predictive attributes and a target that is the total of orders for daily treatment.

This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, and **regression modelling techniques**. 
It also allows you to practice with large number of features. Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name                              	| Definition                                                                    	| Data Type    	| Example                   	| % Null Ratios 	|
|-------------------	|---------------------------------------------	|-------------------------------------------------------------------------------	|--------------	|---------------------------	|---------------	|
| 1                 	| Week of the month                           	| Week of the month (1: first, 2:   second, 3: third, 4: fourth, 5:fifth)       	| Quantitative 	| 1, 2, 3                   	| 0             	|
| 2                 	| Day of the week                             	| Day of the week (2: Monday, 3:   Tuesday, 4: Wednesday, 5:Thursday, 6:Friday) 	| Quantitative 	| 2, 3, 4                   	| 0             	|
| 3                 	| Non-urgent order                            	| Non-urgent order                                                              	| Quantitative 	| 171.297, 220.343, 127.805 	| 0             	|
| 4                 	| Urgent order                                	| Urgent order                                                                  	| Quantitative 	| 127.667, 141.406, 114.813 	| 0             	|
| 5                 	| Order type A                                	| Order type A                                                                  	| Quantitative 	| 41.542, 46.241, 39.025    	| 0             	|
| 6                 	| Order type B                                	| Order type B                                                                  	| Quantitative 	| 113.294, 120.865, 110.74  	| 0             	|
| 7                 	| Order type C                                	| Order type C                                                                  	| Quantitative 	| 162.284, 196.296, 94.47   	| 0             	|
| 8                 	| Fiscal sector orders                        	| Fiscal sector orders                                                          	| Quantitative 	| 18.156, 1.653, 1.617      	| 0             	|
| 9                 	| Orders from the traffic   controller sector 	| Orders from the traffic   controller sector                                   	| Quantitative 	| 49971, 34878, 33366       	|               	|
| 10                	| Banking orders (1)                          	| Banking orders (1)                                                            	| Quantitative 	| 33703, 32905, 21103       	| 0             	|
| 11                	| Banking orders (2)                          	| Banking orders (2)                                                            	| Quantitative 	| 69054, 117137, 84558      	| 0             	|
| 12                	| Banking orders (3)                          	| Banking orders (3)                                                            	| Quantitative 	| 18423, 29188, 16683       	| 0             	|
| 13                	| Target (Total orders)                       	| Target (Total orders)                                                         	| Quantitative 	| 317.12, 363.402, 244.235  	| 0             	|
---

### Acknowledgement

This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Daily Demand Forecasting Orders Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Daily+Demand+Forecasting+Orders). 
The UCI page mentions the following publication as the original source of the data set:

*Ferreira, R. P., Martiniano, A., Ferreira, A., Ferreira, A., & Sassi, R. J. (2016). Study on daily demand forecasting orders using artificial neural network. IEEE Latin America Transactions, 14(3), 1519-1525*

