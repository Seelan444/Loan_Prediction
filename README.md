#  Loan Prediction Project

This project predicts whether a loan application is likely to be approved or not based on various applicant features. It is part of a machine learning initiative to automate and streamline the loan approval process.

##  Dataset

The dataset is sourced from a loan prediction challenge and contains information such as:

- Gender, Marital Status, Dependents
- Education and Employment
- ApplicantIncome, CoapplicantIncome
- LoanAmount and Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status (Target variable)

##  Data Preprocessing

- Handled missing values using:
  - **Mode** for categorical features (`Gender`, `Married`, `Self_Employed`, `Credit_History`)
  - **Median** for `LoanAmount`
- Label encoded categorical variables
- Split the dataset into training and testing sets

##  Model Used

A **Logistic Regression** model was trained to predict `Loan_Status`.
