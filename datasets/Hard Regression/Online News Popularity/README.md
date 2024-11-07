Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Advanced <br/>
**Recommended Use:** Regression/Classification Models<br/>
**Domain:** Business/Web<br/> 

## Online News Popularity Data Set 

### Predict the number of shares in social networks 


---
![](OBDL960.jpg)
---

This *advanced* level data set has 39644 rows and 61 columns.
This dataset summarizes a heterogeneous set of features about articles published by Mashable in a period of two years. 
This could be used to predict the number of shares of an article in social networks.

This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, and **regression/classification modelling techniques**. 
It also allows you to practice with large number of features. Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name                	| Definition                                                                                     	| Data Type    	| Example                                                        	| % Null Ratios 	|
|-------------------	|-------------------------------	|------------------------------------------------------------------------------------------------	|--------------	|----------------------------------------------------------------	|---------------	|
| 1                 	| URL                           	| URL Of The Article (Non-Predictive)                                                            	| Qualitative  	| "http://mashable.com/2013/01/07/amazon-instant-video-browser/" 	| 0             	|
| 2                 	| Timedelta                     	| Timedelta: Days Between The Article Publication And The Dataset   Acquisition (Non-Predictive) 	| Quantitative 	| 731                                                            	| 0             	|
| 3                 	| N_Tokens_Title                	| N_Tokens_Title: Number Of Words In The Title                                                   	| Quantitative 	| 12                                                             	| 0             	|
| 4                 	| N_Tokens_Content              	| N_Tokens_Content: Number Of Words In The Content                                               	| Quantitative 	| 219                                                            	| 0             	|
| 5                 	| N_Unique_Tokens               	| N_Unique_Tokens: Rate Of Unique Words In The Content                                           	| Quantitative 	| 0.663594467                                                    	| 0             	|
| 6                 	| N_Non_Stop_Words              	| N_Non_Stop_Words: Rate Of Non-Stop Words In The Content                                        	| Quantitative 	| 0.999999992                                                    	| 0             	|
| 7                 	| N_Non_Stop_Unique_Tokens      	| N_Non_Stop_Unique_Tokens: Rate Of Unique Non-Stop Words In The Content                         	| Quantitative 	| 0.815384609                                                    	| 0             	|
| 8                 	| Num_Hrefs                     	| Num_Hrefs: Number Of Links                                                                     	| Quantitative 	| 4                                                              	| 0             	|
| 9                 	| Num_Self_Hrefs                	| Num_Self_Hrefs: Number Of Links To Other Articles Published By Mashable                        	| Quantitative 	| 2                                                              	| 0             	|
| 10                	| Num_Imgs                      	| Num_Imgs: Number Of Images                                                                     	| Quantitative 	| 1                                                              	| 0             	|
| 11                	| Num_Videos                    	| Num_Videos: Number Of Videos                                                                   	| Quantitative 	| 0                                                              	| 0             	|
| 12                	| Average_Token_Length          	| Average_Token_Length: Average Length Of The Words In The Content                               	| Quantitative 	| 4.680365297                                                    	| 0             	|
| 13                	| Num_Keywords                  	| Num_Keywords: Number Of Keywords In The Metadata                                               	| Quantitative 	| 5                                                              	| 0             	|
| 14                	| Data_Channel_Is_Lifestyle     	| Data_Channel_Is_Lifestyle: Is Data Channel 'Lifestyle'?                                        	| Quantitative 	| 0                                                              	| 0             	|
| 15                	| Data_Channel_Is_Entertainment 	| Data_Channel_Is_Entertainment: Is Data Channel 'Entertainment'?                                	| Quantitative 	| 1                                                              	| 0             	|
| 16                	| Data_Channel_Is_Bus           	| Data_Channel_Is_Bus: Is Data Channel 'Business'?                                               	| Quantitative 	| 0                                                              	| 0             	|
| 17                	| Data_Channel_Is_Socmed        	| Data_Channel_Is_Socmed: Is Data Channel 'Social Media'?                                        	| Quantitative 	| 0                                                              	| 0             	|
| 18                	| Data_Channel_Is_Tech          	| Data_Channel_Is_Tech: Is Data Channel 'Tech'?                                                  	| Quantitative 	| 0                                                              	| 0             	|
| 19                	| Data_Channel_Is_World         	| Data_Channel_Is_World: Is Data Channel 'World'?                                                	| Quantitative 	| 0                                                              	| 0             	|
| 20                	| Kw_Min_Min                    	| Kw_Min_Min: Worst Keyword (Min. Shares)                                                        	| Quantitative 	| 0                                                              	| 0             	|
| 21                	| Kw_Max_Min                    	| Kw_Max_Min: Worst Keyword (Max. Shares)                                                        	| Quantitative 	| 0                                                              	| 0             	|
| 22                	| Kw_Avg_Min                    	| Kw_Avg_Min: Worst Keyword (Avg. Shares)                                                        	| Quantitative 	| 0                                                              	| 0             	|
| 23                	| Kw_Min_Max                    	| Kw_Min_Max: Best Keyword (Min. Shares)                                                         	| Quantitative 	| 0                                                              	| 0             	|
| 24                	| Kw_Max_Max                    	| Kw_Max_Max: Best Keyword (Max. Shares)                                                         	| Quantitative 	| 0                                                              	| 0             	|
| 25                	| Kw_Avg_Max                    	| Kw_Avg_Max: Best Keyword (Avg. Shares)                                                         	| Quantitative 	| 0                                                              	| 0             	|
| 26                	| Kw_Min_Avg                    	| Kw_Min_Avg: Avg. Keyword (Min. Shares)                                                         	| Quantitative 	| 0                                                              	| 0             	|
| 27                	| Kw_Max_Avg                    	| Kw_Max_Avg: Avg. Keyword (Max. Shares)                                                         	| Quantitative 	| 0                                                              	| 0             	|
| 28                	| Kw_Avg_Avg                    	| Kw_Avg_Avg: Avg. Keyword (Avg. Shares)                                                         	| Quantitative 	| 0                                                              	| 0             	|
| 29                	| Self_Reference_Min_Shares     	| Self_Reference_Min_Shares: Min. Shares Of Referenced Articles In   Mashable                    	| Quantitative 	| 496                                                            	| 0             	|
| 30                	| Self_Reference_Max_Shares     	| Self_Reference_Max_Shares: Max. Shares Of Referenced Articles In   Mashable                    	| Quantitative 	| 496                                                            	| 0             	|
| 31                	| Self_Reference_Avg_Sharess    	| Self_Reference_Avg_Sharess: Avg. Shares Of Referenced Articles In   Mashable                   	| Quantitative 	| 496                                                            	| 0             	|
| 32                	| Weekday_Is_Monday             	| Weekday_Is_Monday: Was The Article Published On A Monday?                                      	| Quantitative 	| 1                                                              	| 0             	|
| 33                	| Weekday_Is_Tuesday            	| Weekday_Is_Tuesday: Was The Article Published On A Tuesday?                                    	| Quantitative 	| 0                                                              	| 0             	|
| 34                	| Weekday_Is_Wednesday          	| Weekday_Is_Wednesday: Was The Article Published On A Wednesday?                                	| Quantitative 	| 0                                                              	| 0             	|
| 35                	| Weekday_Is_Thursday           	| Weekday_Is_Thursday: Was The Article Published On A Thursday?                                  	| Quantitative 	| 0                                                              	| 0             	|
| 36                	| Weekday_Is_Friday             	| Weekday_Is_Friday: Was The Article Published On A Friday?                                      	| Quantitative 	| 0                                                              	| 0             	|
| 37                	| Weekday_Is_Saturday           	| Weekday_Is_Saturday: Was The Article Published On A Saturday?                                  	| Quantitative 	| 0                                                              	| 0             	|
| 38                	| Weekday_Is_Sunday             	| Weekday_Is_Sunday: Was The Article Published On A Sunday?                                      	| Quantitative 	| 0                                                              	| 0             	|
| 39                	| Is_Weekend                    	| Is_Weekend: Was The Article Published On The Weekend?                                          	| Quantitative 	| 0                                                              	| 0             	|
| 40                	| Lda_00                        	| Lda_00: Closeness To Lda Topic 0                                                               	| Quantitative 	| 0.500331204                                                    	| 0             	|
| 41                	| Lda_01                        	| Lda_01: Closeness To Lda Topic 1                                                               	| Quantitative 	| 0.37827893                                                     	| 0             	|
| 42                	| Lda_02                        	| Lda_02: Closeness To Lda Topic 2                                                               	| Quantitative 	| 0.040004675                                                    	| 0             	|
| 43                	| Lda_03                        	| Lda_03: Closeness To Lda Topic 3                                                               	| Quantitative 	| 0.041262648                                                    	| 0             	|
| 44                	| Lda_04                        	| Lda_04: Closeness To Lda Topic 4                                                               	| Quantitative 	| 0.040122544                                                    	| 0             	|
| 45                	| Global_Subjectivity           	| Global_Subjectivity: Text Subjectivity                                                         	| Quantitative 	| 0.521617145                                                    	| 0             	|
| 46                	| Global_Sentiment_Polarity     	| Global_Sentiment_Polarity: Text Sentiment Polarity                                             	| Quantitative 	| 0.092561983                                                    	| 0             	|
| 47                	| Global_Rate_Positive_Words    	| Global_Rate_Positive_Words: Rate Of Positive Words In The Content                              	| Quantitative 	| 0.0456621                                                      	| 0             	|
| 48                	| Global_Rate_Negative_Words    	| Global_Rate_Negative_Words: Rate Of Negative Words In The Content                              	| Quantitative 	| 0.01369863                                                     	| 0             	|
| 49                	| Rate_Positive_Words           	| Rate_Positive_Words: Rate Of Positive Words Among Non-Neutral   Tokens                         	| Quantitative 	| 0.769230769                                                    	| 0             	|
| 50                	| Rate_Negative_Words           	| Rate_Negative_Words: Rate Of Negative Words Among Non-Neutral   Tokens                         	| Quantitative 	| 0.230769231                                                    	| 0             	|
| 51                	| Avg_Positive_Polarity         	| Avg_Positive_Polarity: Avg. Polarity Of Positive Words                                         	| Quantitative 	| 0.378636364                                                    	| 0             	|
| 52                	| Min_Positive_Polarity         	| Min_Positive_Polarity: Min. Polarity Of Positive Words                                         	| Quantitative 	| 0.1                                                            	| 0             	|
| 53                	| Max_Positive_Polarity         	| Max_Positive_Polarity: Max. Polarity Of Positive Words                                         	| Quantitative 	| 0.7                                                            	| 0             	|
| 54                	| Avg_Negative_Polarity         	| Avg_Negative_Polarity: Avg. Polarity Of Negative Words                                         	| Quantitative 	| -0.35                                                          	| 0             	|
| 55                	| Min_Negative_Polarity         	| Min_Negative_Polarity: Min. Polarity Of Negative Words                                         	| Quantitative 	| -0.6                                                           	| 0             	|
| 56                	| Max_Negative_Polarity         	| Max_Negative_Polarity: Max. Polarity Of Negative Words                                         	| Quantitative 	| -0.2                                                           	| 0             	|
| 57                	| Title_Subjectivity            	| Title_Subjectivity: Title Subjectivity                                                         	| Quantitative 	| 0.5                                                            	| 0             	|
| 58                	| Title_Sentiment_Polarity      	| Title_Sentiment_Polarity: Title Polarity                                                       	| Quantitative 	| -0.1875                                                        	| 0             	|
| 59                	| Abs_Title_Subjectivity        	| Abs_Title_Subjectivity: Absolute Subjectivity Level                                            	| Quantitative 	| 0                                                              	| 0             	|
| 60                	| Abs_Title_Sentiment_Polarity  	| Abs_Title_Sentiment_Polarity: Absolute Polarity Level                                          	| Quantitative 	| 0.1875                                                         	| 0             	|
| 61                	| Shares                        	| Shares: Number Of Shares                                                                       	| Quantitative 	| 593                                                            	| 0             	|

---

### Acknowledgement

This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Online News Popularity Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity). 
The UCI page mentions the following publication as the original source of the data set:

*K. Fernandes, P. Vinagre and P. Cortez. A Proactive Intelligent Decision Support System for Predicting the Popularity of Online News. Proceedings of the 17th EPIA 2015 - Portuguese Conference on Artificial Intelligence, September, Coimbra, Portugal*

