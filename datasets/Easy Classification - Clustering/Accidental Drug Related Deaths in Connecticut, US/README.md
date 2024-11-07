Data Science Dojo  <br/>
Copyright (c) 2019 - 2020

---

**Level:** Beginner <br/>
**Recommended Use:** Classification  <br/>
**Domain:** Health/Social Sciences <br/>

---

### Accidental Drug Related Deaths in Connecticut, US

---
![](IllegalDrugAbuse.jpg)
---


The Connecticut Deaths due to Drugs Dataset contains information about 5106 people who died due to drug overdose between 2012 and 2018 in Connecticut, US.

The dataset includes data related to the age, race, gender, place of residence of the victims as well as the drugs they overdosed on. This information can be used to understand if drug use is prevalent in a specific area or city, drug use by individuals of different age groups and races as well as the popularity of different types of drugs.
 
This dataset is recommended for exploring data visualization techniques, clustering techniques and implementing regression models to predict how drug use may increase over time. 

---

### Data Dictionary

| Column Number | Attribute           | Attribute Description                                             | Data Type |
| ------------- | ------------------- | ----------------------------------------------------------------- | --------- |
| 1             | ID                  | Row ID                                                            | Text      |
| 2             | Date                | Date                                                              | Date/Time |
| 3             | DateType            | Type of Date in Column 2 <br>[Date of Reporting ot Date of Death] | Text      |
| 4             | Age                 | Age of Patient                                                    | Numeric   |
| 5             | Sex                 | Sex of Patient                                                    | Text      |
| 6             | Race                | Race of Patient                                                   | Text      |
| 7             | ResidenceCity       | City of Residence                                                 | Text      |
| 8             | ResidenceCounty     | County of Residence                                               | Text      |
| 9             | ResidenceState      | State of Residence                                                | Text      |
| 10            | DeathCity           | City of Death                                                     | Text      |
| 11            | DeathCounty         | County of Death                                                   | Text      |
| 12            | Location            | Location of Death [Hospital or Residence]                         | Text      |
| 13            | LocationifOther     | Location of Death if Not Hospital or Residence                    | Text      |
| 14            | DescriptionofInjury | Cause of Death                                                    | Text      |
| 15            | InjuryPlace         | Place of Event that caused Death                                  | Text      |
| 16            | InjuryCity          | City of Event that caused Death                                   | Text      |
| 17            | InjuryCounty        | County of Event that caused Death                                 | Text      |
| 18            | InjuryState         | State of Event that caused Death                                  | Text      |
| 19            | COD                 | Detailed Cause of Death                                           | Text      |
| 20            | OtherSignifican     | Other Significant Injuries that may have lead to Death            | Text      |
| 21            | Heroin              | Drug Found in Body [Y/N]                                          | Text/Bool |
| 22            | Cocaine             | Drug Found in Body [Y/N]                                          | Text/Bool |
| 23            | Fentanyl            | Drug Found in Body [Y/N]                                          | Text/Bool |
| 24            | FentanylAnalogue    | Drug Found in Body [Y/N]                                          | Text/Bool |
| 25            | Oxycodone           | Drug Found in Body [Y/N]                                          | Text/Bool |
| 26            | Oxymorphone         | Drug Found in Body [Y/N]                                          | Text/Bool |
| 27            | Ethanol             | Drug Found in Body [Y/N]                                          | Text/Bool |
| 28            | Hydrocodone         | Drug Found in Body [Y/N]                                          | Text/Bool |
| 29            | Benzodiazepine      | Drug Found in Body [Y/N]                                          | Text/Bool |
| 30            | Methadone           | Drug Found in Body [Y/N]                                          | Text/Bool |
| 31            | Amphet              | Drug Found in Body [Y/N]                                          | Text/Bool |
| 32            | Tramad              | Drug Found in Body [Y/N]                                          | Text/Bool |
| 33            | Morphine_NotHeroin  | Drug Found in Body [Y/N]                                          | Text/Bool |
| 34            | Hydromorphone       | Drug Found in Body [Y/N]                                          | Text/Bool |
| 35            | Other               | Drug Found in Body [Y/N]                                          | Text/Bool |
| 36            | OpiateNOS           | Drug Found in Body [Y/N]                                          | Text/Bool |
| 37            | AnyOpioid           | Drug Found in Body [Y/N]                                          | Text/Bool |
| 38            | MannerofDeath       | Manner of Death                                                   | Text      |
| 39            | DeathCityGeo        | City of Death                                                     | Text      |
| 40            | ResidenceCityGeo    | City of Residence                                                 | Text      |
| 41            | InjuryCityGeo       | City of Injury                                                    | Text      |


---

### Acknowledgement

This data set has been sourced from the [US Government's 
Open Data Initiative](https://data.gov) [Accidental Drug Related Deaths Dataset](https://catalog.data.gov/dataset/accidental-drug-related-deaths-january-2012-sept-2015).  
The Open Data Initiative page mentions the following as the original source of the
data set:  
*Local Government, Connecticut*
