# Telecom Customer Churn Prediction

This project focuses on predicting customer churn in a telecom company using machine learning.

Customer churn means that a customer stops using the company service. The project uses customer information to predict whether a customer is likely to leave or stay with the company.

## Dataset

The dataset used in this project is the **Telcom Customer Churn Dataset** from Kaggle.

Dataset source: [Telcom Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/mosapabdelghany/telcom-customer-churn-dataset)

The dataset file used is:

`WA_Fn-UseC_-Telco-Customer-Churn.csv`

The dataset contains customer information such as:

- Gender
- Senior citizen status
- Partner and dependents
- Tenure
- Phone service
- Internet service
- Contract type
- Payment method
- Monthly charges
- Total charges
- Churn status

The target column is `Churn`, where `Yes` means the customer left the company and `No` means the customer stayed.

## Project Goal

The goal of this project is to build machine learning models that can predict whether a telecom customer is likely to churn.

This type of prediction can help telecom companies understand customer behavior and identify important factors that may lead to customer loss.

## Project Workflow

The project includes the main steps of a machine learning process:

- Data loading and exploration
- Data cleaning and preprocessing
- Removing unnecessary columns
- Encoding categorical features
- Data visualization
- Train-test splitting
- Handling class imbalance using SMOTE
- Training different machine learning models
- Evaluating model performance
- Using ROC curves and feature importance for result analysis

## Models Used

The following machine learning models were used:

- Random Forest
- Tuned Random Forest
- XGBoost
- Tuned XGBoost
- Logistic Regression Pipeline

## Results Summary

The models produced different results. Some models achieved higher accuracy, while others performed better in detecting customers who are likely to churn.

Model tuning helped reduce overfitting and improved the balance between predicting churn and non-churn customers.

The results showed that several features had an important effect on customer churn, including:

- Contract type
- Tenure
- Internet service
- Payment method
- Online security
- Tech support
- Monthly charges

## Tools and Libraries

This project was developed using Python and Jupyter Notebook.

Main libraries used:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn
- xgboost

## Conclusion

This project demonstrates how machine learning can be used to predict customer churn in a telecom company.

It covers the main stages of a machine learning project, including data preprocessing, model training, model evaluation, and result interpretation.
