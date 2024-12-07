# Week 1: Pairs Trading with ML

## Overview

This week’s assignment introduces **Pairs Trading**, a market-neutral trading strategy where positions are taken in two correlated stocks. The aim is to predict the price ratio of the two stocks using **Machine Learning (ML)** techniques and generate trading signals.

By completing this assignment, you will:
1. Understand the concept of pairs trading.
2. Implement a trading strategy using historical stock data.
3. Train a machine learning model to predict stock price ratios.
4. Simulate the trading strategy and evaluate its performance based on profit and loss (PnL).

---

## Getting Started

### Step 1: Learn About Pairs Trading

Start by reading about the fundamentals of pairs trading. Here are some helpful resources:
- [Investopedia: Pairs Trading Basics](https://www.investopedia.com/terms/p/pairs_trade.asp)
- [Medium Article: A Gentle Introduction to Pairs Trading](https://medium.com)

---

### Step 2: Understand the Code and Supplementary Materials

1. **`Introduction_To_Pairs_Trading.ipynb`**: This notebook contains the implementation of the pairs trading strategy. It includes:
   - Fetching stock price data from Yahoo Finance.
   - Engineering features based on stock price ratios and technical indicators.
   - Training an ML model to predict future price ratios.
   - Simulating the trading strategy based on predictions.

2. **Supplementary Document**: Read it side-by-side with the jupyter notebook, to understand deeply the basic fundamentals introduced there.

3. **`ADF_Examples.ipynb`**: This file contains examples of the Augmented Dickey-Fuller (ADF) test, a statistical test for stationarity. Refer to this for understanding how stationarity is crucial for pairs trading.

---

### Step 3: Complete the Assignment

1. **Assignment Notebook**: Start working on the assignment notebook for this week. You are required to:
   - Fetch stock data for two selected companies.
   - Create technical features.
   - Train a Random Forest Regressor to predict price ratios (or any other ML model). Reach out to anyone of us, in case you are new to ML.
   - Generate buy/sell signals based on predictions.
   - Simulate and evaluate your trading strategy.

2. **Submission**: Ensure your code is well-commented, and include all relevant plots and explanations. Submit your notebook by the end of the week.

---

## Notes

- This assignment requires Python programming and familiarity with libraries like `pandas`, `numpy`, `sklearn`, `statsmodels` and `matplotlib`.
- If you encounter issues, refer to the supplementary materials or ask for help to anyone of us.

May the Profit be with you!
