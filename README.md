# Portfolio Optimization & Risk Analytics

## Overview

This project applies Modern Portfolio Theory (MPT) and Monte Carlo Simulation to construct an optimal investment portfolio using historical stock market data. The objective is to maximize risk-adjusted returns by identifying the portfolio with the highest Sharpe Ratio while analyzing portfolio risk and diversification.

## Features

- Downloaded historical stock data using Yahoo Finance
- Calculated daily and annualized returns
- Computed the covariance matrix for portfolio risk analysis
- Simulated 100,000 random portfolios using Monte Carlo Simulation
- Identified the Maximum Sharpe Ratio and Minimum Volatility portfolios
- Visualized the Efficient Frontier
- Generated portfolio allocation, correlation heatmap, cumulative returns, and risk-return plots

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yfinance

## Key Concepts

- Modern Portfolio Theory (MPT)
- Portfolio Optimization
- Monte Carlo Simulation
- Sharpe Ratio
- Diversification
- Risk-Return Tradeoff
- Covariance Matrix

## Results

- Evaluated over 100,000 simulated portfolios
- Identified the optimal portfolio based on the highest Sharpe Ratio
- Compared optimal and minimum-risk portfolios
- Demonstrated the impact of diversification on portfolio performance

## How to Run

1. Clone the repository.
2. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn yfinance
```

3. Open the Jupyter Notebook and run all cells.

## Future Improvements

- Add optimization using `scipy.optimize`
- Include portfolio constraints
- Compare against benchmark indices (NIFTY 50)
- Incorporate additional financial metrics such as Sortino Ratio and Value at Risk (VaR)
