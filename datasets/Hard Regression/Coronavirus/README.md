Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Intermediate <br/>
**Recommended Use:** Classification Models<br/>
**Domain:** Health Sciences<br/> 

## Coronavirus Data Set 

### Track the outbreak of coronoavirus (COVID-19) 


---
![](coronavirus.jpg)
---

The recent outbreak of the novel coronavirus has caused great concern all around the world. It has affected more around tens of thousands of people, mostly in China. 
The outbreak, originating in the Chinese city of Wuhan, has been declared a global emergency by the World Health Organization (WHO).

This data set consists of 4 files and was collected through various sources.
The data is available from 22 Jan, 2020 and was last updated on 3 March, 2020. 
The first file **covid_19_data.csv** contains daily level information on the number of 2019-nCoV affected cases across the globe.
The next 3 files contain time series data of confirmed cases, death cases and recovered cases, respectively.

The data dictionary for the first file is provided below.


---

### Data Dictionary 

| Column   Position 	| Atrribute Name        	| Definition																	|  
|-------------------	|-----------------------	|------------------------------------------------------------------------------ |
| 1                 	| Sno		              	| Serial Number					  												|
| 2                 	| ObservationDate     		| Date and time of the observation in MM/DD/YYYY HH:MM:SS       				| 
| 3                 	| Province / State   		| Province or state of the observation                          				| 
| 4                 	| Country / Region			| Country of observation                                        				| 
| 5                 	| Last Update 				| Time in UTC at which the row is updated for the given province or country. 	| 
| 6                 	| Confirmed                 | Number of confirmed cases														| 
| 7                 	| Deaths                  	| Number of deaths                                                              | 
| 8                 	| Recovered     			| Number of recovered cases                  									|

---

### Merged Data Sources

In an effort to help people stay informed and updated on Coronavirus (COVID-19), Data Science Dojo has decided to merge together several data sources of daily reports on the situation. This merged dataset includes not only the latest cases and death counts, but also the travel advisory levels and travel restrictions, by country. This will be updated daily for your convenience, with past days of the data in CSV format archived in our public git repository.  
This single view of the current status of Coronavirus is pulled, cleaned and merged daily from the World Health Organization reports, US Department of State Travel Advisories, Smart Traveller, and CNN news service. 

### Acknowledgement


This data set has been sourced from [Kaggle](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset) and [Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19). 
This dataset is provided to the public strictly for educational and academic research purposes