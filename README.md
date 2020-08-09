# New York Stock Exchange Stock Prediction                                                                                                                                2019
## Technology Used: R, PLOTLY, Holt-Winters, Altman Z-Score
##    Predicted the future stock prices using Holt-Winters for time series data & determined the companies that might get bankrupt in the near future using the Altman Z-Score.

### MOTIVATION AND OBJECTIVE
•	As the variation in the IT market is on a rise, we have focused on the data in the ‘Information Technology’ sector, to predict how a company might perform in the near future and determine the companies that might get bankrupt<br />
•	The analysis of the same is a sought field in finance, which could be used to protect a company by tracking its performance or to advise investors, share holders and stock market specialists to make decisions 
•	These might help to foresee any challenges pertaining to recession and help take measures to avoid it

### GOALS
•	Check for the completeness of the data and use appropriate data cleansing method 
•	Investigate data in the Information Technology sector using EDA and explore the trends of company’s stocks over a period to analyze the performance
•	Predict the future stock prices using Holt-Winters for time series data
•	Determine the companies that might get bankrupt in the near future

### DATASET DESCRIPTION
•	Includes data from 2010 to 2016, for 508 companies, and has 4 files
•	Prices.csv: raw data with daily stock prices, mostly from 2010 to 2016. For companies that are new in stock market, the date range is shorter
•	Prices-split-adjusted.csv: same as prices, with additional adjustments for splits
•	Securities.csv: details of companies with respect to sectors, regions and start date
•	Fundamentals.csv: metrics data from annual SEC 10K fillings with 78 predictors

### HOLT-WINTERS METHOD
•	Model of time series behavior allows to forecast
•	Allows to model three aspects of the time series: a typical value (average), a slope (trend) over time, and a cyclical repeating pattern (seasonality)
•	Triple exponential smoothening to encode values from past and use them to predict values for present and future

### THE Z-SCORE VALUE
•	The Altman Z-Score is used to predict the likelihood that a business will go bankrupt within the next two years 
•	The formula is based on information found in the income/balance sheet of an organization
•	It is given by:
#### 					Z = 1.2*A + 1.4*B + 3.3*C +0.6*D + 1*E
where, 
A = working capital / total assets
B = retained earnings / total assets
C = earnings before interest and tax / total assets
D = market value of equity / book value of equity
E = sales / total assets



