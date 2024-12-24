# Car-Resale-Price-Prediction

This repository contains the implementation of a machine learning project to predict car resale prices using a dataset obtained from Kaggle. The project involves data preprocessing, exploratory data analysis, and model development.

## Dataset
The dataset used in this project is publicly available on the Kaggle at Car Resale Prices Dataset.
It contains various car features, such as their make, model, year, mileage, and other factors influencing resale prices.

## Project Overview
This repository contains the following:

**Preprocessing_code.ipynb:** Preprocessing the dataset to clean, transform, and prepare it for modeling.
**Final_code.ipynb:** Applying machine learning models to predict the car resale price and evaluating their performance.

## Preprocessing the Dataset
The preprocessing steps included in this project are:

Handling Missing Values: Imputed missing data for numerical and categorical features.

Feature Engineering: Created additional features from existing data to improve model performance.

Data Transformation: Scaled numerical features using standard scaling techniques and One-hot encoded categorical variables to convert them into numerical form.

Splitting the Dataset: Divided the dataset into training and testing sets to evaluate the model's performance.

## Model Evaluation
The machine learning models used in this project include:

Linear Regression: A baseline model to predict resale prices.
Random Forest Regressor: A tree-based model known for handling nonlinear relationships effectively.
Gradient Boosting Regressor: A boosting algorithm that combines weak learners to create a strong learner.
XGBoost: An optimized gradient boosting framework for high-performance predictions.

## Evaluation Metrics
The performance of these models was evaluated using the following metrics:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R-squared (R²)
