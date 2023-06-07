# Telco Customer Churn

## Project Domain
The domain used in this project is telecommunications. One of the problems that becomes a measure of product success in all fields is customer churn. Customer retention is one of the efforts that companies can make by analysing customer behaviour.

Dataset source : https://drive.google.com/file/d/1ldO3J_BqeeCaVvV8mEmfBm4MPBgvuJ6T/view?usp=sharing

## Business Understanding
In this case, the telecommunications company wanted to study customer behaviour in order to reduce churn. The company has data on the type of service, customer account information and demographic information.

### Problem Statement
1. From different types of data on customer characteristics, which variables have the greatest impact on customer churn.
2. From 3 models, namely Logistic Regression, Random Forest Classifier and KNN, which one has the highest accuracy.

### Goals
- Know which characteristic variables have the greatest impact on customer churn.
- Build the best machine learning model to predict this case.

### Solution Statement
On this case, I will use 3 Machine Learning model :
- **Logistic Regression**. Logistic regression is a widely used statistical model for binary classification problems like churn prediction. It is especially useful when there is a need to understand the impact of individual features on the likelihood of churn. Logistic regression models the relationship between the independent variables (customer features) and the dependent variable (churn or not churn) using a logistic function. It provides interpretable coefficients that can help identify the most influential features and their direction of impact.
- **Random Forest Classifier**. Random forest is an ensemble learning technique that combines multiple decision trees to make predictions. It is known for its ability to handle complex relationships between features and has good generalization performance. Random forests can capture non-linearities, interactions, and feature importance. It works well with categorical and numerical features, and it's less sensitive to outliers. Random forest models are robust and less prone to overfitting.
- **K-Nearest Neighbors (KNN)**. KNN is a non-parametric algorithm used for both classification and regression tasks. In churn prediction, KNN can be used as a classification model. KNN predicts the class of a new data point by considering the classes of its k nearest neighbors. It is simple to understand and implement, and it can capture complex decision boundaries. KNN does not assume any underlying distribution of data and can handle imbalanced datasets. However, it can be computationally expensive, especially with large datasets.

## Data Understanding

The dataset include information about :

- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

### Columns Description
- customerID - Customer's ID.
- gender - Customer's gender.
- SeniorCitizen - Whether the customer is a senior citizen or not.
- Partner - Whether the customer has a partner or not.
- Dependents - Whether the customer has dependents or not.
- tenure - How long has the customer subscribed in months.
- PhoneService - Whether the customer has a phone service or not.
- MultipleLines - Whether the customer has multiple lines or not.
- InternetService - Customer’s internet service provider status.
- OnlineSecurity - Whether the customer has online security or not.
- OnlineBackup - Whether the customer has online backup or not.
- DeviceProtection - Whether the customer has device protection or not.
- TechSupport - Whether the customer has tech support or not.
- StreamingTV - Whether the customer has streaming TV or not.
- StreamingMovies - Whether the customer has streaming movies or not.
- Contract - The customer's contract term.
- PaperlessBilling - Whether the customer has paperless billing or not.
- PaymentMethod - The customer’s payment method.
- MonthlyCharges - The amount charged to the customer (monthly).
- TotalCharges - The total amount charged to the customer.
- Churn - Whether the customer churned or not churned.
