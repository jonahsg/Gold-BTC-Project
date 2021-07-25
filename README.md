# Gold-BTC-Project


The purpose of this project is to analyze the effects of two proxies for inflation, CPI and US M2, on Gold, BTC, and S&P 500 prices.



## CPI Background Information:
“The Consumer Price Index (CPI) is a measure that examines the weighted average of prices of a basket of consumer goods and services, such as transportation, food, and medical care. It is calculated by taking price changes for each item in the predetermined basket of goods and averaging them. Changes in the CPI are used to assess price changes associated with the cost of living.

The CPI is one of the most frequently used statistics for identifying periods of inflation or deflation.” [CPI Background Info](https://www.investopedia.com/terms/c/consumerpriceindex.asp)



## M2 Background Information:
“M2 is a measure of the money supply that includes cash, checking deposits, and easily convertible near money.
M2 is a broader measure of the money supply than M1, which just includes cash and checking deposits.
M2 is closely watched as an indicator of money supply and future inflation, and as a target of central bank monetary policy.”
[M2 Background Info](https://www.investopedia.com/terms/m/m2.asp)



## Datasets Used:
Gold (Daily) [Gold Dataset](https://www.kaggle.com/sonukiller99/gold-price-from-1978-till-2020-in-24-currencies)

BTC (Daily) [BTC Dataset](https://www.kaggle.com/sudalairajkumar/cryptocurrencypricehistory?select=coin_Bitcoin.csv)

CPI (Monthly) [CPI Dataset](https://www.kaggle.com/varpit94/us-inflation-data-updated-till-may-2021)

US M2 (Weekly) [US M2 Dataset](https://fred.stlouisfed.org/series/M2#0)

S&P 500 (Daily) [S&P 500 Dataset](https://www.kaggle.com/lowerlight/original-sp-500)



## Analysis Done (High Level):

Calculated % change of US M2 and CPI

Categorized US M2 and CPI data into 'High', 'Normal', and 'Low' periods of change

Calculated % change in gold, BTC, and S&P 500 data over given US M2 and CPI timeframes

Created series for gold, BTC, and S&P 500 based on categorical change variables for US M2 and CPI

Hypothesis tested for gold, BTC, and S&P 500 between series from different categorical change variables for US M2 and CPI


