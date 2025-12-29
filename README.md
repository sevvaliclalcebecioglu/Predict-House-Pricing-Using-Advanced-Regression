# Predict House Pricing Using Advanced Regression

## Project Overview
This project focuses on predicting **house prices** using advanced regression techniques. Regression is a statistical method used to:
- Predict future outcomes based on historical data.
- Analyze the relationship between two or more variables.

The goal of this project is to process the given housing dataset, apply **feature engineering**, and develop predictive models to accurately estimate house prices.

## Dataset Processing
- **Data Cleaning:** Missing values were handled and outliers were checked.  
- **Feature Engineering:** New meaningful features were created to improve model performance.  
- **Categorical Encoding:** Non-numeric categorical features were transformed into numeric representations for model compatibility.

## Model Performance Comparison

| Model               | R² Score | RMSE          | MAE          |
|--------------------|----------|---------------|--------------|
| XGBRegressor        | 0.908    | 26,566.36     | 17,360.13    |
| Gradient Boosting   | 0.896    | 28,277.48     | 16,534.81    |
| Ridge               | 0.871    | 31,400.46     | 20,389.55    |
| SGD                 | 0.864    | 32,297.11     | 20,454.62    |
| Lasso               | 0.837    | 35,411.02     | 19,455.31    |
| KNeighborsRegressor | 0.824    | 36,765.88     | 24,391.65    |
| Extra Tree          | 0.794    | 39,708.22     | 26,860.33    |
| Decision Tree       | 0.770    | 41,990.35     | 26,062.94    |
| AdaBoost            | 0.740    | 44,684.07     | 25,996.59    |
| ElasticNet          | 0.626    | 53,549.93     | 31,805.06    |
| Linear              | 0.102    | 82,998.76     | 23,939.01    |
| SVR                 | -0.024   | 88,630.87     | 59,524.63    |
| MLP Regressor       | -3.665   | 189,169.07    | 167,841.48   |

## Key Insights
- The **XGBRegressor** and **Gradient Boosting** models achieved the highest accuracy and the lowest error rates, making them the most effective for predicting house prices.  
- Feature engineering and proper preprocessing significantly improved model performance.  
- Other models, including Ridge, SGD, and Lasso, also performed reasonably well but were less accurate than ensemble methods.

## Conclusion
By combining **advanced regression models** with careful **data preprocessing and feature engineering**, this project successfully predicts housing prices with high accuracy, providing actionable insights for real estate pricing and investment strategies.
