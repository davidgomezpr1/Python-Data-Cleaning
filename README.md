# [Project 1: Data Cleaning of 2021 Bitcoin Data](https://github.com/davidgomezpr1/Python_Data_Cleaning/blob/main/2021%20BTC%20Price%20Analysis)
![](https://thumbs.dreamstime.com/b/fluctuating-course-bitcoin-highest-capped-cryptocurrency-symbols-exchange-rates-154494448.jpg)

## Overview

- Created code to import Price Data for the cryptocurrency Bitcoin (BTC) in 2021. 
- Data was fetched from the [Yahoo Finance website](https://finance.yahoo.com/quote/BTC-USD/history).
- The Dataset had missing values that were successfully dealt with, by filling the values using previous Price
records.
- Columns that were not of interest for this analysis were dropped.
- The central tendency of the price of BTC was analyzed, determining that we were dealing with a
symmetrical distribution.
- The distribution was plotted, using both Maltplotlib and Seaborn.
- Analyzed the relationship between the price and volume of Bitcoin. Concluded that there was a very weak, almost inexistent, linear relationship between the variables, mainly due to a very small absolute correlation coefficient.
- An analytical analysis of invalid values was conducted. The InterQuartile Range was utilized, due to its
reduced sensitiveness to outliers. 
