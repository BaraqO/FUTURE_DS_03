# FUTURE_DS_03
Loan Application Prediction Model to determine whether loan applications get approved or denied. 
Using a dataset containing features like applicant Income, Loan Amount, and Credit History, I implemented multiple machine learning models.
## Features of the Dataset
  1. Loan_ID: Unique Loan Identifier
  2. Gender: Male/Female
  3. Married: Applicant's marital status
  4. Dependents: Number of dependents
  5. Education: Applicant's education level
  6. Self-Employed: Whether the applicant is self-employed
  7. ApplicantIncome: Applicant's Income
  8. CoapplicantIncome: Co-applicant's Income
  9. Loan Amount: Loan amount requested
  10. Loan_Amount_term: Term of loan in months
  11. Credit_History: Whether the applicant has a credit history (1=yes, 0=no)
  12. Property_Area: Urban, Rural or SemiUrban
  13. Loan_Status: Whether the loan was approved or not (Y/N)

## Libraries Used
  1. Pandas
  2. Numpy
  3. Matplotlib
  4. sklearn
  5. Standardscaler
  6. labelencoder
## Data Preprocessing
  -Handled missing values in columns by filling them with appropriate statistical measures
  -created new features TotalIncome, Loan-Income-Ratio, and Debt-Income-Ratio for better model performance
  -Normalized features using StandardScaler
