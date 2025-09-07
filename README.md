                                                          Laptop Price Prediction 💻
Project Overview:
    
    Aim :  This project aims to predict the price of laptops based on their specifications using Machine Learning model.
The dataset contains various laptop attributes such as RAM, Processor, GPU, Storage, Display, Weight, Battery, Operating System, and more.
The end goal is to build a reliable regression model that can estimate the laptop price

Key Features

Data Cleaning & Preprocessing
 - Removed inconsistencies and renamed columns.
 - Handled missing values using statistical techniques.

Feature engineering
  - Extracted Some useful features from features

Exploratory Data Analysis (EDA)
  - Distribution of prices and specifications.
  - Correlation heatmaps and feature importance.
  - Outlier detection and treatment.

Modeling
  - Applied XGBoost and did  Hyperparameter tuning using RandomizedSearchCV.

Best performance: ~89% R² Score.

Evaluation Metrics
   - R² Score
   - RMSE (Root Mean Squared Error

Programming Language: Python 

Libraries & Tools: pandas, numpy, matplotlib, seaborn,scikit-learn
xgboost,Jupyter Notebook

Dataset

Source: Kaggle

original 

shape: 8198 rows * 76 columns

cleaned

Shape: 8177 rows * 30 columns

Target Variable: Price
