# Stock-Forecasting
Stock forecasting refers to the process of predicting the future price movement of company stocks or other financial instruments traded on the stock market. It involves analyzing historical data, market trends, and various technical and fundamental indicators to make informed guesses about where a stock’s price might go.

# yfinance
The yfinance API is a powerful tool for accessing financial data from Yahoo Finance. It allows users to download historical market data, retrieve financial information, and perform various financial analyses.
yfinance is not affiliated, endorsed, or vetted by Yahoo, Inc. It's an open-source tool that uses Yahoo's publicly available APIs, and is intended for research and educational purposes.

-- pip install yfinance
import yfinance as yf

# Prophet
Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

--pip install prophet
from prophet import Prophet

# Plotly
plotly.py is an interactive, open-source, and browser-based graphing library for Python :sparkles:
Built on top of plotly.js, plotly.py is a high-level, declarative charting library. plotly.js ships with over 30 chart types, including scientific charts, 3D graphs, statistical charts, SVG maps, financial charts, and more.

--pip install plotly
import plotly.graph_objects as go
