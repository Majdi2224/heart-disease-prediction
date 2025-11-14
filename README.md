# Heart Disease Prediction

💡 **Predicting Heart Disease using Machine Learning**

This project is an exploration and predictive modeling exercise on a heart disease dataset (303 patient records, 9 features). It demonstrates the full machine learning workflow: data exploration, feature engineering, model training, evaluation, and feature importance analysis.

---

## Features

- **Exploratory Data Analysis (EDA):**  
  Insights about how features like Chest Pain Severity, Max Heart Rate, ST Slope, and Age correlate with heart disease.

- **Feature Engineering:**  
  Added interaction features such as Chest Pain × Exercise-Induced Angina, Oldpeak × Max Heart Rate, and more.

- **Models Trained:**  
  - Logistic Regression  
  - Random Forest Classifier  
  - Gradient Boosting Classifier  

- **Model Evaluation Metrics:**  
  - Accuracy, Precision, Recall, F1-score  
  - ROC-AUC  
  - Confusion Matrices  
  - Feature Importance (Tree-based and Permutation Importance)

---

## Key Findings

- Logistic Regression and Random Forest performed best (ROC-AUC ~0.93).  
- Engineered features did not significantly improve performance — the original features captured most of the predictive signal.  
- Top predictive features: Chest Pain Severity, Max Heart Rate Achieved, ST Slope, and Calcium.

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/Majdi2224/heart-disease-prediction.git

