# machine-learning-credit-risk

## Project Overview

This project develops an end-to-end machine learning pipeline to predict the probability of loan default. It demonstrates a typical credit risk modeling workflow used in banking and consumer lending by generating borrower data, training a classification model, evaluating performance, and interpreting predictions using SHAP.

> **Note:** This version uses a synthetic dataset for demonstration purposes. The workflow can be applied to real-world loan datasets such as LendingClub or Home Credit.

---

## Features

- Synthetic credit risk dataset generation
- Data preprocessing
- XGBoost classifier
- ROC-AUC model evaluation
- Feature Importance visualization
- SHAP explainability
- Model serialization using Joblib

---

## Tech Stack

- Python
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib
- Seaborn
- Joblib

---

## Project Workflow

1. Generate synthetic loan data
2. Prepare training and testing datasets
3. Train an XGBoost classifier
4. Evaluate model performance using ROC-AUC
5. Visualize feature importance
6. Explain predictions using SHAP
7. Save the trained model

---

## Results

The project includes:

- ROC Curve
- Feature Importance Plot
- SHAP Summary Plot

These visualizations help evaluate model performance and interpret the factors influencing loan default predictions.

---

## Future Improvements

- Train on real LendingClub or Home Credit datasets
- Hyperparameter tuning
- Cross-validation
- Calibration Curve
- Precision-Recall Curve
- Confusion Matrix
- Additional borrower features
- Model deployment using Flask or FastAPI

---

## Repository Structure

```
machine-learning-credit-risk-trial-project/
│
├── Credit_Risk_Model.ipynb
├── credit_risk_xgboost_final.pkl
├── README.md
├── requirements.txt
└── images/
```
## Results

### ROC Curve

![ROC](images/roc_curve.png)

### Feature Importance

![Importance](images/feature_importance.png)

### SHAP Summary

![SHAP](images/shap_summary.png)

---

## Author

**Reet Sharma**
