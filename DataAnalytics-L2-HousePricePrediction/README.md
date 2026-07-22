# Task — Predicting House Prices with Linear Regression

## Track
Data Analytics

## Objective
Build and evaluate a linear regression model that predicts house prices based on features such
as area, location, number of rooms, and age — covering the full pipeline from data cleaning
through to model interpretation.

## Dataset
House Prices - Advanced Regression Techniques — sourced from Kaggle. Contains 1,460 residential
property records with 79 explanatory features (area, quality ratings, year built, neighborhood,
garage details, etc.) and the target variable SalePrice.

## Tech Stack
Python, pandas, scikit-learn, matplotlib, seaborn, Jupyter Notebook

## Key Steps Performed
- Exploratory Data Analysis: null check, descriptive statistics, target variable distribution
- Feature selection discussion identifying likely predictors (area, quality, location, age)
- Missing value handling (median/mode imputation) and One-Hot Encoding of categorical features
- Correlation heatmap of top features most correlated with house price
- 80/20 train/test split
- Linear Regression model training using scikit-learn
- Model evaluation using MSE, RMSE, and R² score
- Actual vs. predicted price scatter plot
- Residual plot analysis to check for systematic prediction errors
- Coefficient analysis identifying the strongest positive/negative price drivers
- Bonus: performance comparison against Ridge and Lasso regularised models

## Key Insights
- SalePrice is right-skewed, with most homes priced between ₹100,000–₹200,000 and a long tail
  of high-value properties
- GarageArea, TotalBsmtSF, 1stFlrSF, OverallQual, and FullBath showed the strongest correlation
  with price
- The Linear Regression model achieved an R² of 0.8545 and RMSE of ₹33,407.37
- Ridge regression outperformed both plain Linear Regression and Lasso, achieving the best
  results overall: R² of 0.878 and RMSE of ₹30,576.78
- Prediction accuracy declined for high-end/luxury homes, likely due to fewer such properties
  in the training data

## Files in this Folder
- `House_Price_Prediction_LinearRegression.ipynb` — full notebook with code, charts, and analysis
- `screenshots/` — output visualizations
- `README.md` — this file

## Author
[Ananya R Naik]
