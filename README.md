# 🏥 Medical Insurance Cost Prediction

Predicting individual medical insurance costs using Machine Learning techniques.
This project analyzes demographic and health-related factors to estimate medical charges accurately.

## Project Overview

Medical insurance companies determine premium charges based on multiple factors such as age, BMI, smoking habits, and region.

This project aims to:

Perform Exploratory Data Analysis (EDA)

Identify key factors affecting insurance costs

Build and compare Machine Learning models

Deploy a predictive system for real-time cost estimation

## Dataset Information

Dataset Name: Insurance Dataset

File: insurance.csv

Records: 1338

## Features:

Feature	Description
age	Age of primary beneficiary
sex	Gender (male/female)
bmi	Body Mass Index
children	Number of dependents
smoker	Smoking status
region	Residential area
charges	Medical insurance cost (Target Variable)


## Exploratory Data Analysis (EDA)

## Key insights discovered:

🔥 Smokers have significantly higher insurance charges.

📈 Age and BMI positively correlate with insurance cost.

👨‍👩‍👧 Number of children has minimal impact.

📊 Region has moderate effect on charges.

## Data visualization techniques used:

Distribution plots

Correlation heatmap

Box plots

Pair plots

##  Machine Learning Models Used

Linear Regression

Lasso Regression

Ridge Regression

Random Forest Regressor

## Best Performing Model:

Random Forest Regressor (Highest R² Score)

## Tech Stack

Python 🐍

NumPy

Pandas

Matplotlib & Seaborn

Scikit-learn

Jupyter Notebook

## Project Workflow
1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Encoding
5. Model Training
6. Model Evaluation
7. Prediction System
8. Model Evaluation Metrics

### R² Score

### Mean Absolute Error (MAE)

### Mean Squared Error (MSE)


## Future Improvements

Hyperparameter tuning (GridSearchCV)

XGBoost implementation

Model deployment using Streamlit

Docker containerization

CI/CD integration
