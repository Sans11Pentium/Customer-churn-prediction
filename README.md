# Telecom Customer Churn Prediction

## Problem Statement

Customer churn, or customer attrition, is the loss of clients or customers. In the telecom industry, it refers to customers who stop using a company's services. Predicting churn is crucial for telecom companies because retaining existing customers is often more cost-effective than acquiring new ones. By identifying customers at risk of churning, companies can take proactive measures to retain them, such as offering discounts or personalized services. This project addresses this problem by building a predictive model that helps identify potential churners based on their usage patterns and account information.

![alt text]([http://url/to/img.png](https://soloway.tech/wp-content/uploads/2023/06/Churn-prediction.png))

## Project Overview

This project aims to predict customer churn in a telecom company using a decision tree classifier. The dataset contains various features about customers and their usage patterns, which will be used to build and evaluate the model.

## Dataset

The project uses two datasets from kaggle:

- `churn-bigml-20.csv`: Used for training the model.
- `churn-bigml-80.csv`: Used for testing the model.

Both datasets contain the following columns:

- `State`: The state where the customer resides.
- `Account length`: The number of days the customer has been with the company.
- `Area code`: The area code of the customer.
- `International plan`: Whether the customer has an international plan (yes/no).
- `Voice mail plan`: Whether the customer has a voice mail plan (yes/no).
- `Number vmail messages`: The number of voice mail messages.
- `Total day minutes`: Total minutes of day calls.
- `Total day calls`: Total number of day calls.
- `Total day charge`: Total charges for day calls.
- `Total eve minutes`: Total minutes of evening calls.
- `Total eve calls`: Total number of evening calls.
- `Total eve charge`: Total charges for evening calls.
- `Total night minutes`: Total minutes of night calls.
- `Total night calls`: Total number of night calls.
- `Total night charge`: Total charges for night calls.
- `Total intl minutes`: Total minutes of international calls.
- `Total intl calls`: Total number of international calls.
- `Total intl charge`: Total charges for international calls.
- `Customer service calls`: Number of calls to customer service.
- `Churn`: Whether the customer has churned (yes/no).
