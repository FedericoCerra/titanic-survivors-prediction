# Titanic: Machine Learning from Disaster

This repository contains my solution for the Titanic Kaggle competition. 

## Key Features
* **Feature Engineering:** Extracted passenger titles (Mr, Miss, etc.) and binned ages to capture non-linear survival patterns.
* **Optimization:** Used **Optuna** to find the best hyperparameters for LinearRegression,  Random Forest and XGBoost.
* **Encoding:** Implemented `OneHotEncoder` for categorical variables (Title, Embarked).
* **Visualization:** Includes decision tree paths and survival density plots using Seaborn.

## Tech Stack
* **Python**
* **Scikit-Learn**
* **Optuna** (Hyperparameter Tuning)
* **Seaborn/Matplotlib** (Visualization)

## Results
* **Best Model:** Random Forest
* **Validation Accuracy:** ~82%
* **Kaggle competition score:** 0.77033

