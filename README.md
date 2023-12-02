# credit_risk_classification
# Module 12 Report Template
## Overview of the Analysis

The purpose of this analysis was to develop and evaluate machine learning models for predicting loan status based on financial information. Two key stages involved in the analysis were:

Logistic Regression with Original Data:

1. Fitted a logistic regression model to the original data to predict loan status.
2. Assessed the model's performance using metrics such as accuracy, precision, recall, and F1-score.

Logistic Regression with Resampled Data:

1. Utilized RandomOverSampler to address class imbalance in the dataset.
2. Fitted a logistic regression model to the resampled data and evaluated its performance.
   
Financial Information and Prediction Target
The dataset contained financial information such as loan size, interest rate, borrower income, etc. The goal was to predict the loan status (healthy or high-risk) based on this information.

**Results**

**Machine Learning Model 1 (Logistic Regression with Original Data):**
Balanced Accuracy: 0.952
Precision and Recall:
Healthy Loans (Label 0): Precision=1.00, Recall=0.99
High-Risk Loans (Label 1): Precision=0.85, Recall=0.91
F1-Score (High-Risk Loans): 0.88

**Machine Learning Model 2 (Logistic Regression with Resampled Data):**
Balanced Accuracy: 0.995
Precision and Recall:
Healthy Loans (Label 0): Precision=0.99, Recall=0.99
High-Risk Loans (Label 1): Precision=0.99, Recall=0.99
F1-Score (High-Risk Loans): 0.99

Summary
The logistic regression model with resampled data (Model 2) outperforms the model trained on the original data. It achieves a higher balanced accuracy and demonstrates good precision, recall, and F1-score for both healthy and high-risk loans.

Recommendation:

The logistic regression model with resampled data is recommended for its superior performance.
The choice depends on the specific problem. In this case, achieving balance in predicting both healthy and high-risk loans is crucial, and the resampled model is best in this regard.
