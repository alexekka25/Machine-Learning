# Stock Price Prediction

This project involves predicting stock prices using various machine learning models. The dataset used contains historical stock prices for Amazon (AMZN), including features such as open, high, low, close, adjusted close prices, and trading volume.

## Table of Contents
- [Installation](#installation)
- [Data Loading](#data-loading)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Model Comparison](#model-comparison)

 ## Installation

Clone the repository and install the required packages.

## Data Loading
Load the stock price data using pandas

## Data Preprocessing
Preprocess the data by creating new features and preparing it for model training.

## Model Training
Train various models to predict stock prices.

  1. Random Forest Regressor
  2. Gradient Boosting Regressor
  3. Support Vector Regressor (SVR)

 ## Model Comparison
Compare the performance of the different models.

Summary of Model Performance

Model         	                     MSE	      RMSE	       R²


Random Forest                    	0.317697	   0.563646	    0.999848

Gradient Boosting	                0.393770	   0.627511	    0.999812

Support Vector Regressor (SVR)	  2091.991835	  45.738297	   0.001719

 ## Conclusion

The Random Forest model performed the best, followed by the Gradient Boosting model. The SVR model did not perform well on this dataset.

For deployment and further use, consider saving the best model and deploying it using a web framework like Flask.

