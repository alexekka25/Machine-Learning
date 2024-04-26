
# Bank Customer Churn Prediction Model

This project aims to predict customer churn in the banking industry using machine learning techniques.


## Introduction

Customer churn is a significant challenge for banks, as it can lead to revenue loss and decreased customer satisfaction. This project aims to develop a machine learning model to predict customer churn and identify factors influencing it.
## Features

- Age
- Gender
- Balance
- Number of Products
- CustomerId          
- Surname             
- CreditScore         
- Geography                        
- Tenure                           
- Num Of Products     
- Has Credit Card     
- Is Active Member    
- Estimated Salary    
- Churn     

## Data
Number of samples: 10,000

Data source: YBI Foundation GitHub

Dataset URL: https://raw.githubusercontent.com/YBI-Foundation/Dataset/main/Bank%20Churn%20Modelling.csv

Number of features: 13
## Modeling
The churn prediction model is developed using the Support Vector Machines (SVM) algorithm with the SVC (Support Vector Classifier) implementation from the scikit-learn library.

## Evaluation
The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. 
## Usage/Examples

To use the churn prediction model:
1. Install the required dependencies.
2. Train the model using the provided dataset.
3. Make predictions on new data using the trained model.
4. Interpret the results and take appropriate actions to mitigate customer churn.


## Dependencies
- Python (>=3.6)
- scikit-learn
- pandas
- matplotlib
