# Predict Future Sales

## Group Member
We are group 3. Our members are Ziwei Li, Kexin Zhang, Kewei Chen and HsinYu Chen.

## Kaggle Competition
* [Predict Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales/overview) - Link to Kaggle Competition
* Description:
In this competition we worked with a challenging time-series dataset consisting of daily sales data, kindly provided by one of the largest Russian software firms - 1C Co, and we are asked to predict total sales for every product and store in the next month.

## Project Description
In this project, we have tried different models such as
* XGBoost
* LGM
* Linear Regression
* LASSO Regression
* Ridge Regression
* Elastic Net Regression
* Random Forest
* Time Series

We have employed 21 features in our model and selected them according to the feature performance.
We had also tried to convert the categorical data columns into binary ones by one-hot-encoding for better model performance.
According to the result we got from Time Series Analysis, we selected the best part of data, which is the most recent six months data to train our models.

## Contents of Repository
* Dataset provided by Kaggle
* Project Jupyter Notebook
* Shapley Values Plot Jupyter Notebook
* Submission File for Kaggle Scoring
* Time Series Model Jupyter Notebook
