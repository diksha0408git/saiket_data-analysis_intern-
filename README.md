# Customer Churn Prediction

## Project Overview
This project focuses on analyzing customer behavior and predicting customer churn using data analysis and machine learning techniques. The objective is to identify customers who are at risk of leaving and provide insights that can help businesses improve customer retention strategies.


## Project Tasks
- **Task 1:** Data Cleaning and Preprocessing  
- **Task 2:** Exploratory Data Analysis (EDA)  
- **Task 3:** Customer Segmentation and Churn Insights  
- **Task 4:** Churn Prediction using Machine Learning  


## Dataset Description
The dataset includes customer demographic details, service subscriptions, contract types, billing information, and churn status.

Target Variable:
- `Churn` (1 = Customer churned, 0 = Customer retained)


## Machine Learning Model
- **Algorithm Used:** Logistic Regression
- **Train-Test Split:** 80% training, 20% testing
- **Feature Scaling:** Applied for better model convergence


## Model Performance
- **Accuracy:** ~79%
- **Precision (Churn):** 0.62
- **Recall (Churn):** 0.52
- **F1-Score (Churn):** 0.56

The model performs well in identifying non-churn customers and provides meaningful predictions for churn-risk customers.


## Key Insights
- Customers with **shorter tenure** have significantly higher churn rates.
- **Month-to-month contracts** show the highest churn compared to long-term contracts.
- **Higher monthly charges** increase the probability of churn.
- Long-term customers demonstrate strong retention behavior.


## Business Impact
The insights and predictions from this project can help businesses:
- Identify high-risk customers early
- Design targeted retention strategies
- Reduce customer loss and improve revenue stability


## Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
