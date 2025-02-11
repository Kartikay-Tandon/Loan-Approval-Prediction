# Loan-Approval-Prediction
#Overview

This project focuses on predicting loan approvals using machine learning models, specifically Random Forest and XGBoost. By leveraging historical loan application data, the model aims to determine whether a loan should be approved or rejected based on key applicant features.

#Features

Utilizes Random Forest and XGBoost for accurate loan approval prediction.

Performs data preprocessing, including handling missing values and encoding categorical variables.

Implements feature engineering to improve prediction accuracy.

Includes model evaluation metrics such as accuracy, precision, recall, and F1-score.

#Dataset

The dataset consists of historical loan application records with features such as:

person_age – Age of the applicant.
person_income – Applicant's income.
person_home_ownership – Type of home ownership (e.g., rent, mortgage, own).
person_emp_length – Length of employment in years.
loan_intent – Purpose of the loan (e.g., education, medical, etc.).
loan_grade – Credit grade assigned to the loan.
loan_amnt – Loan amount requested.
loan_int_rate – Interest rate of the loan.
loan_percent_income – Loan amount as a percentage of income.
cb_person_default_on_file – Whether the applicant has a prior default on file (Yes/No).
cb_person_cred_hist_length – Length of the applicant's credit history in years.
loan_status – Target variable indicating loan approval status (0: Not approved, 1: Approved).



#Usage

Load the dataset: The notebook provides a method to load and preprocess the data.

Train the models: Run the notebook to train Random Forest and XGBoost models.

Evaluate performance: Compare model performance using different evaluation metrics.

Make predictions: Use the trained models to predict loan approvals for new applicants.

#Model Performance

Random Forest: Provides robust performance with high interpretability.

XGBoost: Offers superior accuracy and handles complex patterns in the data.

#Results

The models are evaluated based on:

Accuracy Score

Confusion Matrix

Precision, Recall, and F1-score

ROC Curve and AUC Score

#Future Improvements

Optimize hyperparameters using Grid Search or Bayesian Optimization.

Experiment with Deep Learning models for better performance.

Deploy the model using Flask or FastAPI for real-time predictions.
