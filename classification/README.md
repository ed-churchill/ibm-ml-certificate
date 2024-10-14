# Classification

# Predicting the Sign of the 1-week Forward Return of S&P 500 Constituents

## Overview
This folder contains code and a writeup for a supervised learning project that was submitted as part of the IBM Machine Learning Professional Certificate.

## Objective
The objective of this analysis is to predict the sign (positive or negative) of the 1-week forward return of constituents of
the S&P 500. The return of a constituent stock is simply its change in price over the period divided by its price at the
start of the period. The prediction should be ‘1’ for a positive return and ‘0’ for a negative return (we choose ‘0’ instead of
‘-1’ for easier compatibility with certain binary classification algorithms). In the unlikely scenario that a stock has a
return of exactly zero return over the period, we classify it as ‘1’ to keep the problem binary. To calculate returns
throughout, we use the adjusted closing price of each stock, which is the closing price adjusted for dividends and stock
splits.

## Contents
- `ibm-classification-writeup.pdf`: Formal writeup with theory and results
- `ibm-classification-eda.ipynb`: Code to explore and clean data
- `ibm-classification-feature-engineering.ipynb`: Code to generate predictive features
- `ibm-classification-feature-selection.ipynb`: Code to select best features
- `ibm-classification-logistic-regression.ipynb`: Code to implement Logistic Regression
- `ibm-classification-xgboost.ipynb`: Code to implement XGBoost
- `ibm-classification-lstm.ipynb`: Code to implement an LSTM
- `ibm-classification-results-analysis.ipynb`: Code to compare strategy results
