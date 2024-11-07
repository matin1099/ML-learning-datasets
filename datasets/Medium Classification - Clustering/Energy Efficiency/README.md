Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Intermediate <br/>
**Recommended Use:** Regression/Classification Models<br/>
**Domain:** Energy<br/> 

## Energy Efficiency Data Set 

### Assess heating and cooling load requirements of building 


---
![](OFASNQ0.jpg)
---

This *intermediate* level data set has 768 rows and 10 columns.
This study looked into assessing the heating load and cooling load requirements of buildings (that is, energy efficiency) as a function of building parameters
Energy analysis using 12 different building shapes simulated in Ecotect has been performed. 
The buildings differ with respect to the glazing area, the glazing area distribution, and the orientation, amongst other parameters. 
It can also be used as a multi-class classification problem if the response is rounded to the nearest integer.

This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, **regression** and **classification modelling techniques**. 
Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. 
The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name 	| Definition                   	| Data Type    	| Example                	| % Null Ratios 	|
|-------------------	|----------------	|------------------------------	|--------------	|------------------------	|---------------	|
| 1                 	| X1             	| Relative   Compactness       	| Quantitative 	| 0.86, 0.71, 0.79       	| 0             	|
| 2                 	| X2             	| Surface   Area               	| Quantitative 	| 588.0, 689.0, 710.5    	| 0             	|
| 3                 	| X3             	| Wall   Area                  	| Quantitative 	| 318.5, 416.5, 294.0    	| 0             	|
| 4                 	| X4             	| Roof   Area                  	| Quantitative 	| 110.25, 147.00, 122.50 	| 0             	|
| 5                 	| X5             	| Overall   Height             	| Quantitative 	| 7.0, 3.5               	| 0             	|
| 6                 	| X6             	| Orientation                  	| Quantitative 	| 2, 3, 5                	| 0             	|
| 7                 	| X7             	| Glazing   Area               	| Quantitative 	| 0.1, 0.25, 0.4         	| 0             	|
| 8                 	| X8             	| Glazing Area   Distribution  	| Quantitative 	| 0, 2, 4                	| 0             	|
| 9                 	| Y1             	| Heating   Load               	| Quantitative 	| 10.43, 11.69, 11.09    	| 0             	|
| 10                	| Y2             	| Cooling Load                 	| Quantitative 	| 13.71, 14.45, 19.34    	| 0             	|


### Acknowledgement


This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Energy Efficiency Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Energy+efficiency).<br/> 
The UCI page mentions the following publication as the original source of the data set:<br/> 
[A. Tsanas, A. Xifara: 'Accurate quantitative estimation of energy performance of residential buildings using statistical machine learning tools', Energy and Buildings, Vol. 49, pp. 560-567, 2012 (the paper can be accessed from](http://people.maths.ox.ac.uk/tsanas/Preprints/ENB2012.pdf).  
