Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level** Intermediate <br/>
**Recommended Use:** Classification Models<br/>
**Domain:** Health Sciences <br/>

## Heart Disease Data Set

### Was that chest pain an indicator of a heart disease?


---
![](closeup-of-heart-and-a-stethoscope-cardiovascular-checkup-concept_53876-65587.jpg)
---

This *intermediate* level data set provides health examination data among 303 patients who presented with chest pain and might have been suffering from heart disease. The data set has 14 attributes including patients' age, gender, blood pressure, cholesterol level, and their heart disease status indicating whether the diagnosed patient were found to have a heart disease or not. This data set is recommended for learning and practicing your skills in **classification modelling techniques**. Feel free to do **exploratory data analysis** and **data visualization** on the data set. The Following data dictionary gives more details on this data set:

---

### Data Dictionary

**Column Position** | **Attribute Name** |  **Description**                                                                                     | **Attribute Type**    
--------------------| -------------------|  ----------------------------------------------------------------------------------------------------|------------------
     #1             |   age              |  age of the patient                                                                                  | quantitative
     #2             |   sex              |  gender of the patient                                                                               | qualitative
     #3             |   cp               |  type of chest pain (1:'Typical Angina', 2:'atypical angina', 3:'non-anginal pain', 4:'asymptomatic')| qualitative           
     #4             |   trestbps         |  resting blood pressure (in mm Hg on admission to the hospital)                                      | quantitative    
     #5             |   chol             |  serum  cholesterol in mg/dl                                                                         | quantitative     
     #6             |   fbs              |  (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)                                             | qualitative
     #7             |   restecg          |  resting ECG results (0: 'normal', 1 and 2: 'abnormal')                                              | qualitative
     #8             |   thalach          |  maximum heart rate achieved                                                                         | quantitative
     #9             |   exang            |  exercise induced angina (1 = yes; 0 = no)                                                           | qualitative
     #10            |   oldpeak          |  ST depression induced by exercise relative to rest                                                  | quantitative
     #11            |   slope            |  the slope of the peak exercise ST segment (1: 'upsloping', 2: 'flat', 3: 'down sloping)             | qualitative
     #12            |   ca               |  number of major vessels (0-3) colored by fluoroscopy                                                | qualitative   
     #13            |   thal             |  thalassemia (3: 'normal', 6: 'fixed defect' , 7: 'reversible defect')                               | qualitative    
     #14            |   num              |  angiographic disease status (0: no heart disease, > 0: heart disease)                               | qualitative

---

### Acknowledgement


This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Heart Disease Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/heart+Disease). The UCI page mentions following as the principal investigator responsible for the data collection:

* 1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
* 2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
* 3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
* 4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation:Robert Detrano, M.D., Ph.D.
