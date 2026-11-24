# Stock Price Analyzer (Python)

## Overview
An interactive Python tool that shows the current price of any stock and plots
its price history with 7-day and 30-day moving averages.

## Features
- Takes any stock symbol as input (for example `HDFCBANK.NS` or `AAPL`)
- Shows the company name, current price, and daily change in price and percent
- Downloads daily price history for any date range you choose
- Calculates 7-day and 30-day moving averages
- Plots the daily price and both moving averages on one chart
- Handles wrong symbols and network problems without crashing
- Runs in a loop, so you can check many stocks. Type `Quit` to stop

## Tools Used
- Python, Pandas, NumPy, Matplotlib, Seaborn
- yfinance (Yahoo Finance data)
- Google Colab (Jupyter Notebook)

## How to Run
1. Download `Stock_Price_Analyzer.ipynb`
2. Open it in Google Colab or Jupyter
3. Install the library: `pip install yfinance`
4. Run all cells
5. Type a stock symbol, then a start date and an end date (format: yyyy-mm-dd)

## Example
Symbol: `HDFCBANK.NS`, from `2024-07-10` to `2026-06-13`

## Future Improvements
- Add more indicators, such as RSI
- Compare two stocks on one chart
- Save the charts as images
