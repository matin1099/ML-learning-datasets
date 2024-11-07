Data Science Dojo  <br/>
Copyright (c) 2019 - 2020

---

**Level:** Beginner <br/>
**Recommended Use:** Regression  <br/>
**Domain:** Transportation and Mobility <br/>

---

### Interstate-94 (I-94) Traffic Volume Dataset

---
![](Interstate94.jpg)
---


The Interstate Traffic Volume Dataset contains information about the hourly traffic volume on the West-bound lane of Interstate-94 (I-94) in the US. The dataset includes hourly weather and temperature reports from 2012 to 2018.

The information in the dataset can be used to understand the flow of traffic on the interstate with respect to time and date and can be helpful in prediction of rush hours, weather forecasting as well as planning expansions of interstates and highways in the US. 

This data set is recommended for exploring data visualization techniques and implementing regression models for prediction tasks.

---

### Data Dictionary

| Column Number | Attribute           | Attribute Description                            | Data Type |
| ------------- | ------------------- | ------------------------------------------------ | --------- |
| 1             | holiday             | Categorical US Holidays                          | Text      |
| 2             | temp                | Average Temperature (Kelvin)                     | Numeric   |
| 3             | rain_1h             | Amount of rain (in mm) in the last hour          | Numeric   |
| 4             | snow_1h             | Amount of snow (in mm) in the last hour          | Numeric   |
| 5             | clouds_all          | Percentage of Cloud Cover                        | Numeric   |
| 6             | weather_main        | Short Description of Weather in the last hour    | Text      |
| 7             | weather_description | Detailed Description of Weather in the last hour | Text      |
| 8             | date_time           | Date and Time of Data Point                      | Date/Time |
| 9             | traffic_volume      | Traffic Volume reported on I-94 in the last hour | Numeric   |

---

### Acknowledgement

This data set has been sourced from the Machine Learning Repository of
University of California, Irvine [Metro Interstate Traffic Volume Dataset (UC
Irvine)](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume).  
The UCI page mentions the following individual as the original source of the
data set:  
*John Hogue, john.d.hogue '@' live.com, Social Data Science & General Mills*
