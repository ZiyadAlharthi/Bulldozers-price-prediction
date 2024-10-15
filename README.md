# Bulldozers price predictions

## Problem Statement
The primary objective of this project is to predict the sale price of bulldozers using various machine learning techniques. By analyzing multiple characteristics of the bulldozers, the project aims to estimate the potential price based on historical data.

## Dataset Description
The dataset used in this project is collected from the Kaggle Bluebook for Bulldozers competition. It includes three main files:

- Train.csv: The training dataset, which contains data up to the end of 2011.
- Valid.csv: The validation dataset, which contains data from January 1, 2012, to April 30, 2012.
- Test.csv: The test dataset, which contains data from May 1, 2012, to November 2012, and will not be released until the final week of the competition.

You can access the dataset [here](https://www.kaggle.com/c/bluebook-for-bulldozers/data).

## Features
The dataset includes several features, with some of the key ones being:

| Feature | Description |
| --- | --- |
| SalesID | Sale identification number |
| SalePrice | Actual sale price |
| MachineID | Machine identification number |
| ModelID | Model identification number |
| YearMade | Year of manufacture |
| MachineHoursCurrentMeter | Current operating hours of the machine |
| UsageBand | Usage category |
| State | Condition of the machine |
| ProductGroup | Product group |

## Tools
The project utilizes the following Python libraries:
- pandas
- NumPy
- Matplotlib
- Scikit-Learn

## Algorithms
The project employs the following supervised learning algorithms:
- Linear Regression
- Random Forest Regressor
- Other regression algorithms such as XGBoost

## Evaluation Metrics
The performance of the machine learning models will be evaluated using the following metrics:
- Root Mean Squared Log Error (RMSLE)
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
