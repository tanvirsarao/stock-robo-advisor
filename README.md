# Robo Stock Portfolio Advisor

This is Team 7's submission to the annual CFM 101 Team Competition at the University of Waterloo, achieving **3rd place**!

## About

Our program is a Python-based portfolio optimization tool that uses LSTM neural networks, multithreading and Monte Carlo simulation to create market-matching investment portfolios.

## Features

* Advanced stock price prediction using LSTM neural networks with historical performance backtesting and visualization.
* Optimizes portfolio weights through Monte Carlo simulation while considering transaction costs and broker fees.
* Handles multi-currency (USD/CAD) trading with automated stock filtering based on volume, volatility, and market cap.
* Targets market-matching performance against S&P 500 and TSX composite indices using parallel processing for efficient computation.


## Try it out!

1. Download the `.ipynb` and `requirements.txt` files from the repo.
2. Install the dependencies in the `.txt` file.
`pip install -r dependencies.txt` in the terminal with `dependencies.txt` in your root directory.
3. Create a list of stocks which are of interest to you. The input `.csv` should contain one column of stock tickers. This would play the role of the `Tickers.csv` file in this repo.
4. Run the `.ipynb` file in an environment of your choice.

## Output

The program will generate `Final_Portfolio.csv`, containing the selected stocks and their optimal weights in the portfolio.
