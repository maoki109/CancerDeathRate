# Cancer Death Rate
DPhi Machine Learning Bootcamp Datathon 2 / Assignment 3

## Objective
Build a machine learning model that would predict the cancer death rate for the given year.

## Problem
"Many aspects of the behaviour of cancer disease are highly unpredictable. Even with the huge number of studies that have been done on the DNA mutation responsible for the disease, we are still unable to use these information at clinical level. However, it is important that we understand the effects and impacts of this disease from the past information as much as we possibly can."

## Model Building
We perform exploratory data analysis (EDA) on the given data to remove data we don't want to use, replace missing values, and get more details about our variables. We test a Linear Regression Model, Random Forest Regressor, and Decision Tree Regressor. We then perform hyperparameter tuning and use the Boruta feature selection technique with a Random Forest Regressor model for our final predictions. 
