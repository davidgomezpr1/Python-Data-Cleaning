# Data Cleaning of 2021 Bitcoin Data
![](https://images.unsplash.com/photo-1609726494499-27d3e942456c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80)

## Motivation

As a long-term investor wishing to grow my investment portfolio by investing into the cryptocurrency market. I decided to analyze the relationship between the price and the daily amount of coins traded, also known as trading volume, of the "crypto" gold, Bitcoin.  

Daily price and volume data relevant to Bitcoin traded was obtained from the [Yahoo Finance website](https://finance.yahoo.com/quote/BTC-USD/history). Within the framework of data applicable for analysis, the data set for this analysis includes observations for the period between January 1, 2021 and January 1, 2022.


## Overview

- Importing the Data.
- Cleaning of the data, which may include:
    - Missing values handling.
    - Removal of columns.
- Calculation of daily and weekly returns.
- Analysis of the relationship between the price and volume of Bitcoin. 
- Analysis of the distribution of the Price of Bitcoin.
- Exploratory statistical analysis to identify invalid values of Price.

## Conclusions

- The Dataset had missing values that were successfully dealt with, by filling the values using previous Price records.
- Columns that were not of interest for this analysis were dropped.
- It was concluded that there was a very weak, almost inexistent, linear relationship between the variables, due to a very small absolute correlation coefficient, -0.00056.
- The central tendency of the price of BTC was analyzed, determining that we were dealing with a symmetrical distribution.
-  An analytical analysis of invalid values was conducted.The InterQuartile Range was utilized, due to its reduced sensitiveness to outliers, and determined the upper and lower limits to be 83120.03 and 11769.59 USD, respectively. Any value above the upper limit or below the lower limit, would be considered invalid, for the period of analysis.
- Bitcoin reached its maximum price of 67,567 USD on November, 8, experiencing a bull market for the better part of the period for this analysis. This indicates that it was a good year for Bitcoin, with an annual return of 62.4%. Compare this to the annualized return of an index fund, like the S&P 500, of about 10% since inception. We can conclude that, without taking into account the risk of investment, buying Bitcoin would be a good addition to my investment portfolio.
