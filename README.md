# Customer Churn Classification using Random Forest Classifier

## Overview
This project involves predicting customer churn for a telecommunications company using machine learning. The task is to predict whether a customer will churn based on various features such as their contract type, tenure, and charges. A **Random Forest Classifier** model is used for this classification task.

## Problem Statement
Customer churn prediction is essential for businesses to retain their customers and reduce revenue losses. By analyzing customer data, we aim to predict whether a customer is likely to churn or not, allowing businesses to take proactive measures.

## Dataset
The dataset used contains customer-related features, including:
- **Customer demographics**
- **Services used**
- **Monthly charges**
- **Tenure**
- **Total charges**
- **Churn status** (target variable)

## Approach
The solution was developed using the following steps:
1. **Data Preprocessing:**
   - The dataset was cleaned by converting the `TotalCharges` column to numeric values and handling missing data.
   - Categorical variables were encoded using **LabelEncoder**.
   
2. **Feature Selection:**
   - The target variable `Churn` was separated from the features for training.
   
3. **Model Selection:**
   - A **Random Forest Classifier** was chosen for its ability to handle large datasets and prevent overfitting.
   
4. **Hyperparameter Tuning:**
   - **GridSearchCV** was used to find the optimal hyperparameters such as `n_estimators`, `max_depth`, and `min_samples_split`.
   
5. **Model Evaluation:**
   - The model’s performance was evaluated using **accuracy**, **precision**, **recall**, and a **confusion matrix**.




