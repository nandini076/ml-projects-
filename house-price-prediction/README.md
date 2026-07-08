# House Price Prediction

## Objective
Predict house sale prices using regression techniques on a dataset with 79 features.

## Approach
- Handled missing values and performed log transformation on the target variable
- Conducted EDA to identify key predictors (OverallQual, GrLivArea)
- Feature engineering and one-hot encoding for categorical variables
- Compared 9 regression models (Linear Regression, Ridge, Lasso, Decision Tree, 
  Random Forest, Gradient Boosting, XGBoost, SVR, KNN)
- Hyperparameter tuning on top models

## Result
Best Model: **Gradient Boosting** — R² Score: **0.88**
Grade received: A

## Tools
Python, Pandas, scikit-learn, XGBoost, Matplotlib, Seaborn
