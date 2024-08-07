# Google-Stock-Market-Analysis-


![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-Enabled-orange)

## Introduction
This is a practice project involves analyzing Google's stock market data and predicting future stock prices using linear regression. It serves as a practice project to understand the application of linear regression in financial data analysis.

# What is Linear Regression
Linear regression is a statistical method used to model the relationship between a dependent variable (often called the target or outcome variable) and one or more independent variables (often called predictors or features). The goal is to find the best-fitting straight line through the data points that predicts the dependent variable as accurately as possible.



## Table of Contents
- [Introduction](#introduction)
- [Process](#features)
- [Data](#data)
- [Results](#results)
- [Contributing](#contributing)


## Process
- Data collection and preprocessing
- Data visualization
- Linear regression model training
- Stock price prediction
- Evaluation of model performance

## Data
The data used in this project is historical stock price data for Google, obtained https://www.kaggle.com/datasets/abdalrahmanshahrour/googcsv
-Dataset Columns:
-symbol: The stock ticker symbol (e.g., GOOGL for Google).
-date: The trading date.
-close: The closing price of the stock on that date.
-high: The highest price the stock reached on that date.
-low: The lowest price the stock reached on that date.
-open: The price at which the stock opened on that date.
-volume: The number of shares traded on that date.
-adjClose: The adjusted closing price, accounting for any corporate actions.
-adjHigh: The adjusted high price.
-adjLow: The adjusted low price.
-adjOpen: The adjusted open price.
-adjVolume: The adjusted volume of shares traded.
-divCash: Cash dividends paid.
-splitFactor: Stock split factor.

Target(Dependent Variable): close
Features(Independent Variable): open, high, low, volume

## Results
The linear regression model provides a reasonable estimate of future stock prices based on historical data. The model's performance can be improved with more advanced techniques and additional features.


## Acknowledgements
- [Scikit-Learn](https://scikit-learn.org/) for the machine learning tools.
- [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) for data visualization.
