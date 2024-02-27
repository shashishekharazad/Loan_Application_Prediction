# Loan Application Prediction

## Problem Statement:
Banks encounter numerous loan applications daily, necessitating efficient processing mechanisms. The accuracy of loan approvals greatly impacts a bank's profitability and customer satisfaction. Credit history is a pivotal factor in assessing loan applications, necessitating effective data management and analysis.

## Objective:
The main objective of our Loan Application Prediction algorithm is to develop a robust and accurate machine learning model that can predict the likelihood of loan approval for applicants based on their profiles and historical data. Our goal is to provide a reliable tool for banks and financial institutions to automate the initial screening process, improve efficiency, and make informed lending decisions while minimizing the risk of default.

### The Data

Variable | Description
----------|--------------
Loan_ID | Unique Loan ID
Gender | Male/ Female
Married | Applicant married (Y/N)
Dependents | Number of dependents
Education | Applicant Education (Graduate/ Under Graduate)
Self_Employed | Self employed (Y/N)
ApplicantIncome | Applicant income
CoapplicantIncome | Coapplicant income
LoanAmount | Loan amount in thousands
Loan_Amount_Term | Term of loan in months
Credit_History | credit history meets guidelines
Property_Area | Urban/ Semi Urban/ Rural
Loan_Status | Loan approved (Y/N)

Applied Data Preprocessing and PCA algorithm to reduce the data into two dimensions to visualize the classification of data using classification techniques like:

### Logistic Regression:
Logistic regression is a simple and interpretable algorithm that is widely used for binary classification tasks.
It works well with linearly separable data and provides probabilistic outputs, making it easy to interpret.

### Random Forest:
Random forest is an ensemble learning method that combines multiple decision trees to improve predictive performance.
It can handle non-linear relationships and interactions between features and is less prone to overfitting compared to individual decision trees.

### Support Vector Machines (SVM):
SVM is a powerful algorithm for binary classification tasks that works well with both linear and non-linear decision boundaries.
It is effective in high-dimensional spaces and is less affected by overfitting, especially in cases where the number of features is greater than the number of samples.

### K-Nearest Neighbors (KNN):
KNN is a simple yet effective algorithm that classifies instances based on their similarity to neighboring instances in the feature space.
It can be particularly useful when there are local patterns or clusters in the data.
