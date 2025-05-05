# Credit-Risk-Analysis
# Credit Risk Analysis

This project uses machine learning to predict the likelihood of a loan applicant defaulting on a loan. The dataset contains various features such as **demographics**, **financial history**, and **behavioral data** that are used to classify whether an applicant will default on a loan or not.

## 🛠️ Project Structure
1. Dataset
The Credit Risk Analysis model uses the "Give Me Some Credit" dataset, which is available on Kaggle. You can download the dataset from the following link:

Give Me Some Credit Dataset on Kaggle

Dataset Features:
Age: Age of the applicant

Loan Amount: Requested loan amount

Credit Score: The applicant’s credit score

Current Balance: Current bank balance of the applicant

Monthly Income: The applicant's monthly income

TARGET: The target variable (1: loan default, 0: no default)

2. Running the Notebooks
The project contains Jupyter notebooks for data preprocessing, model building, and evaluation:

01_EDA_and_preprocessing.ipynb: Data exploration, handling missing values, and scaling the features.

02_model_training.ipynb: Model training (Logistic Regression, XGBoost).

03_model_evaluation.ipynb: Evaluating the models using various metrics (accuracy, precision, recall, ROC-AUC).
