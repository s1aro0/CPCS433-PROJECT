# Telecom Customer Churn Prediction

This project is about predicting customer churn in a telecom company using machine learning.

Customer churn means that a customer stops using the company service. In this project, I used customer data to train different machine learning models and see which model can predict churn better.

## Dataset

The dataset used in this project is the **Telcom Customer Churn Dataset** from Kaggle.

Dataset source: [Telcom Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/mosapabdelghany/telcom-customer-churn-dataset)

The dataset file used in this project is:

`WA_Fn-UseC_-Telco-Customer-Churn.csv`

The dataset contains information about telecom customers, such as:

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

The target column is `Churn`.

- `Yes` means the customer left the company
- `No` means the customer stayed with the company

## Project Goal

The goal of this project is to build a machine learning model that can predict whether a customer is likely to churn or not.

This kind of prediction can help telecom companies understand their customers better and try to reduce customer loss.

## What I Did

In this notebook, I followed the main steps of a machine learning project:

1. Loaded the dataset
2. Explored the data
3. Checked the data types and missing values
4. Cleaned the data
5. Removed unnecessary columns like `customerID`
6. Converted categorical values into numeric values
7. Visualized the data to understand churn patterns
8. Split the data into training and testing sets
9. Used SMOTE to handle class imbalance
10. Trained different machine learning models
11. Compared the models using accuracy and classification reports
12. Used ROC curves and feature importance to understand the results better

## Models Used

The models used in this project are:

- Random Forest
- Tuned Random Forest
- XGBoost
- Tuned XGBoost
- Logistic Regression Pipeline

## Results

The models gave different results. Some models had better accuracy, while others were better at detecting customers who may churn.

Tuning the models helped improve the performance and reduce overfitting. It also made the models more balanced when predicting both churn and non-churn customers.

From the feature importance results, some features had a strong effect on churn, such as:

- Contract type
- Tenure
- Internet service
- Payment method
- Online security
- Tech support
- Monthly charges

## Tools and Libraries

This project was done using Python and Jupyter Notebook.

The main libraries used are:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn
- xgboost

## How to Run the Project

1. Download the project files.
2. Open the notebook:

   `CPCS433_Project_Telco_Churn_Prediction.ipynb`

3. Make sure the dataset file is in the same folder:

   `WA_Fn-UseC_-Telco-Customer-Churn.csv`

4. Run the notebook cells from top to bottom.

If you are using Google Colab, upload the CSV file first, then run the notebook.

## Project Files

- `CPCS433_Project_Telco_Churn_Prediction.ipynb` — main notebook
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — dataset file
- `README.md` — project description

## Conclusion

This project helped me practice the full machine learning process, starting from data cleaning and exploration to model training and evaluation.

It also helped me understand how machine learning can be used in real business problems, such as predicting customer churn and helping companies improve customer retention.
