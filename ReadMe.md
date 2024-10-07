# Cointegration-Based Statistical Arbitrage Strategy

## Project Goals
This project implements a cointegration-based statistical arbitrage trading strategy using stock pairs from the S&P 500 index. The key objectives are to:
- Identify cointegrated stock pairs with stationarity using the Augmented Dickey-Fuller (ADF) test.
- Calculate the half-life of mean reversion for the residuals between cointegrated pairs.
- Backtest a pairs trading strategy based on z-score signals of the residuals.
- Evaluate the performance using metrics like Sharpe ratio and total returns.

## Technologies Used
- **Programming Languages**: Python
- **Libraries**: 
  - `pandas` for data manipulation.
  - `yfinance` for fetching historical stock data.
  - `matplotlib` for plotting stock prices and residuals.
  - `statsmodels` for cointegration and ADF tests.
  - `sklearn` for machine learning models (used for future extensions).
  - `numpy` for numerical operations.

  