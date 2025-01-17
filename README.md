# Indian House Price Prediction System

## Overview
This project aims to predict house prices based on various factors such as area, number of rooms, and other features that influence the pricing of properties. The system uses machine learning algorithms such as **Random Forest**, **XGBoost**, and **AdaBoost** to make accurate price predictions. The dataset contains **30,000 entries** and **11 features**, and the models were fine-tuned using ** hyperparameter optimization** to achieve the highest possible prediction accuracy.

## Key Features

- **Predictive Modeling**: Implements Random Forest, XGBoost, and AdaBoost regressors for predicting house prices.
- **Manual Hyperparameter Tuning**: Achieved **8% improvement** in prediction accuracy through careful manual tuning of model parameters.
- **Data Preprocessing**: Utilized techniques like **Feature Scaling**, **One-Hot Encoding**, **Label Encoding**, and **Variance Inflation Factor** for better model performance.
- **Exploratory Data Analysis (EDA)**: Performed comprehensive EDA using heatmaps, correlation matrices, distribution plots, and more.
- **Cross-Validation**: Applied **5-fold cross-validation** for reliable and consistent model evaluation.
- **High Accuracy**: Achieved an **R² score of 94%** on test data, ensuring robust prediction capability.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: 
  - **NumPy**, **Pandas**, **Matplotlib**, **Seaborn** (for data handling and visualization)
  - **Scikit-Learn** (for model building and evaluation)
  - **XGBoost** (for XGBoost model)
  - **Statsmodels** (for VIF and statistical analysis)
