# Bank-of-America-Stock-Analysis

This project analyzes Bank of America's (BAC) stock performance using historical data from Yahoo Finance. It examines price movements, trends, and returns through moving averages and return calculations. Using Python-based analysis and visualization, the project provides insights into BAC’s historical behavior and potential trading signals.

## Terminologies Used in the Analysis
1. Stock Price Data

     * Open Price:The price at which a stock starts trading at the beginning of a market session.
       
     * Close Price:
       The last traded price of a stock before the market closes for the day.
       
     * High & Low Prices:
       The highest and lowest prices at which the stock traded during a given period.
       
     * Adjusted Close Price:
       The closing price adjusted for corporate actions like dividends and stock splits.
       
     * Volume:
       The number of shares traded during a given period.

3. Moving Averages (MA)

    * 20-Day Moving Average (20-MA): The average closing price of the stock over the past 20 trading days. Helps identify short-term trends.
      
    * 50-Day Moving Average (50-MA): The average closing price over the past 50 trading days. Used for longer-term trend analysis.
      
    * Golden Cross & Death Cross: A bullish signal occurs when a short-term moving average crosses above a long-term moving average (Golden Cross), while a bearish signal occurs when the short-term average crosses below the long-term average (Death Cross).

4. Returns Analysis

   * Daily Return: The percentage change in stock price from one day to the next.
   * Cumulative Return: The total return over a period, assuming all gains/losses are compounded over time

## Features:
    1. Data Collection: Retrieves BAC stock data from 2020 to 2025.
    2. Moving Averages: Calculates 20-day and 50-day moving averages to observe trends.
    3. Daily & Cumulative Returns: Computes daily percentage changes and cumulative returns over time.
    4. Visualization: Plots stock closing prices alongside moving averages for trend identification.

## Tools Used:
    Python
    Pandas & NumPy for data processing
    Matplotlib & Plotly for visualization
    yFinance for stock data retrieval


# Citations
https://blog.bytescrum.com/python-for-finance-analyzing-stock-data-with-pandas
https://medium.com/@financial_python/building-a-macd-indicator-in-python-190b2a4c1777
