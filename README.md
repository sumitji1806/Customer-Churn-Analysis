
Customer Churn Analysis

This project explores customer churn behavior using a dataset from a telecommunications company. The goal is to analyze patterns in customer data to understand the key factors that contribute to churn and potentially build predictive models to identify customers at risk.


The dataset contains information such as customer demographics, account details, service usage, and whether the customer has churned.


## Features Description

| Feature             | Description |
|---------------------|-------------|
| `customerID`        | Unique ID assigned to each customer |
| `gender`            | Gender of the customer |
| `SeniorCitizen`     | Indicates if the customer is a senior citizen (1 = Yes, 0 = No) |
| `Partner`           | Whether the customer has a partner (Yes/No) |
| `Dependents`        | Whether the customer has dependents (Yes/No) |
| `tenure`            | Number of months the customer has stayed with the company |
| `PhoneService`      | Indicates if the customer has phone service |
| `MultipleLines`     | Indicates if the customer has multiple lines |
| `InternetService`   | Type of internet service (DSL, Fiber optic, No) |
| `OnlineSecurity`    | Whether the customer has online security service |
| `OnlineBackup`      | Whether the customer has online backup |
| `DeviceProtection`  | Whether the customer has device protection service |
| `TechSupport`       | Whether the customer has tech support service |
| `StreamingTV`       | Whether the customer has streaming TV |
| `StreamingMovies`   | Whether the customer has streaming movies |
| `Contract`          | Type of customer contract (Month-to-month, One year, Two year) |
| `PaperlessBilling`  | Whether the customer uses paperless billing |
| `PaymentMethod`     | Customer’s payment method |
| `MonthlyCharges`    | The amount charged to the customer monthly |
| `TotalCharges`      | The total amount charged to the customer |
| `Churn`             | Whether the customer has churned (Yes/No) |


##  Data Cleaning Notes

- `TotalCharges` column is of type `object`, requires conversion to numeric.
- No missing values found across columns.

## Tools Used

- Python (Pandas, NumPy)
- Matplotlib / Seaborn for visualization
- Jupyter Notebook 

## Potential Analyses

- Churn distribution by contract type, internet service, and payment method
- Tenure analysis of churned vs retained customers
- Impact of monthly charges on churn probability

## Author

**Sumit Lohani**  
[LinkedIn](https://www.linkedin.com/in/sumit-lohani-56183230b) | [GitHub](https://github.com/sumitji1806)


