PRCP-1006-HomeLoanDef/
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
