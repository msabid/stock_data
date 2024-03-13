# stock_data
This repository contains historical stock price data obtained from Yahoo Finance using yfinance library. Data includes daily stock prices and trading volume for AAPL from 2020-01-01 to 2024-03-12.



# Historical Stock Price Dataset

## Overview
This repository contains historical stock price data obtained from Yahoo Finance using the yfinance library in Python. The dataset includes daily stock prices and trading volume for AAPL (Apple Inc.) from January 1, 2020, to March 12, 2024.

## Dataset Details
- Ticker Symbol: AAPL (Apple Inc.)
- Start Date: January 1, 2020
- End Date: March 12, 2024

## File Structure
- `aapl_ticker.csv`: CSV file containing the historical stock price data.

## Usage
You can use this dataset for various data analysis and machine learning projects, such as stock price prediction, trend analysis, and financial modeling.

## Dependencies
- Python 3.x
- yfinance library

## Usage Example
```python
import pandas as pd

# Load the dataset
stock_data = pd.read_csv('aapl_ticker.csv')

# Start exploring the data
print(stock_data.head())
