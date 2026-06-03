# Give-A-Credit-or-Not
# Credit Risk Default Prediction Using Machine Learning

## Project Overview

This project develops a machine learning model to predict whether a borrower is likely to default on a loan. Credit risk assessment is a critical task in the financial industry, helping banks and lending institutions make informed lending decisions while minimizing financial losses.

Using historical customer financial data, the model identifies patterns associated with loan default and predicts the probability of future default for new applicants.

---

## Business Problem

Financial institutions face significant losses when borrowers fail to repay loans. Traditional credit assessment methods can be time-consuming and may not fully capture complex risk patterns.

The goal of this project is to build a predictive model that can:

* Identify high-risk borrowers
* Support loan approval decisions
* Reduce default-related financial losses
* Improve overall risk management strategies

---

## Dataset

**Source:** Kaggle – Give Me Some Credit Dataset

The dataset contains customer financial information, including:

* Age
* Monthly Income
* Debt Ratio
* Number of Open Credit Lines
* Number of Late Payments
* Credit Utilization
* Real Estate Loans
* Dependents

**Target Variable**

* `SeriousDlqin2yrs`

  * 1 = Customer defaulted
  * 0 = Customer did not default

---

## Project Workflow

### 1. Data Collection

* Imported the dataset into Python using Pandas.
* Examined data structure and feature descriptions.

### 2. Data Cleaning

* Handled missing values.
* Removed duplicates where necessary.
* Verified data types and consistency.

### 3. Exploratory Data Analysis (EDA)

Performed financial risk analysis through visualizations and statistical summaries, including:

* Debt Ratio vs Default Risk
* Monthly Income vs Default Risk
* Credit Utilization Analysis
* Age Group Risk Trends
* Correlation Analysis

### 4. Data Preprocessing

* Feature selection
* Train-test split
* Feature scaling using StandardScaler

### 5. Machine Learning Models

The following models were trained and evaluated:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

### 6. Model Evaluation

Models were assessed using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Key Findings

* Higher debt ratios are associated with increased default risk.
* Customers with lower income tend to have a higher probability of default.
* High credit utilization is a strong indicator of financial distress.
* Historical delinquency behavior is one of the strongest predictors of future default.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* Jupyter Notebook / Google Colab

---

## Project Structure

```text
credit-risk-prediction/
│
├── credit_risk_prediction.ipynb
├── README.md
├── requirements.txt
├── credit_risk_model.pkl
├── scaler.pkl
└── images/
```

## Future Improvements

* Hyperparameter tuning
* SHAP explainability analysis
* Credit risk dashboard using Streamlit
* Probability-based risk scoring system
* Model deployment as a web application

---

## Business Impact

This project demonstrates how machine learning can be applied to real-world financial risk management. The resulting model can help lenders make data-driven decisions, improve credit approval processes, and reduce exposure to loan defaults.

---

## Author

Mosh Letsie
