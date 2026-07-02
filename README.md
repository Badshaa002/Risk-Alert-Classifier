# 🚨 Risk Alert Classifier

### AI-Powered Customer Risk Prediction using Machine Learning

```{=html}
<p align="center">
```
![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)

```{=html}
</p>
```

------------------------------------------------------------------------

## 📌 Project Overview

The **Risk Alert Classifier** predicts whether a customer is **Low
Risk** or **High Risk** using Machine Learning. The project includes
preprocessing, KNN imputation, class imbalance handling, model training,
hyperparameter tuning, and evaluation.

## 🎯 Problem Statement

Develop a binary classification model to identify high-risk customers
while minimizing false negatives.

## 📂 Dataset

-   👥 4600 Customers
-   📊 16 Features
-   ⚠️ 12% High-Risk Customers

### Features

-   Age
-   Gender
-   Region
-   Employment Type
-   Annual Income
-   Credit Score
-   Credit Utilization Ratio
-   Missed Payments
-   Average Late Payment Days
-   Monthly Transactions
-   Monthly Spending
-   Cash Advance Count
-   Complaints
-   Failed Login Attempts

------------------------------------------------------------------------

## 🛠️ Technologies

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Scikit-Learn
-   imbalanced-learn
-   Jupyter Notebook

------------------------------------------------------------------------

## 🤖 Machine Learning Models

-   Logistic Regression
-   Decision Tree
-   Random Forest

### Class Balancing

-   No Sampling
-   Random Under Sampling
-   Random Over Sampling
-   SMOTE ✅
-   ADASYN

------------------------------------------------------------------------

## 🔍 Hyperparameter Tuning

-   RandomizedSearchCV
-   GridSearchCV

------------------------------------------------------------------------

## 📈 Evaluation Metrics

-   Accuracy
-   Precision
-   Recall
-   F1 Score
-   ROC-AUC Score
-   Confusion Matrix

------------------------------------------------------------------------

## 🏆 Final Results

  Model                     Accuracy   Recall   F1 Score      AUC
  ----------------------- ---------- -------- ---------- --------
  Logistic Regression          1.000    0.982      0.990    1.000
  Decision Tree (Tuned)        0.976    0.937      0.904    0.966
  Random Forest (Tuned)        0.996    0.982      0.982   0.9999

## 🥇 Best Model

**Logistic Regression + SMOTE**

✔ Highest Recall\
✔ Highest F1 Score\
✔ Lowest False Negatives

------------------------------------------------------------------------

# 📸 Screenshots

## 📊 Dataset Preview

![](screenshots/data_preview.png)

## 🤖 Logistic Regression

![](screenshots/logistic_results.png)

## ⚖️ Imbalance Handling Comparison

![](screenshots/imbalance_comparison.png)

## 🌳 Decision Tree vs Random Forest

![](screenshots/tree_randomforest.png)

## ⚙️ Hyperparameter Tuning

![](screenshots/hyperparameter_tuning.png)

## 📈 ROC-AUC Comparison

![](screenshots/auc_comparison.png)

## 📋 Project Summary

![](screenshots/project_summary.png)

------------------------------------------------------------------------

## 📂 Project Structure

``` text
Risk-Alert-Classifier/
│── RISK ALERT CLASSIFIER.ipynb
│── risk_alert_dataset.csv
│── README.md
│── screenshots/
│   ├── data_preview.png
│   ├── logistic_results.png
│   ├── imbalance_comparison.png
│   ├── tree_randomforest.png
│   ├── hyperparameter_tuning.png
│   ├── auc_comparison.png
│   └── project_summary.png
```

------------------------------------------------------------------------

## ▶️ Installation

``` bash
git clone https://github.com/yourusername/Risk-Alert-Classifier.git
cd Risk-Alert-Classifier
pip install pandas numpy matplotlib scikit-learn imbalanced-learn
jupyter notebook
```

Open **RISK ALERT CLASSIFIER.ipynb** and run all cells.

------------------------------------------------------------------------

## 💡 Future Improvements

-   XGBoost
-   LightGBM
-   CatBoost
-   SHAP Explainability
-   Streamlit Web App
-   REST API Deployment

------------------------------------------------------------------------

## 👨‍💻 Author

**Badshaa**

⭐ If you like this project, don't forget to **Star** the repository!
