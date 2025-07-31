# Customer Churn Prediction Model

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Supervised-brightgreen)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0%2B-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-1.5%2B-green)

A machine learning project to predict customer churn for a telecom company, with model deployment via FastAPI.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [API Deployment](#api-deployment)
- [Contributing](#contributing)

## Project Overview
This project develops predictive models to identify customers at risk of churning (leaving the service). We compare Logistic Regression and XGBoost approaches, with the latter showing superior performance.

Key steps:
- Data cleaning and feature engineering
- Exploratory data analysis
- Model training and evaluation
- API deployment for predictions

## Dataset
The dataset contains 3,150 customer records with 14 original features, expanded to 22 through feature engineering.

Original features include:
- Call metrics (failure rate, usage seconds, frequency)
- Subscription details (length, charge amount)
- Customer demographics (age group, tariff plan)
- Behavioral data (distinct numbers called, SMS frequency)

## Features
### Engineered Features
1. `Usage_Per_Day`: Seconds of Use / Subscription Length
2. `Call_Failure_Rate`: Call Failure / Frequency of use  
3. `Complaints_Per_Use`: Complains / Frequency of use
4. One-hot encoded categorical features

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction
