# Diamonds Price Analysis and Prediction

## Project Overview

This project involves the analysis and prediction of diamond prices based on various attributes such as carat, cut, color, clarity, and more. The goal is to build a machine learning model that can accurately predict the price of a diamond given its features.

## Notebook Contents

### Data Exploration and Visualization
- **Loading and Inspecting Data:** Initial loading of the dataset and inspection of its structure.
- **Univariate Analysis:** Exploring individual features using histograms and boxplots.
- **Multivariate Analysis:** Investigating relationships between features using scatter plots and correlation matrices.

### Data Preprocessing
- **Handling Missing Values:** Identifying and addressing any missing values in the dataset.
- **Encoding Categorical Features:** Converting categorical features into numerical values using one-hot encoding.
- **Feature Scaling:** Normalizing the features to ensure they are on the same scale.

### Model Training and Evaluation
- **Splitting Data:** Dividing the data into training and test sets.
- **Training the Model:** Using a RandomForestRegressor to train the model on the training data.
- **Evaluating the Model:** Assessing the model's performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) metrics.

## Key Findings
- **Model Accuracy:** The low MAE and RMSE values indicate that the model predictions are fairly accurate.
- **Explained Variance:** The high R² value demonstrates that the model explains most of the variance in diamond prices.
