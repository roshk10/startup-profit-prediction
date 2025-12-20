# Startup Profit Prediction using Regression

## Project Overview
This project focuses on analyzing and predicting the profit of startup companies based on their expenditure patterns. The objective is to understand which factors influence startup profit the most and to build a regression model that can estimate profit for new startups.



---

## Problem Statement
Startup companies invest in multiple areas such as research & development, marketing, and administration.  
This project aims to:
- Analyze how these investments impact profit
- Build a regression model to predict profit for new startups
- Identify the most influential factors affecting profitability

---

## Dataset Description
The dataset contains 50 startup records with the following attributes:

- R&D Spend – Investment in research and development  
- Marketing Spend – Marketing expenditure  
- Administration – Administrative costs  
- State – Location of the startup (categorical)  
- Profit – Final profit (target variable)

---

## Why Regression?
Profit is a continuous numeric value, making this a regression problem.  
Regression models are used to learn the relationship between multiple input variables and a numeric output.

---

## Methodology

### 1. Data Preparation
- Separated input features and target variable
- Encoded the categorical State column using One-Hot Encoding
- Ensured all features were numeric for regression models

### 2. Train–Test Split
- 80% of data used for training
- 20% of data used for testing  
This prevents overfitting and helps evaluate performance on unseen data.

### 3. Models Implemented
- Linear Regression (baseline model)
- Ridge Regression (reduces impact of large coefficients)
- Lasso Regression (performs feature selection)

### 4. Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Key Insights
- R&D Spend has the strongest positive influence on startup profit
- Marketing Spend contributes positively but with smaller impact
- Administration costs slightly reduce profit
- Startup location (State) has limited direct impact

---

## Limitations
- Small dataset size (50 startups)
- Assumes linear relationships
- External market factors not included

---

## Future Scope
- Use larger and more diverse datasets
- Apply time-series forecasting for profit over time
- Explore advanced machine learning or deep learning models


---

## Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Google Colab  
- GitHub  

---

## Conclusion
This project demonstrates a complete and correct machine learning pipeline—from problem understanding to model evaluation and interpretation. 

---

## Author
Roshan Raguraman
