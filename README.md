# Housing Price Prediction

This repository contains a machine learning project aimed at predicting housing prices using linear regression. The dataset includes various features about houses, such as location, the number of rooms, and proximity to the ocean.

## Dataset

- **Source**: `housing.csv`
- The dataset includes both numerical and categorical data, such as `median_house_value`, `households`, `total_bedrooms`, and `ocean_proximity`.

## Project Structure

1. **Data Preprocessing**:
    - Handled missing values by removing rows/columns or imputing them with mean or mode.
    - Separated numerical and categorical columns.
    - Applied label encoding and one-hot encoding for categorical features.

2. **Normalization**:
    - Used `MinMaxScaler` to normalize the features.

3. **Linear Regression Model**:
    - Split the data into training and testing sets using `train_test_split`.
    - Built a linear regression model using `LinearRegression`.
    - Evaluated the model using `mean_squared_error` and `r2_score`.

## Results

- **Test Set**:
    - Mean Squared Error (MSE): **0.0276**
    - R-squared (R2): **0.5997**
  
- **Training Set**:
    - Mean Squared Error (MSE): **0.0281**
    - R-squared (R2): **0.5981**

## Dependencies

- pandas
- numpy
- scikit-learn
- matplotlib
- scipy
