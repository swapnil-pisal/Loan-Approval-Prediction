# Loan-Approval-Prediction
Machine learning project to predict loan approval

### Overview
This project predicts whether a loan application will be approved using machine learning.

### Dataset
Contains applicant details such as Gender,Married,Dependents,Education,Self_Employed,ApplicantIncome,CoapplicantIncome,Loan_Amount,Loan_Amount_Term,Credit_History,Loan_Status,Total_Income,LoanIncomeRatio	,IncomeGroup,etc.

### ML Models Used
- Logistic Regression 

### Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

### Result
The model helps automate loan approval decisions with improved accuracy.

##  Repository Structure

This repository contains two types of notebooks:

- learning_notebooks/  
  Notebooks created during the learning and experimentation phase.

- notebooks/  
  Clean, structured notebooks representing the complete end-to-end
  Machine Learning pipeline used for the final project.

## learning notebook model comaparion table

|      Model          | Precision    | Recall    | F1    | AUC    | Overfitting |
| --------------------| -------------| ----------|-------|--------|-------------|
| Logistic Regression | 0.76         | 0.97      | 0.86  | 0.79   | Low         |
| Decision Tree       | 0.76         | 0.81      | 0.79  | 0.72   | High        |
| Random Forest       | 0.77         | 0.93      | 0.84  | 0.77   | Medium      |
| Gradient Boosting   | 0.65         | 0.82      | 0.73  | 0.80   | Medium      |
| XGBoost             | 0.65         | 0.82      | 0.73  | 0.80   | Low         |




