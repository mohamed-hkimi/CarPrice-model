# CarPrice-model
Car Sales Price Prediction Project

📋 Overview
This project analyzes a dataset of used car sales to build a predictive model for estimating vehicle prices based on key attributes like manufacturer, model, engine size, fuel type, age, and mileage. Using exploratory data analysis (EDA), feature engineering, and machine learning regression techniques, we uncover patterns in the used car market and deploy a robust model to forecast prices with high accuracy.
Perfect for data science enthusiasts, automotive analysts, or anyone interested in real-world regression tasks!

📊 Dataset

Source: Synthetic/real-world inspired car_sales.csv (generated for educational purposes).
Size: 50,000 records.
Features:

Manufacturer: Brand (e.g., Ford, Toyota, Porsche).
Model: Specific model (e.g., Fiesta, 718 Cayman).
Engine_size: Displacement in liters (float).
Fuel_type: Petrol, Diesel, Hybrid, etc.
Year_of_manufacture: Production year (int).
Mileage: Odometer reading in miles (int).
Price: Selling price in USD (target variable, int).

Key Stats: No missing values; skewed price distribution (median ~$10k-15k, outliers up to $100k+); diverse manufacturers (20+ uniques) with high-cardinality models.

🎯 Objectives

Perform EDA to visualize distributions, correlations, and outliers.
Engineer features (e.g., car age, log-transforms, mileage bins) for better model performance.
Preprocess data (encoding categoricals, scaling numerics) and split for train/test.
Train and evaluate regression models (Linear Regression, Random Forest, XGBoost) using RMSE/MAE metrics.
Achieve ~70-85% variance explained (R²) on test set.

🛠 Tech Stack

Language: Python 3.8+
Libraries:

Data Manipulation: pandas, numpy
Visualization: matplotlib, seaborn
Modeling: scikit-learn (pipelines, metrics), xgboost (advanced trees)


Environment: Jupyter Notebook or Google Colab recommended.
