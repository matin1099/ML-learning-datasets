Data Science Dojo <br/>
Copyright (c) 2019 - 2020

---

**Level:** Intermediate <br/>
**Recommended Use:** Clustering/Regression/Classification Models<br/>
**Domain:** Business/Finance<br/> 

## Dow Jones Index Data Set 

### Predict which stock will provide greatest rate of return 


---
![](9.jpg)
---

This *intermediate* level data set has 750 rows and 16 columns.
This dataset contains weekly data for the Dow Jones Industrial Index. It has been used in computational investing research.
In this dataset, each record (row) is data for a week. Each record also has the percentage of return that stock has in the following week (percent_change_next_weeks_price). 
Ideally, this could be used to determine which stock will produce the greatest rate of return in the following week. 

This data set is recommended for learning and practicing your skills in **exploratory data analysis**, **data visualization**, **clustering** and **regression/classification modelling techniques**. 
Feel free to explore the data set with multiple **supervised** and **unsupervised** learning techniques. The Following data dictionary gives more details on this data set:

---

### Data Dictionary 

| Column   Position 	| Atrribute Name                     	| Definition                                                                                                                                                      	| Data Type    	| Example                               	| % Null Ratios 	|
|-------------------	|------------------------------------	|-----------------------------------------------------------------------------------------------------------------------------------------------------------------	|--------------	|---------------------------------------	|---------------	|
| 1                 	| quarter                            	| Quarter: the   yearly quarter (1: Jan-Mar; 2: Apr-Jun).                                                                                                         	| Quantitative 	| 1, 2                                  	| 0             	|
| 2                 	| stock                              	| Stock: the   stock symbol*                                                                                                                                      	| Qualitative  	| INTC, INTC, BA                        	| 0             	|
| 3                 	| date                               	| Date: the last   business day of the work (this is typically a Friday)                                                                                          	| Quantitative 	| 40564, 40683, 40620                   	| 0             	|
| 4                 	| open                               	| Open: the   price of the stock at the beginning of the week                                                                                                     	| Quantitative 	| $21.03, $23.32, $71.17                	| 0             	|
| 5                 	| high                               	| High: the   highest price of the stock during the week                                                                                                          	| Quantitative 	| $21.2, $23.96, $71.23                 	| 0             	|
| 6                 	| low                                	| Low: the   lowest price of the stock during the week                                                                                                            	| Quantitative 	| $20.62, $23.08, $67.34                	| 0             	|
| 7                 	| close                              	| Close: the   price of the stock at the end of the week                                                                                                          	| Quantitative 	| $20.82, $23.22, $69.1                 	| 0             	|
| 8                 	| volume                             	| Volume: the   number of shares of stock that traded hands in the week                                                                                           	| Quantitative 	| 218479469, 387571150, 29746370        	| 0             	|
| 9                 	| percent_change_price               	| Percent_Change_Price:   the percentage change in price throughout the week                                                                                      	| Quantitative 	| -0.998573, -0.428816, -2.90853        	| 0             	|
| 10                	| percent_change_volume_over_last_wk 	| Percent_Change_Volume_Over_Last_Week:   the percentage change in the number of shares of stock that traded hands   for this week compared to the previous week  	| Quantitative 	| -20.29526016, 12.41924755, 16.3954667 	| 4             	|
| 11                	| previous_weeks_volume              	| Previous_Weeks_Volume:   the number of shares of stock that traded hands in the previous week                                                                   	| Quantitative 	| 274111012, 344755154, 25556296        	| 4             	|
| 12                	| next_weeks_open                    	| Next_Weeks_Open:   the opening price of the stock in the following week                                                                                         	| Quantitative 	| $21.03, $22.92, $70.29                	| 0             	|
| 13                	| next_weeks_close                   	| Next_Weeks_Close:   the closing price of the stock in the following week                                                                                        	| Quantitative 	| $21.46, $22.21, $73.34                	| 0             	|
| 14                	| percent_change_next_weeks_price    	| Percent_Change_Next_Weeks_Price:   the percentage change in price of the stock in the                                                                           	| Quantitative 	| 2.0447, -3.09773, 4.33917             	| 0             	|
| 15                	| days_to_next_dividend              	| Following Week   Days_to_next_dividend: the number of days until the next dividend                                                                              	| Quantitative 	| 13, 75, 54                            	| 0             	|
| 16                	| percent_return_next_dividend       	| Percent_Return_Next_Dividend:   the percentage of return on the next dividend                                                                                   	| Quantitative 	| 0.864553, 0.904393, 0.607815          	| 0             	|

---
*Stock Symbols:<br/>
3M		 	MMM<br/>
American Express 	AXP<br/>
Alcoa			AA<br/>
AT&T 			T<br/>
Bank of America		BAC<br/>
Boeing 		 	BA<br/>
Caterpillar 	 	CAT<br/>
Chevron 	 	CVX<br/>
Cisco Systems 		CSCO<br/>
Coca-Cola 	 	KO<br/>
DuPont 		 	DD<br/>
ExxonMobil 	 	XOM<br/>
General Electric 	GE<br/>
Hewlett-Packard		HPQ<br/>
The Home Depot 	 	HD<br/>
Intel 		 	INTC<br/>
IBM 		 	IBM<br/>
Johnson & Johnson 	JNJ<br/>
JPMorgan Chase 	 	JPM<br/>
Kraft			KRFT<br/>
McDonald's 		MCD<br/>
Merck 		 	MRK<br/>
Microsoft 	 	MSFT<br/>
Pfizer 		 	PFE<br/>
Procter & Gamble 	PG<br/>
Travelers 	 	TRV<br/>
United Technologies 	UTX<br/>
Verizon 	 	VZ<br/>
Wal-Mart 	 	WMT<br/>
Walt Disney 	 	DIS<br/>

---
### Acknowledgement

This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Dow Jones Index Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Dow+Jones+Index). 
The UCI page mentions the following publication as the original source of the data set:

*Brown, M. S., Pelosi, M. & Dirska, H. (2013). Dynamic-radius Species-conserving Genetic Algorithm for the Financial Forecasting of Dow Jones Index Stocks. Machine Learning and Data Mining in Pattern Recognition, 7988, 27-41*

