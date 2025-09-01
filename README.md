# Customer Churn Analysis

## Project Overview

This project analyzes the **Customer Churn dataset** using Python. It covers **data manipulation, data visualization, and machine learning models** to understand customer behavior and predict churn.

The workflow includes:

* Extracting and filtering customer data
* Performing exploratory data analysis (EDA)
* Building visualizations for insights
* Implementing regression and classification models
* Evaluating model performance


##  Dataset

The dataset used is **`customer_churn.csv`**, which contains customer information such as:

* Demographics (gender, senior citizen, partner, dependents)
* Services (phoneservice, internetservice, contract type, payment method)
* Billing details (monthly charges, total charges, tenure)
* Target variable: **Churn (Yes/No)**


## Technologies Used

* **Python**
* **Pandas & NumPy** → Data manipulation
* **Matplotlib & Seaborn** → Data visualization
* **Scikit-learn** → Machine learning models



##  Data Manipulation

* Extracted specific columns (5th, 15th)
* Filtered customers based on multiple conditions
* Sampled random records
* Counted churn distribution


##  Data Visualization

* **Bar Plot** → Distribution of Internet Services
* **Histogram** → Distribution of Tenure
* **Scatter Plot** → Tenure vs. Monthly Charges
* **Box Plot** → Contract type vs. Tenure



## Machine Learning Models

### Regression

* **Linear Regression**

  * Predicted Monthly Charges using Tenure
  * Evaluated with RMSE

* **Logistic Regression**

  * Single feature: Monthly Charges
  * Multi-feature: Tenure & Monthly Charges
  * Evaluated with confusion matrix & accuracy

### Classification

* **Decision Tree Classifier**

  * Target: Churn
  * Feature: Tenure

* **Random Forest Classifier**

  * Target: Churn
  * Features: Tenure, Monthly Charges



## Results

* Visualizations highlighted trends in customer churn
* Logistic regression, decision tree, and random forest were able to predict churn with reasonable accuracy
* Random Forest generally performed better compared to simple models
