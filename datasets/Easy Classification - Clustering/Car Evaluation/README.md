Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Beginner <br/>
**Recommended Use:** Classification Models<br/>
**Domain:** Automobile<br/> 

## Car Evaluation Data Set 

### Predict acceptibility of a car


---
![](1190.jpg)
---

This *beginner* level data set was derived from a decision-making model which was originally developed for research on multi-attribute decision making. 
Decision making involves selection between seemingly conflicting alternatives. 

The data set has 1728 rows and 7 columns in which car attributes such as price and technology are described across 6 attributes such as "Buying Price", "Maintenance", and "Safety" etc. There are multiple alternatives under each of the 6 attributes. Car's acceptability,
the seventh attribute, is the outcome variable.         

This data set is recommended for learning and practicing your skills in **classification modelling techniques**. Feel free to explore the data set with multiple 
classification methods. The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name 	| Definition                                                                                	| Data Type   	| Example          	| % Null Ratios 	|
|-------------------	|----------------	|-------------------------------------------------------------------------------------------	|-------------	|------------------	|---------------	|
| 1                 	| buying         	| Buying price of the car (v-high, high, med, low)                                          	| Qualitative 	| low, med, high   	| 0             	|
| 2                 	| maint          	| Price of the maintenance of car (v-high, high, med, low)                                  	| Qualitative 	| low, med, high   	| 0             	|
| 3                 	| doors          	| Number of doors (2, 3, 4, 5-more)                                                         	| Qualitative 	| 2, 3, 4          	| 0             	|
| 4                 	| persons        	| Capacity in terms of persons to carry (2, 4, more)                                        	| Qualitative 	| 2, 4, more       	| 0             	|
| 5                 	| lug_boot       	| The size of luggage boot (small, med, big)                                                	| Qualitative 	| small, med, big  	| 0             	|
| 6                 	| safety         	| Estimated safety of the car (low, med, high)                                              	| Qualitative 	| low, med, high   	| 0             	|
| 7                 	| class          	| Car acceptability (unacc: unacceptible, acc: acceptible, good: good,   v-good: very good) 	| Qualitative 	| unacc, acc, good 	| 0             	|

---

### Acknowledgement

This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Car Evaluation Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Car+Evaluation). The UCI page mentions following as the donor of the dataset:       

+ Marko Bohanec (marko.bohanec '@' ijs.si) 
+ Blaz Zupan (blaz.zupan '@' ijs.si)    




