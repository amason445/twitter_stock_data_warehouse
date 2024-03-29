# Warehousing Tweets and Stock Data

## Project Goals
This project aims to build a simple data warehouse in SQLite for a sample of tweets and stock data sourced from Kaggle. The data warehouse will aggregate monthly twitter mentions and volume weighted average opening and closing price

## Data Source
- Stock Tweets for Sentiment Analysis and Prediction - HANNA YUKHYMENKO
- https://www.kaggle.com/datasets/equinxx/stock-tweets-for-sentiment-analysis-and-prediction?select=stock_yfinance_data.csv

## Key Calculations
* **Volume Weighted Average Price (VWAP):** 
  - $VWAP = \frac{\sum{Volume\ \cdot\ Price}}{\sum{Volume}}$
* **Price:** 
  - $Price = \frac{(High\ +\ Low\+\ Close)}{3}$
* https://education.howthemarketworks.com/volume-weighted-average-price/

## Conclusion
Successfully created data warehouse file and met requirements. Takeaways and ideas:
- Add other stock metrics to fact table such as return data or volatility measures
- Adapt into a general SQL file for other databases
- Clean dim tables and add new external attributes like metadata or more company information
- Conform load tables to schema ERD
