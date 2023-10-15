# Advanced-Regression-Assingment

> This is Advance Regression assignment based on Housing price problem. Multiple models are used to identify the best model.

## Table of Contents

- [Problem Statement](#problem-statement)
- [Business Goal](#business-goal)
- [Dataset](#dataset-and-data-dictionary)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [Contact](#Contact)

## Problem Statement

A US-based housing company called Surprise Housing has made the decision to expand its operations into the Australian market. This company utilizes data analytics to acquire properties at prices lower than their actual market values, and subsequently, resell them at higher prices. In pursuit of this objective, the company has amassed a dataset from property sales in Australia, which is available in the provided CSV file.

The company is currently exploring potential properties for acquisition as part of its market entry strategy. Your task is to construct a regression model with regularization techniques to forecast the true value of these prospective properties and make informed investment decisions.

The company is interested in understanding two key aspects:

Identifying which variables play a significant role in predicting property prices.
Evaluating how effectively these variables explain variations in property prices.

## Business Goal

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Dataset and Data Dictionary

The following files are present inside datasets folder:

- train.csv (dataset)
  - Data Definition.txt

## Conclusions

Normal Regression is worst model due to negative R2 score

Ridge and Lasso both have good performance over RFE.

The optimal lambda value of Ridge and Lasso are below: Ridge - 1 Lasso - 0.0002

The MSE of Ridge and Lasso are:

Ridge - 0.125217 Lasso - 0.126049

Also, since Lasso helps in feature reduction, Lasso has a better edge over Ridge.

Best Variables to describe according to best algorithm Lasso hence are: OverallQual 0.520026 GrLivArea 0.448735 1stFlrSF 0.442132 MSZoning_RH 0.375424 MSZoning_FV 0.321321 MSZoning_RL 0.318949 OverallCond 0.317879 MSZoning_RM 0.256601 GarageCars 0.195930 Neighborhood_StoneBr 0.178402

## Technologies Used

a. Python
b. matplotlib
c. seaborn
d. panda
e. numpy
f. sklearn
g. statsmodels

## Acknowledgements

## Contact

Created by Das Balvinder Das[https://github.com/DasBalvinderDas] - feel free to contact me!
