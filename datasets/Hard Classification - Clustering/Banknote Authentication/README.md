Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Advanced <br/>
**Recommended Use:** Classification Models<br/>
**Domain:** Banking/Finance<br/> 

## Bank Note Authentication Data Set 

### Predict if a note is genuine

---
![](983.jpg)
---

This *advanced* level data set has 1372 rows and 5 columns.
Data were extracted from images that were taken for the evaluation of an authentication procedure for banknotes.
Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. 
The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.

This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, and **classification modelling techniques**. 
It also allows you to practice with large number of features. Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name                          	| Definition                              	| Data Type    	| Example                     	| % Null Ratios 	|
|-------------------	|-----------------------------------------	|-----------------------------------------	|--------------	|-----------------------------	|---------------	|
| 1                 	| Variance of Wavelet Transformed   Image 	| Variance of Wavelet Transformed   Image 	| Quantitative 	| 1.8993, 1.7939, 0.65497     	| 0             	|
| 2                 	| Skewness of Wavelet Transformed   Image 	| Skewness of Wavelet Transformed   Image 	| Quantitative 	| 7.6625, -1.1174, 5.1815     	| 0             	|
| 3                 	| Curtosis of Wavelet Transformed   Image 	| Curtosis of Wavelet Transformed   Image 	| Quantitative 	| 0.15394, 1.5454, 1.0673     	| 0             	|
| 4                 	| Entropy of Image                        	| Entropy of Image                        	| Quantitative 	| -3.1108, -0.26079, -0.42113 	| 0             	|
| 5                 	| Class                                   	| Class (1: genuine, 0: forged)           	| Quantitative 	| 1, 0                        	| 0             	|

---

### Acknowledgement

This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Bank Note Authentication Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/banknote+authentication). 
The UCI page mentions the following publication as the source of the data set:

*Volker Lohweg (University of Applied Sciences, Ostwestfalen-Lippe, volker.lohweg '@' hs-owl.de)* 
*Helene DÃ¶rksen (University of Applied Sciences, Ostwestfalen-Lippe, helene.doerksen '@' hs-owl.de)*

