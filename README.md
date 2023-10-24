# Python-Pandas-and-Dataframe_Company-Stocks

Assignment 4: Find all dividends.
This assignment uses Pandas. 

Data Preparation: Use the 6 stocks ['IBM', 'MSFT', 'GOOG', 'AAPL', 'AMZN', 'FB'] historical data.

Load the data to dataframes: will have 6 dataframes loaded by Pandas.

Understand how to compute the dividends:
There are two columns in each csv file, "Close" and "Adj Close". If we compute the ratio of previous day's "Close" price and today's "Close" price, then compare with the ratio of previous day's "Adj Close" price and today's "Adj Close" price, on most of days, the two ratios should be equal. On dividend day, the two ratios will have a difference. The difference times today's "Close" price, will get the dividend.

The result has 6 dataframes, each of them has two columns: Date and Dividend. The dataframe only has the rows that represent the divident day and amount.
