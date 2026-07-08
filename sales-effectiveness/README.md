# Sales Effectiveness Prediction (Live Client Project)

## Objective
Predict high-quality sales leads to help the sales team prioritize efforts and 
improve conversion rates. Completed as a live client project during internship 
at Rubixe.

## Approach
- Cleaned and explored a dataset of 7,400+ sales lead records
- EDA on lead source, sales agent performance, location, and time-based trends
- Feature engineering: lead age, month/day-of-week/quarter features
- Outlier treatment (IQR method), correlation analysis, and encoding
- Compared 5 models (Logistic Regression, Random Forest, XGBoost, LightGBM, 
  Gradient Boosting)
- Hyperparameter tuning via GridSearchCV

## Result
Best Model: **Gradient Boosting (tuned)** — ROC-AUC: **0.80**
Grade received: A

## Business Impact
Delivered actionable recommendations to the sales team on lead prioritization 
and delivery-mode strategy based on model insights.

## Tools
Python, scikit-learn, XGBoost, LightGBM, Pandas, Matplotlib, Seaborn
