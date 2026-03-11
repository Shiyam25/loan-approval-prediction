# Loan Approval Prediction using Machine Learning

## Overview

This project focuses on predicting whether a loan application will be approved or rejected using machine learning classification algorithms. The model analyzes applicant information such as age, income, employment experience, home ownership, and loan details to determine the loan approval status.

The objective of the project is to compare multiple classification models and identify the algorithm that performs best for the loan approval prediction task.


## Dataset

Dataset shape: (45000, 14)

The dataset contains 14 features related to applicant demographics, income, employment history, and loan details.

Some important features include:

- person_age
- person_income
- person_emp_exp
- person_home_ownership
- loan_amnt
- loan_intent
- loan_percent_income

Target variable:

* loan_status

Dataset used in this project is stored in the repository as:
loan_data.csv


## Technologies Used

The project was implemented using the following tools and libraries:

* Python
* Pandas
* NumPy
* Scikit-learn


## Machine Learning Models Used

The following classification models were trained and evaluated in this project:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Random Forest Classifier

Among these models, Random Forest achieved the highest accuracy for this dataset.


## Project Workflow

The main steps followed in this project are:

1. Load the dataset
2. Perform data cleaning
3. Handle missing values
4. Encode categorical variables
5. Split the dataset into training and testing sets
6. Train multiple machine learning models
7. Evaluate and compare model performance


## Files in this Repository

loan_approval_prediction.ipynb – Jupyter notebook containing the full implementation
loan_data.csv – Dataset used for training the model


## Conclusion

This project demonstrates how machine learning classification algorithms can be used to predict loan approval based on applicant information. By comparing multiple models, Random Forest was identified as the best performing model for this dataset.
