## Research Proposal: < Title >¶
By Keyi Huang, Zhongrui Zhang, Chengming Weng, Jie Lin
---
### Research Question¶
#### Bigger problem: How is the tech sector doing in the stock market, and what are the trends in the future？
#### Smaller questions:
    1. What are the variables that would affect the tech sector the most?
    2. What is the best model (among linear regression, time series, and deep learning) to predict the tech sector?
    3. How does the “best model” fit Tesla’s stock?
### Initial hypotheses: 

The “best model” can accurately predict stock returns of firms in the tech sector by using the selected variables.

### Metrics of success: 

The predicted Tesla stock return looks roughly the same as the actual return. If there are significant discrepancies, we are able to find the causes.
---
### Necessary Data¶
1. Sample period: 2012-2021
2. Observations: Top 50 technology firms based on market cap.
3. Sample conditions: The selected subsample, 50 technology companies’ stock price movement, is corresponding to the entire technology industry market performance. Firms with smaller market cap are excluded, as they may have less impact on the overall technology sector.
4. Necessary variables: 
    1. Regression model: 
    exchange rate, interest rate, Twitter tweets, stock prices
    2. Time series model: 
    historical stock prices with time stamps
    3. Deep learning model: 
    Date,"High", "Low", "Close", "Volume", "Adj Close" of each stock
    
### Data we have and data we need
1. Data we have
    1. List of top 50 technology firms based on market cap: CSV file
    2. Stock data from Yahoo Finance: CSV file
    3. Historical interest rates
2. Data we need: 
Twitter tweet or new titles

### How will we collect more data


### What are the raw inputs and how will you store them.
1. Create an “input” folder to store company data. Import 50 companies’ stock data from Yahoo Finance to an individual data frame. 
2. “text file” for twitter textual analysis?

### Speculate at a high level (not specific code!) about how you’ll transform the raw data into the final form.
1. Stock prices will be transformed into stock returns.
2. Text elements will be quantified into ratings and classifications.

