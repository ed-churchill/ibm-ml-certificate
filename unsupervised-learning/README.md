# Unsupervised Learning

# Portfolio Construction with Hierarchical Risk Parity: a Comparison to the Minimum-Variance and Risk-Parity Methods

## Overview
This folder contains code, a writeup and a presentation for an unsupervised learning project that was submitted as part of the IBM Machine Learning Professional Certificate.

## Objective
The objective of the analysis is based on a 2016 paper by Marcos López de Prado called *Building Diversified Portfolios
that Outperform Out-of-Sample*. He uses a technique called Hierarchical Risk-Parity (HRP) to construct portfolios that
allocate risk more effectively than traditional techniques such as Risk-Parity and Minimum-Variance. HRP uses the
unsupervised learning algorithm *hierarchical agglomerative clustering* to group ‘similar’ securities together before
assigning each of them a weight so that there is risk-parity within each cluster. The analysis includes a practical implementation of three slightly different versions of HRP. We choose the one
that performs best and compare it to the Risk-Parity and Minimum-Variance methods, as well as a naïve equally-weighted portfolio. 

## Contents
- `ibm-unsupervised-learning-writeup.pdf`: Formal writeup with theory and results
- `ibm-unsupervised-learning-presentation.pptx`: Powerpoint presentation for colleagues at M&G Investments
- `ibm-unsupervised-learning-get-data.ipynb`: Code to fetch data
- `ibm-unsupervised-learning-eda-and-data-cleaning.ipynb`: Code to explore and clean data
- `ibm-unsupervised-learning-hrp.ipynb`: Code to implement HRP
- `ibm-unsupervised-learning-risk-parity.ipynb`: Code to implement Risk-Parity
- `ibm-unsupervised-learning-minimum-variance.ipynb`: Code to implement Minimum-Variance
- `ibm-unsupervised-learning-equal-weight.ipynb`: Code to implement an equally weighted portfolio
- `ibm-unsupervised-learning-results-analysis.ipynb`: Code to compare strategy results
