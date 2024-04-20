# SC1015-Project 🤖🤖🤖
## About
In this project, we'll explore a comprehensive analysis of a weather dataset.  
Our objective is to clean this data, perform exploratory data analysis (EDA), and apply several machine learning models to predict whether it will rain tomorrow in Australia.  
Please read through the notebook files in the following order
* Data_Cleaning_KNN.ipynb
* Data_Cleaning_and_EDA.ipynb
* data_cleaning_eda_new.ipynb
* Logistic_Regression_Weather_AUS.ipynb
* XGBoost_Weather_AUS.ipynb
* Multilayer_Perceptron.ipynb
Note that there're 2 cleaned version of the dataset, which would be examined separately for comparison purpose.
## Contributor
Hoang Pham Viet Quang. Matric Number: U2323602H  
Luu Minh Thang. Matric Number: U2323630J
## Problem
Data set: Rain in Australia
https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package
## Model Used
Logistic Regression
> Fitting 1 curved line into our dataset
Multilayer Perceptron
> Using shallow neural network to fit our dataset
XGBoost
> Building many scaled tree factors that ultimately, leading to our prediction
## Conclusion
Through this effort to predict rain by data analysis and statistical modelling, we've found that:
*
* 
* XGBoost and MLP perform the best on our dataset, while Logistic Regresion perform not really good compared to the previous two models.
* Logistic Regression did not perform well with non-linearly correlated variables
* When we train our MLP model on our dataset for 100 epochs, our model start to be overfit.
* Using KNN Imputation for filling data can help we got a huge dataset without removing too much data. 
  
## Reference
