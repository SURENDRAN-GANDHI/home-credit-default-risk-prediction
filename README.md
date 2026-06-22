# 🏠 Home Credit Default Risk Prediction

> 🚧 Project Under Construction 🚧
> This project is currently in development. New features, analysis, and models are being added progressively.

## 📌 Project Overview

Financial institutions face significant risks when approving loans. The objective of this project is to build a machine learning solution that predicts whether a customer is likely to default on a home loan based on their financial history and credit-related information.

The project follows an end-to-end Data Science workflow including:

* Data Understanding
* Exploratory Data Analysis (EDA)
* Data Preprocessing
* Feature Engineering
* Model Training
* Model Evaluation
* Business Insights & Recommendations

---

## 🎯 Project Goal

The primary goal is to:

* Predict the probability of customer loan default.
* Identify important factors influencing default risk.
* Support data-driven loan approval decisions.
* Compare multiple machine learning models and select the best-performing model for production.

---

## 📂 Project Structure

```text
home-credit-default-risk-prediction/
│
├── data/
│   ├── raw/
│   │   ├── application_train.csv
│   │   ├── bureau.csv
│   │   ├── bureau_balance.csv
│   │   ├── previous_application.csv
│   │   ├── installments_payments.csv
│   │   ├── POS_CASH_balance.csv
│   │   └── credit_card_balance.csv
│   │
│   ├── processed/
│   └── final/
│
├── notebooks/
│   └── HomeLoanDefault.ipynb
│
├── src/
│   ├── data_ingestion.py
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   ├── evaluation.py
│   └── utils.py
│
├── models/
│   ├── logistic_regression.pkl
│   ├── random_forest.pkl
│   └── best_model.pkl
│
├── reports/
│   ├── EDA_Report.pdf
│   ├── Model_Comparison_Report.pdf
│   └── Challenges_Report.pdf
│
├── requirements.txt
└── README.md

```

---

## 📊 Dataset

The project uses the Home Credit Default Risk dataset consisting of:

* application_train.csv
* bureau.csv
* bureau_balance.csv
* previous_application.csv
* installments_payments.csv
* POS_CASH_balance.csv
* credit_card_balance.csv

⚠️ Datasets are not included in this repository due to file size limitations.

Download the dataset and place the files inside:

```text
data/raw/
```

---

## 🛠️ Current Progress

* [x] Project Structure Setup
* [x] Git Repository Setup
* [x] Dataset Collection
* [ ] Data Understanding
* [ ] Data Cleaning
* [ ] Exploratory Data Analysis
* [ ] Feature Engineering
* [ ] Dataset Aggregation
* [ ] Model Development
* [ ] Hyperparameter Tuning
* [ ] Model Comparison
* [ ] Business Recommendations
* [ ] Documentation

---

## 🤖 Planned Models

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost
* LightGBM

---

## 📈 Evaluation Metrics

* ROC-AUC
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🚀 Status

Current Status: Building the foundation before teaching the models how to approve loans responsibly 😄

Stay tuned for updates!
