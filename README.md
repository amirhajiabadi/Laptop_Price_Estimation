# Laptop_Price_Estimation

## Introduction

Laptop Price Estimation is aimed at analyzing and predicting laptop prices using various machine learning models. It encompasses data analysis, preprocessing, and model building, with a focus on key aspects.

## Data Analysis

- **Importing Libraries:** We begin by importing essential Python libraries (e.g., pandas, numpy, seaborn, matplotlib) for data handling and visualization.

- **Data Preprocessing:** This stage includes:
    - Loading the dataset from a CSV file.
    - Selecting pertinent columns: 'Company', 'TypeName', 'Ram', 'OpSys', 'Weight', and 'Price'.
    - Handling missing values.
    - Converting data types.
    - Conducting exploratory data analysis.

## Feature Engineering

- **Screen Resolution:** Extracting 'TouchScreen' and 'IPS' features and calculating 'PPI.'

- **CPU:** Categorizing CPU brands.

- **Memory:** Extracting memory types and calculating storage capacity.

- **GPU:** Extracting GPU brands.

- **Operating System:** Categorizing OS.

- **Weight:** Analyzing weight distribution and identifying outliers.

## Model Building

Multiple models, including Linear Regression, Ridge Regression, Lasso Regression, Decision Tree, and Random Forest, are trained and evaluated for price prediction.

## Hyperparameter Tuning

Hyperparameter tuning is performed for the Random Forest model using Randomized Search CV to optimize parameters such as the number of estimators, maximum depth, and more.

## Model Evaluation

Model performance is assessed using R-squared (R2) and Mean Absolute Error (MAE) metrics, aiding in the selection of the best model.

## Predictions

The chosen model is used for price predictions across the dataset, with a transformation from log values to the original price scale.

## Conclusion

This project offers insights into laptop price prediction, covering data processing, feature engineering, model development, hyperparameter tuning, and model assessment. The final model provides accurate laptop price estimates.

![image](https://user-images.githubusercontent.com/82854373/207858578-095cce75-8f45-4a4a-a320-55d0c5d9dc71.png)

**The prices are not denominated in euros and undergo conversion in the final stage within the application situated in the app folder.**



