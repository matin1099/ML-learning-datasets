Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Beginner <br/>
**Recommended Use:** Classification Models<br/>
**Domain:** Finance/Banking<br/> 

## Qualitative Bankruptcy Data Set 

### Estimate chance of Bankruptcy from Qualitative parameters from experts 

---
![](407.jpg)
---

This *beginner* level data set has 250 rows and 7 columns.
This dataset contains 6 qualitative parameters from experts which could be used to predict the bankruptcy.
This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, and **classification modelling techniques**. 
Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name        	| Definition                                                   	| Data Type   	| Example 	| % Null Ratios 	|
|-------------------	|-----------------------	|--------------------------------------------------------------	|-------------	|---------	|---------------	|
| 1                 	| Industrial Risk       	| Industrial Risk (P: Positive, A: Average, N: Negative)       	| Qualitative 	| P, A, N 	| 0             	|
| 2                 	| Management Risk       	| Management Risk (P: Positive, A: Average, N: Negative)       	| Qualitative 	| P, A, N 	| 0             	|
| 3                 	| Financial Flexibility 	| Financial Flexibility (P: Positive, A: Average, N: Negative) 	| Qualitative 	| P, A, N 	| 0             	|
| 4                 	| Credibility           	| Credibility (P: Positive, A: Average, N: Negative)           	| Qualitative 	| P, A, N 	| 0             	|
| 5                 	| Competitiveness       	| Competitiveness (P: Positive, A: Average, N: Negative)       	| Qualitative 	| P, A, N 	| 0             	|
| 6                 	| Operating Risk        	| Operating Risk (P: Positive, A: Average, N: Negative)        	| Qualitative 	| P, A, N 	| 0             	|
| 7                 	| Class                 	| Class (B: Bankruptcy, NB: Non-Bankruptcy)                    	| Qualitative 	| B, NB   	| 0             	|
---
Following are the details of the qualitative risk factors which mentions their risk components:

**i.Industry risk (IR):** 
	Government policies and International agreements, 
	Cyclicality, 
	Degree of competition,				
	The price and stability of market supply,
	The size and growth of market demand,	
	The sensitivity to changes in macroeconomic factors,
	Domestic and international competitive power, 
	Product Life Cycle.

**ii.Management risk(MR):** 
	Ability and competence of management, 
	Stability of management,
	The relationship between management/ owner, 
	Human resources management, 
	Growth process/business performance, 
	Short and long term business planning, 
	achievement and feasibility. 

**iii.Financial Flexibility(FF):** 
	Direct financing, 
	Indirect financing, 
	Other financing 

**iv.Credibility (CR):**  
	Credit history,  
	reliability of information, 
	The relationship with financial institutes.

**v.Competitiveness (CO):**  
	Market position, 
	The level of core capacities, 
	Differentiated strategy, 

**vi.Operating Risk (OP):**  
	The stability and diversity of procurement, 
	The stability of transaction, 
	The efficiency of production, 
	The prospects for demand for product and service, 
	Sales diversification,
	Sales price and settlement condition, 
	Collection of A/R,
	Effectiveness of sale network.

---
### Acknowledgement

This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Qualitative Bankruptcy Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Qualitative_Bankruptcy). 
The UCI page mentions the following publication as the original source of the data set:

*"The discovery of experts’	decision rules from qualitative bankruptcy data using genetic algorithms" by Myoung-Jong Kim, Ingoo Han*

