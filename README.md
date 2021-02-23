# Loan Prediction

This repository contains the data and Jupyter notebook for the Loan Prediction Hackathon challenge hosted by Analytics Vidhya ([https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/](https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/)).

## Predict Loan Eligibility for Dream Housing Finance company

Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers.

### Variables

|Variable|	Description|
|--------|-------------|
|Loan_ID|	Unique Loan ID|
|Gender	|Male/ Female|
|Married	|Applicant married (Y/N)|
|Dependents	|Number of dependents|
|Education	|Applicant Education (Graduate/ Under Graduate)|
|Self_Employed	|Self employed (Y/N)|
|ApplicantIncome	|Applicant income|
|CoapplicantIncome	|Coapplicant income|
|LoanAmount	|Loan amount in thousands|
|Loan_Amount_Term	|Term of loan in months|
|Credit_History	|Credit history meets guidelines|
|Property_Area	|Urban/ Semi Urban/ Rural|
|Loan_Status	(Target) |Loan approved (Y/N)|

## Data science process

The data science process followed in the notebook is:
  1. Loading the data
  2. Understanding the variables.
  3. Exploratory Data Analysis (EDA).
  4. Feature Engineering.
  5. Generating machine learning models.
  6. Tuning the machine learning model parameters.
  7. Generating a CSV file for submission.

The challenge is still on and I am still working on a better model. 
The current model I have (**Random forest model**) has a maximum accuracy of **78%**, which ranks me at position **3708 out of 8383 participants**. 

Working is still up and running!


Happy waiting (for final solution)!!! 
