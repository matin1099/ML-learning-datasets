Data Science Dojo  <br/>
Copyright (c) 2019 - 2020

---

**Level:** Intermediate <br/>
**Recommended Use:** Regression  <br/>
**Domain:** Social Sciences <br/>

---

## EU Population Poverty Status Dataset

### Population unable to keep home adequately warm by poverty status

---
![](EUPoverty.jpg)
---


This dataset provides information about the percentage of population in each EU Country that cannot afford basic indoor heating from 2003 to 2019. It is a good indicator of the percentage of population in the EU that is living close to or below the poverty line.

The dataset can be used to understand if the poor population in the EU has grown over the last 15 years and can be used to predict how the population will change in the years to come.

This data set is recommended for exploring data visualization techniques and implementing regression models for prediction tasks.

---

### Data Dictionary

| Column Number | Attribute   | Attribute Description                                                                                           | Data Type |
| ------------- | ----------- | --------------------------------------------------------------------------------------------------------------- | --------- |
| 1             | hhtyp       | Total                                                                                                           | Text      |
|               | incgrp      | Income Group<br>[A_MD60: Above 60% of Median Equalized Income,<br>B_MD60: Below 60% of Median Equalized Income] | Text      |
|               | unit        | Data Type of Values in the table <br>[PC: Percentage]                                                           | Text      |
|               | geo         | Country in EU.                                                                                                  | Text      |
| 2-18          | 2003 - 2019 | Data Points (in percentage) for years between 2003 to 2019                                                      | Numeric   |


| Special Character | Description                   |
| ----------------- | ----------------------------- |
| :                 | Data not Available            |
| e                 | Data Point has been Estimated |
| b                 | Break in Time Series          |
| p                 | Provisional                   |


---

### Acknowledgement

This data set has been sourced from the [EU Open Data Portal](https://data.europa.eu/euodp/data/dataset/2yoXfAzeAb5AoFO7BSvX2g).  
The EU Open Data Portal mentions the following survery as the original source of the
data set:  
*European Union Statistics on Income and Living Conditions (EU-SILC)*
