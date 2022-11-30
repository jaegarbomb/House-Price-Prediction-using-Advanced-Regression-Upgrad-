# Advanced House Price Regression

## Table of Contents
* [General Info](#general-information)
* [Business Goal](#business-goal)
* [Files](#files)
* [Libraries](#libraries)
* [Observation](#observations)

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.  The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. 

The company wants to know:
- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house.

## Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Files: 
- **train.csv** : the main data source
- **House Price Prediction.ipynb** : The notebook containing the model for the predicting the price.

## Libraries:
- Pandas
- Numpy
- Matplotlib and Seaborn
- Scikit-learn

## Observations:

Using Lasso and Ridge Regulaziation techniques and sampling size of 75% (training data), the following are the most important features that are used to predict the price:

1. Total Square Footage
2. Total Rooms above Grade
3. Size of garage in car capacity
4. Size of garage in square feet
5. Number of fireplaces
6. Lot size in square feet
7. Neighborhood
8. Linear feet of street connected to property
9. Should have Central air conditioning
1-. Type of roof
