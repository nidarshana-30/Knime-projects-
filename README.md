# Loan Prediction Project – KNIME
## 📌 Project Overview

This project focuses on predicting loan approval status using machine learning workflows in KNIME Analytics Platform. The objective is to analyze historical loan data, clean and preprocess it, and build a predictive model to classify whether a loan will be approved or rejected.

## 🗂 Dataset Description

* Dataset Name: Loan Approval Dataset

* Format: CSV / Excel

* Columns include (examples):

* Loan_ID – Unique identifier for each loan application

* Gender – Applicant gender

* Married – Marital status

* Dependents – Number of dependents

* Education – Education level

* Self_Employed – Whether applicant is self-employed

* ApplicantIncome – Applicant income

* CoapplicantIncome – Coapplicant income

* LoanAmount – Requested loan amount

* Loan_Amount_Term – Term of loan in months

* Credit_History – Credit history (1 = good, 0 = bad)

* Property_Area – Urban/Rural/Semiurban

* Loan_Status – Target variable (Y = Approved, N = Rejected)

## 🧹 Data Cleaning & Preprocessing

Performed using KNIME nodes:

* Missing value handling – Replaced or removed missing entries using Missing Value node.

* Data type conversion – Ensured numeric columns are numeric, categorical columns are strings/factors.

* Encoding categorical variables – Used One-to-Many or String to Number nodes for machine learning models.

* Outlier detection & treatment – Applied Box Plot and Rule Engine nodes.

* Derived columns – Created new features like TotalIncome = ApplicantIncome + CoapplicantIncome.

## 📊 Exploratory Data Analysis (EDA)

Performed within KNIME:

* Loan Status Distribution:
Visualized approvals vs rejections using Bar Chart node.

* Income vs Loan Amount Analysis:
Scatter plots and box plots to understand relationship between income and loan amount.

* Credit History Impact:
Analyzed how credit history affects loan approval.

* Property Area Analysis:
Studied loan approval trends across Urban, Rural, and Semiurban areas.

* Correlation Analysis:
Used Correlation node to find relationships between numeric features.

## 🤖 Model Building

* Algorithms used:

Decision Tree

Random Forest

Logistic Regression

Gradient Boosted Trees

* Model Evaluation:

Used Scorer node for accuracy, precision, recall, and F1-score.

Applied Cross-Validation to ensure robust performance.

* Best Model:
[You can specify here which model performed best based on accuracy/F1-score]

## 🛠 Tools & Technologies

* Tool: KNIME Analytics Platform

* Nodes Used: Data Reader, Missing Value, String to Number, One-to-Many, Rule Engine, Partitioning, Learner & Predictor nodes, Scorer
