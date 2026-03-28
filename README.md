# Stock Return Analyzer

## Overview
A quantitative analysis of 5 NSE-listed Indian stocks 
over a 5-year period (2019-2024) using Python.

## Stocks Analyzed
- Reliance Industries (RELIANCE.NS)
- TCS (TCS.NS)
- HDFC Bank (HDFCBANK.NS)
- Infosys (INFY.NS)
- Wipro (WIPRO.NS)

## What This Project Does
- Downloads 5 years of real historical price data using yFinance
- Calculates daily log returns for each stock
- Computes annualised return, volatility and Sharpe ratio
- Calculates 30-day rolling volatility to track risk over time
- Plots cumulative returns, rolling volatility, 
  return distributions and Sharpe ratio comparison

## Key Findings
- INFY had the best risk-adjusted performance 
  (Sharpe ratio 0.47)
- HDFCBANK had the weakest risk-adjusted performance 
  (Sharpe ratio 0.16)
- RELIANCE was the most volatile stock 
  (30.32% annualised volatility)
- COVID-19 crash clearly visible in rolling volatility 
  chart — volatility spiked to 100% annualised in 2020
- Return distributions show excess kurtosis — 
  fatter tails than normal distribution — 
  which has direct implications for risk models 
  that assume normality

## Tools and Libraries
- Python
- Pandas — data manipulation
- NumPy — numerical calculations
- Matplotlib — visualisation
- yFinance — market data download
- SciPy — statistical functions

## Skills Demonstrated
- Financial data analysis
- Statistical analysis of returns
- Risk metrics calculation
- Data visualisation
- Quantitative reasoning
