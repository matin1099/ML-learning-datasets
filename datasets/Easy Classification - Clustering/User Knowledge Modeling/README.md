Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Beginner <br/>
**Recommended Use:** Classification/Clustering<br/>
**Domain:** Education/Web<br/> 

## User Knowledge Modeling Data Set

### Predict student's knowledge level 


---
![](342309-PA9PNI-658.jpg)
---

This *beginner* level data set has 403 rows and 6 columns.
The data set has been divided into training and testing (training: 258, testing: 145).
It is a real dataset about the students' knowledge status about the subject of Electrical DC Machines.
This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, and **classification** and **clustering** techniques. 
Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name 	| Definition                                                              	| Data Type    	| Example                 	| % Null Ratios 	|
|-------------------	|----------------	|-------------------------------------------------------------------------	|--------------	|-------------------------	|---------------	|
| 1                 	| STG            	| The degree of   study time for goal object materials                    	| Quantitative 	| 0.060, 0.100, 0.080     	| 0             	|
| 2                 	| SCG            	| The degree of   repetition number of user for goal object materials     	| Quantitative 	| 0.000, 0.100, 0.250     	| 0             	|
| 3                 	| STR            	| The degree of   study time of user for related objects with goal object 	| Quantitative 	| 0.10, 0.15, 0.05        	| 0             	|
| 4                 	| LPR            	| The exam   performance of user for related objects with goal object     	| Quantitative 	| 0.98, 0.10, 0.01        	| 0             	|
| 5                 	| PEG            	| The exam   performance of user for goal objects                         	| Quantitative 	| 0.66, 0.56, 0.33        	| 0             	|
| 6                 	| UNS            	| The knowledge   level of user (Very Low, Low, Middle, High)             	| Qualitative  	| "High", "Middle", "Low" 	| 0             	|

---

### Acknowledgement


This data set has been sourced from the Machine Learning Repository of University of California, Irvine [User Knowledge Modeling Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/User+Knowledge+Modeling).<br/> 
The UCI page mentions the following publication as the original source of the data set:<br/>
*H. T. Kahraman, Sagiroglu, S., Colak, I., Developing intuitive knowledge classifier and modeling of users' domain dependent data in web, Knowledge Based Systems, vol. 37, pp. 283-295, 2013*