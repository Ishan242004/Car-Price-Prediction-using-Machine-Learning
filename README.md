# Car-Price-Prediction-using-Machine-Learning
# Project Overview
This project aims to predict the selling price of used cars using Machine Learning techniques. The dataset used is "CAR DETAILS FROM CAR DEKHO.csv", which contains information about used cars such as year, fuel type, kilometers driven, owner type, and more.<br>
The objective is to build and compare multiple regression models to accurately estimate car selling prices.

# Dataset Information
Dataset: Car Dekho Used Car Dataset<br>
Target Variable: selling_price

# Features:
Name<br>
Year<br>
Km Driven<br>
Fuel Type<br>
Seller Type<br>
Transmission<br>
Owner

# Workflow
# 1️. Data Exploration
Used info() and describe() to understand dataset<br>
Checked for missing values<br>
Visualized categorical features using Seaborn<br>
Detected outliers using boxplot

# 2️. Outlier Removal
Applied IQR (Interquartile Range) method<br>
Removed extreme values from km_driven<br>

# 3️. Data Preprocessing
Dropped unnecessary columns<br>
Applied One-Hot Encoding using pd.get_dummies()<br>
Split data using train_test_split()

# 4️. Model Building
Implemented and compared multiple regression models:<br>
Linear Regression<br>
Decision Tree Regressor<br>
Random Forest Regressor<br>
Voting Regressor (Ensemble Model)

# 5️. Model Evaluation
Evaluation Metrics Used:<br>
R² Score<br>
Mean Absolute Error (MAE)
