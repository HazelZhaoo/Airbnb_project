# Airbnb_project

## 🏡 Airbnb Price Prediction Project

This project analyzes Vancouver Airbnb listings to predict prices using various machine learning models. The goal is to identify key factors influencing Airbnb prices and build a model that accurately estimates listing prices based on those factors.

## 📊 Project Overview

This project involved:

- Data Cleaning -> Handled missing values, transformed columns, and removed irrelevant or highly correlated features.
- Exploratory Data Analysis (EDA)-> Visualized trends to understand the impact of various factors like amenities, location, and host attributes on pricing.
- Feature Engineering -> Created new features and transformed existing ones to improve model performance.
- Modeling -> Built and evaluated multiple regression models, including:
    * Linear Regression
    * Lasso Regression
    * Decision Tree Regressor
    * K-Nearest Neighbors (KNN)
    * XGBoost Regressor
- Hyperparameter Tuning -> Used GridSearchCV to optimize model parameters.
- Model Evaluation -> Assessed models based on Mean Squared Error (MSE) and R-Squared scores.
 
## 🚀 Key Findings

Top Predictors:
Availability and review scores significantly impact prices.
Amenities like self-check-in, kitchen, and Wi-Fi are also important.

Best Performing Model:
The XGBoost Regressor demonstrated the highest R-squared score, indicating it was the most effective at explaining the variance in listing prices.

## 📈 Future Improvements

Incorporate sentiment analysis of listing descriptions and photos.
Explore deep learning models for improved accuracy.
Collect additional data, such as neighborhood crime rates or nearby attractions.


 
