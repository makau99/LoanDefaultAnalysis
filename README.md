# LoanDefaultAnalysis
# Credit Risk Analysis

## Overview
This project analyzes credit risk using machine learning models to predict the likelihood of default. We leverage a dataset containing customer credit history and financial behavior to build a predictive model.

## Business and Data Understanding
### Stakeholder Audience
Our primary stakeholders include:
- **Financial Institutions:** Banks and credit issuers looking to improve credit risk assessment.
- **Risk Analysts:** Professionals who analyze credit data to minimize defaults.
- **Regulatory Bodies:** Organizations that monitor fair lending practices.

### Dataset Choice
The dataset contains information on credit balances, payment history, and demographic details. It is structured with features such as:
- **Credit Limit**
- **Payment Delays**
- **Total Bill Amount**
- **Default Status**
- **Demographic Features (e.g., Gender, Age)**

## Modeling
We implemented and evaluated multiple machine learning models:

-Logistic Regression

-K-Nearest Neighbors (KNN)

-XGBoost Classifier

-LightGBM Classifier

-Random Forest Classifier

-Multi-Layer Perceptron (MLP) Classifier

The best-performing model was LightGBM, which effectively handled categorical data without encoding.
The model had a 73% accuracy and 77% ROC AUC score.  It could recall defaulters 67% of the time.

## Evaluation
### Performance Metrics
We evaluated the model on the test dataset using:
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-score)**
- **Accuracy Score**


## Conclusion
- **Higher credit limits do not always correlate with higher default risk.**
- **Payment delays are key indicators of default.**
- **The model provides a reasonable prediction of credit risk, aiding financial institutions in decision-making.**

Future work includes exploring ensemble models and additional features for improved accuracy. 🎯
