# Simple Linear Regression: Height and Weight Prediction

This repository contains a simple machine learning project implementing **Linear Regression** using Python and `scikit-learn` to predict a person's height based on their weight.

## 📌 Project Overview
- **Dataset:** `height-weight.csv` (contains Weight and Height measurements)
- **Library Used:** 
  - `pandas` & `numpy` for data manipulation and preprocessing
  - `scikit-learn` (`StandardScaler`, `train_test_split`, `LinearRegression`) for building and evaluating the machine learning model
  - `matplotlib` for data visualization and plotting regression lines
  
## 🚀 Steps & Workflow
1. **Data Loading & Exploration:** Read the dataset and visualize the initial relationship between weight and height using scatter plots.
2. **Data Splitting:** Split the data into training and testing sets (`80%` training, `20%` testing).
3. **Feature Scaling:** Standardize the features using `StandardScaler` to ensure optimal performance for the model.
4. **Model Training:** Train a `LinearRegression` model using the training set.
5. **Prediction & Evaluation:** 
   - Predict the target values and plot the regression line against actual data points.
   - Evaluate model performance using metrics such as **Mean Squared Error (MSE)**, **Root Mean Squared Error (RMSE)**, **Mean Absolute Error (MAE)**, and **R-squared ($R^2$) Score**.
6. **New Predictions:** Test the trained model with custom inputs (e.g., predicting height for a specific weight).

## 📊 Results & Visualization
- The regression model captures the linear trend between height and weight.
- Model performance is verified and validated visually using Matplotlib scatter and line plots.

## 🛠️ Requirements
Make sure you have the following libraries installed:
```bash
pip install pandas numpy matplotlib scikit-learn
