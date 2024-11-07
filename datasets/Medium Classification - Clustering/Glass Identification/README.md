Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Intermediate<br/>
**Recommended Use:** Classification Models<br/>
**Domain:** Physical<br/> 

## Glass Identification Data Set 

### Predict the type of glass 


---
![](211.jpg)
---

This *intermediate* level data set has 214 rows and 10 columns.
The data set provides details about 6 types of glass, defined in terms of their oxide content (i.e. Na, Fe, K, etc).


This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, and **classification modelling techniques**. 
Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name 	| Definition                                                                                                                                                                                                            	| Data Type    	| Example                   	| % Null Ratios 	|
|-------------------	|----------------	|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|--------------	|---------------------------	|---------------	|
| 1                 	| Id number      	| Id number from 1 to 214                                                                                                                                                                                               	| Quantitative 	| 16, 75, 211               	| 0             	|
| 2                 	| RI             	| RI: Refractive Index                                                                                                                                                                                                  	| Quantitative 	| 1.51755, 1.51613, 1.51844 	| 0             	|
| 3                 	| Na             	| NA: Sodium (unit measurement: weight percent in corresponding oxide)                                                                                                                                                  	| Quantitative 	| 13.19, 12.79, 14.21       	| 0             	|
| 4                 	| Mg             	| Mg: Magnesium (unit measurement: weight percent in corresponding oxide)                                                                                                                                               	| Quantitative 	| 3.82, 2.87, 3.59          	| 0             	|
| 5                 	| Al             	| Al: Aluminum (unit measurement: weight percent in corresponding oxide)                                                                                                                                                	| Quantitative 	| 1.56, 1.43,               	| 0             	|
| 6                 	| Si             	| Si: Silicon (unit measurement: weight percent in corresponding oxide)                                                                                                                                                 	| Quantitative 	| 73.20, 71.77, 72.95       	| 0             	|
| 7                 	| K              	| K: Potassium (unit measurement: weight percent in corresponding oxide)                                                                                                                                                	| Quantitative 	| 0.67, 0.57, 0.11          	| 0             	|
| 8                 	| Ca             	| Ca: Calcium (unit measurement: weight percent in corresponding oxide)                                                                                                                                                 	| Quantitative 	| 8.09, 7.83, 9.57          	| 0             	|
| 9                 	| Ba             	| Ba: Barium (unit measurement: weight percent in corresponding oxide)                                                                                                                                                  	| Quantitative 	| 0.00, 0.11, 0.27          	| 0             	|
| 10                	| Fe             	| Fe: Iron (unit measurement: weight percent in corresponding oxide)                                                                                                                                                    	| Quantitative 	| 0.11, 0.14, 0.00          	| 0             	|
| 11                	| Type of Glass  	| Glas Type (1:   building_windows_float_processed, 2: building_windows_non_float_processed, 3:   vehicle_windows_float_processed, 4: vehicle_windows_non_float_processed, 5:   containers, 6: tableware, 7: headlamps) 	| Quantitative 	| 2, 5, 7                   	| 0             	|
---

### Acknowledgement

This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Glass Identification Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Glass+Identification). 
The UCI page mentions USA Forensic Science Service as the following as the original source of the data set.
