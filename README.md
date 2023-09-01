# US Home Prices - Supply and Demand Dynamics

## Overview

This analysis looks at the factors affecting home prices in the United States from 2003-2023, including supply, demand, economic, and market dynamics. Python and Pandas are used for data cleaning, analysis, and visualization.  Different machine learning models are evaluated to predict the S&P/Case-Shiller U.S. National Home Price Index.

## Data

The analysis uses two datasets:

- `supply.csv`: Contains housing supply metrics like new housing inventory, building permits, construction spending, and vacant units.

- `demand.csv`: Contains housing demand factors like mortgage rates, consumer sentiment, GDP, median sales prices.

## Analysis

The steps invovled in the analysis are:

- Data cleaning: Handle missing values, parse dates, fix data types
- Exploratory analysis: Correlation matrix, line/bar charts 
- Feature engineering: Add quarterly time period 
- Model building: Linear regression, decision tree, random forest, SVM, neural network
- Model evaluation: Compare MSE and R^2, analyze coefficients
- Interpretation: Connect observations to economic theory 

## Key Findings

- New housing inventory has slight negative impact on prices
- More construction spending leads to higher prices 
- GDP and median sales price have strong positive correlation with prices
- Mortgage rates and consumer sentiment negatively affect prices
