# Credit Card Spend Prediction

This project was developed for a Kaggle-style machine learning task to predict customers' monthly credit card spending.

## Project Objective
The goal was to build a predictive model for monthly credit card spend using customer financial, credit, and transaction-related variables.

## Methods
- Data preprocessing and cleaning
- Feature engineering
- Baseline linear models
- Lasso with cross-validation
- Tree-based models such as Random Forest, Gradient Boosting, XGBoost, and LightGBM
- Stacking ensemble for improved performance

## Key Feature Engineering
One important engineered feature was:

- total transaction value = number of transactions × average transaction value

## Files
- `best_submission.ipynb`: main notebook for preprocessing, modeling, and prediction
- `best_submission.html`: exported notebook for easier viewing
- `project_report.docx`: written project summary

## Results
The project improved substantially through iterative experimentation. Simple linear models were useful as baselines, while ensemble methods and stronger feature engineering led to better performance.

## Reflection
This project helped me understand the importance of:
- building a strong baseline early
- keeping preprocessing consistent
- using advanced ensemble methods only after the workflow is stable

## Notes
The project is based on Kaggle competition data.Due to dataset usage constraints, the full training and scoring data are not included.
