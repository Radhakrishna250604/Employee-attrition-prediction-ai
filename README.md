# Employee-attrition-prediction-ai
Predicting employee attrition using AI with ensemble learning (RandomForest, XGBoost, Logistic Regression). Includes model evaluation, ROC curve, confusion matrix, and feature importance analysis.
# Employee Attrition Prediction Using AI

This AI project predicts whether an employee is at risk of leaving the organization based on HR and workplace-related features. Using a stacking ensemble model (Random Forest + XGBoost + Logistic Regression), it provides high-accuracy predictions along with insights for HR analytics.

---

## Dataset

- 📁 Source: [Kaggle - IBM HR Analytics Employee Attrition](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Format: CSV (`WA_Fn-UseC_-HR-Employee-Attrition.csv`)
- Total Records: 1,470
- Target Variable: `Attrition` (Yes = 1, No = 0)

---

## Features Used

- Age, Gender, Job Role, Department
- Monthly Income, Work-Life Balance, Job Satisfaction
- Distance from Home, Total Working Years, Years at Company

---

## Model Architecture

| Component          | Description                           |
|--------------------|----------------------------------------|
| Feature Scaling     | StandardScaler                         |
| Base Models         | RandomForest, XGBoost                  |
| Final Estimator     | LogisticRegression                     |
| Ensemble Strategy   | StackingClassifier (from scikit-learn) |

---

## 📈 Evaluation Results

| Metric      | Value   |
|-------------|---------|
| Accuracy    | ~90%    |
| ROC AUC     | ~0.86   |

### Visual Results:
- 📘 Confusion Matrix (`confusion_matrix.png`)
- 📗 ROC Curve (`roc_curve.png`)
- 📙 Feature Importance (`feature_importance.png`)

---

## Recommended Repo Structure


