# Rossmann Store Sales Prediction
Rossmann store sales prediction using XGBoost

## Problem Statement

This is a real-world dataset taken from the [Rossmann Store Sales](https://www.kaggle.com/c/rossmann-store-sales) competition on Kaggle:

> Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. 
>
>
> With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

## Dataset 
The dataset taken from the Kaggle. You can download from [here](https://www.kaggle.com/c/rossmann-store-sales/data)

## Approach
- Downloading a real-world dataset from Kaggle
- Data pre-processing and Feature engineering
- Scaling numeric features to a (0,1) range
- Encoding categorical columns as one-hot vectors
- Training a XGBoost regressor model 
- Validating using K-Fold Cross validation
- Evaluating a model using a test set

