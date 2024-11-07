Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Intermediate <br/>
**Recommended Use:** Regression/Classification Models<br/>
**Domain:** Business/Finance<br/> 

## Istanbul Stock Exchange Data Set 

### Relate returns of Istanbul Stock Exchange with other international indices 


---
![](9.jpg)
---

This *intermediate* level data set has 536 rows and 9 columns.
The data sets includes returns of Istanbul Stock Exchange with seven other international index; SP, DAX, FTSE, NIKKEI, BOVESPA, MSCE_EU, MSCI_EM from Jun 5, 2009 to Feb 22, 2011 and is organized with regard to working days in Istanbul Stock Exchange.
It can be used to find a predictive relationship between the Istanbul Stock Exchange National 100 Index (ISE100) and seven other international stock market indices.

This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, **regression** and **classification** modelling techniques. 
Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name 	| Definition                                   	| Data Type    	| Example                         	| % Null Ratios 	|
|-------------------	|----------------	|----------------------------------------------	|--------------	|---------------------------------	|---------------	|
| 1                 	| Date           	| Date                                         	| Quantitative 	| 13-Jan-09, 23-Jan-09, 30-Jan-09 	| 0             	|
| 2                 	| ISE            	| Stock Exchange Returns                       	| Quantitative 	| 0.025426, -0.022692, 0.046831   	| 0             	|
| 3                 	| ISE.1          	| Istanbul Stock Exchange - National 100 Index 	| Quantitative 	| 0.031813, -0.044349, 0.061708   	| 0             	|
| 4                 	| SP             	| Standard & Poor's 500 Return Index           	| Quantitative 	| 0.007787, -0.054262, 0.005538   	| 0             	|
| 5                 	| DAX            	| Stock Market Return Index of Germany         	| Quantitative 	| 0.008455, -0.01155, 0.034787    	| 0             	|
| 6                 	| FTSE           	| Stock Market Return Index Of UK              	| Quantitative 	| 0.012866, -0.009351, 0.037891   	| 0             	|
| 7                 	| NIKKEI         	| Stock Market Return Index Of Japan           	| Quantitative 	| 0.004162, 0.003239, -0.008182   	| 0             	|
| 8                 	| BOVESPA        	| Stock Market Return Index Of Brazil          	| Quantitative 	| 0.01892, -0.013151, 0.009838    	| 0             	|
| 9                 	| EU             	| MSCI European Index                          	| Quantitative 	| 0.011341, -0.012045, 0.0328     	| 0             	|
| 10                	| EM             	| MSCI Emerging Markets Index                  	| Quantitative 	| 0.008773, -0.004029, 0.01032    	| 0             	|
---

### Acknowledgement


This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Istanbul Stock Exchange Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/ISTANBUL+STOCK+EXCHANGE). 
The UCI page mentions the following paper as the original source of the data set:

*Akbilgic, O., Bozdogan, H., Balaban, M.E., (2013) A novel Hybrid RBF Neural Networks model as a forecaster, Statistics and Computing. DOI 10.1007/s11222-013-9375-7*