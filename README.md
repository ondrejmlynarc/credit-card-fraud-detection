# Credit Card Fraud Detection
==============================

This project evaluates the performance of five machine learning models (Logistic Regression, Decision Tree, Random Forest, XGBoost, and Support Vector Machine) in detecting fraudulent credit card transactions.

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- This file
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- Project documentation and notes (currently in Jupyter notebooks).
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`


--------

## Dataset
The project uses a dataset containing a sample of credit card transactions with features (V1-V28) that are made anonoymous on purpose and a binary target variable (Class) indicating whether a transaction is fraudulent (1) or not (0).


The dataset can be found [here](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023).


## Key Findings

- High Accuracy: All evaluated models achieve high accuracy in identifying fraudulent transactions.
- Top Performers: XGBoost and Support Vector Machine models demonstrated the highest accuracy (over 99%).
- Comprehensive Evaluation: Performance assessed using accuracy, precision, recall, F1-score, confusion matrices,  and classification reports.