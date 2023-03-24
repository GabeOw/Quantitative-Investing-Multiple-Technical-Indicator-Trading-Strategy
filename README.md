# Quantitative-Investing-Trading-Strategy Project

## Introduction 

- Technical indicators are frequently used tools by investors and traders. They implement mathematically based formulas to analyze past data to identify future trading opportunities. Through analyzing historical data, technical analysts use indicators to try and create trading strategies. In this article, we use Python to explore a specific trading strategy based on a combination of 7 of the most commonly used indicators. We generate trading signals based on a defined set of rules, backtest our strategy, and form an optimally weighted portfolio. Our goal is to outperform a standard buy-and-hold strategy of the SPY ETF over a defined period of time. 

## Dataset 
- Nasdaq-100 company daily data for each ticker from January 2000-01-01 to the present. In addition, daily SPY ETF data is used for benchmark stats.

## Factors/Performance Indicators 
- We selected 7 technical indicators for further strategy construction based on research:
  - Simple Moving Average (Price)
  - Simple Moving Average (Volume)
  - Average True Range
  - Stochastic Oscillator
  - Relative Strength Index
  - Moving Average Convergence/Divergence (MACD)

## Trading Strategy
- Our trading strategy makes use of all aforementioned indicators. We will buy the stock when all of the seven indicators show a buy signal, and will sell the same stock if just one of the indicators shows a sell signal. At any point in time in between, we are either holding or have no position in the stock. This methodology applies to all stocks in our portfolio. 

## Risk-Managemnent, Weighting Strategy
We employ the efficient frontier technique and plot returns against volatility to optimize our portfolio's risk and return. We use the Sharpe ratio to identify the optimal risky portfolio with the highest expected return for each risk level, while considering a risk-free rate of 0.01.

##Results and Conclusion
- Our trading strategy outperformed a buy and hold SPY strategy over the years 2000-01-01 to present day by 2235.51%. The addition of indicators, risk management, and weighting proved very useful in predicting buying and selling opportunities. 
  - Improvements to our model and realistic next steps could include:
  -  Testing and comparing various time periods
  - Expanding our dataset to include stocks outside the NASDAQ100
  - Adding additional indicators
  - Implementing more advanced smoothing techniques
  - Incorporating more fundamental analysis
  - Use machine learning techniques within our strategy 

