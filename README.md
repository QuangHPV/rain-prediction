# Rain Prediction in Australia 🌦️⛈️🌞☀️
## About
In this project, we'll explore a comprehensive analysis of a weather dataset.  
Our objective is to clean this data, perform exploratory data analysis (EDA), and apply several machine learning models to predict whether it will rain tomorrow in Australia.  
Please read through the notebook files in the following order
1. [Data Cleaning using KNN Imputation] (https://github.com/QuangHPV/sc1015-project/blob/851919895fe7fc347156137609cc55bdbfa0d614/Data_Cleaning_KNN.ipynb)
2. [Data Cleaning and Exploratory Analysis] (https://github.com/QuangHPV/sc1015-project/blob/851919895fe7fc347156137609cc55bdbfa0d614/Data_Cleaning_and_EDA.ipynb)
3. [Logistic Regression] (https://github.com/QuangHPV/sc1015-project/blob/851919895fe7fc347156137609cc55bdbfa0d614/Logistic_Regression_Weather_AUS.ipynb)
4. [XGBoost] (https://github.com/QuangHPV/sc1015-project/blob/851919895fe7fc347156137609cc55bdbfa0d614/XGBoost_Weather_AUS.ipynb)
5. [Multilayer Perceptron] (https://github.com/QuangHPV/sc1015-project/blob/851919895fe7fc347156137609cc55bdbfa0d614/Multilayer_Perceptron.ipynb)

Note that there're 2 cleaned version of the dataset, which would be examined separately for comparison purpose.
## Contributor
* @QuangHPV - Data Cleaning, Exploratory Data Analysis
* @Devininthelab - Logistic Regression, XGBoost, Multilayer Perception
Luu Minh Thang. Matric Number: U2323630J
## Problem
Data set: Rain in Australia
https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package
Problem Definition: To predict whether it will rain tomorrow based on other variables
## Model Used
Logistic Regression 📈
* Fitting 1 curved line into our dataset

Multilayer Perceptron 🤖
* Using shallow neural network to fit our dataset

XGBoost 🌳
* Building many scaled tree factors that ultimately, leading to our prediction
## Conclusion
Through this effort to predict rain by data analysis and statistical modelling, we've found that:
* XGBoost and MLP perform the best on our dataset, while Logistic Regresion perform not really good compared to the previous two models.
* Logistic Regression did not perform well with non-linearly correlated variables
* When we train our MLP model on our dataset for 100 epochs, our model start to be overfit.
* Using KNN Imputation for filling data can help we got a huge dataset without removing too much data.
## What we have learned
* Various machine learning model from regression to tree-based to neural network
* How to clean complex data: missing values and imputation, outlier removal, etc.
## Reference
