# Multiple Linear Regression
## 📌 Project Overview
This project aims to predict housing prices using Multiple Linear Regression (MLR). The analysis involves applying feature selection techniques (Forward Selection, VIF, and p-value based elimination) to build an optimal regression model and improve interpretability.

## 🎯 Objective
1) Predict house prices based on multiple independent features.
2) Apply feature selection methods to identify significant predictors.
3) Compare results from Forward Selection and Manual Elimination (VIF, p-values).

## 🛠️ Tech Stack
1. Programming Language: Python
2. Libraries: NumPy, Pandas, Statsmodels, Scikit-learn, Matplotlib, Seaborn

## Steps Performed
1. **Data Preprocessing**
Handled missing values and categorical variables.
Scaled features where required.

2. **Exploratory Data Analysis (EDA)**
Distribution of house prices.
Correlation heatmaps of independent variables.

3. **Model Building**
Implemented Multiple Linear Regression.
Applied Forward Selection (automated feature addition based on adjusted R² / AIC).
Applied Manual Elimination using:
  VIF (Variance Inflation Factor) to handle multicollinearity.
  p-values to eliminate statistically insignificant features.

4. **Model Evaluation**
R² and Adjusted R²
RMSE (Root Mean Squared Error)
Residual analysis to check assumptions
