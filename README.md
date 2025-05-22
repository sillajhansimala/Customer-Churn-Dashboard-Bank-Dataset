# Customer-Churn-Dashboard-Bank-Dataset
# Bank Customer Churn Analysis and Dashboard

## Project Overview

This project analyzes customer churn in the banking sector. Using a popular dataset, we explore why some customers leave the bank while others stay. We cleaned and prepared the data using Python, dropping some unnecessary columns, and then created a Power BI dashboard to visualize important insights about customer churn and customer behavior.

The dashboard helps answer questions like:
- How many customers left the bank versus stayed
- How customer features such as age, gender, geography, and product usage relate to churn
- Key summaries including average balance, tenure, and churn rates

## Dataset Details

The dataset contains information about bank customers and whether they churned (left) or not. It includes the following fields:

- **Customer ID**: Unique identifier for each customer (Dropped during preprocessing)  
- **Surname**: Customer's last name (Dropped during preprocessing)  
- **RowID**: Row identifier (Dropped during preprocessing)  
- **Credit Score**: Numeric credit score  
- **Geography**: Country of residence (France, Spain, or Germany)  
- **Gender**: Male or Female  
- **Age**: Customer's age  
- **Tenure**: Number of years with the bank  
- **Balance**: Account balance amount  
- **NumOfProducts**: Number of bank products used (e.g., savings account, credit card)  
- **HasCrCard**: Whether the customer has a credit card (1 = yes, 0 = no)  
- **IsActiveMember**: Whether the customer is an active member (1 = yes, 0 = no)  
- **EstimatedSalary**: Customer's estimated salary  
- **Exited**: Whether the customer churned (1 = yes, 0 = no)  

## Project Files

- **datasets/**  
  - `BankChurners_Original.csv`: Original raw data from Kaggle  
  - `BankChurners_Cleaned.csv`: Cleaned data after preprocessing (with RowID, Customer ID, and Surname columns removed)  

- **CustomerChurnDashboard.pbix**  
  Power BI dashboard file showing visualizations of churn patterns and customer insights  

- **images/**  
  Screenshots of the Power BI dashboard for preview  

- **README.md**  
  This project description file  

## Tools Used

- Python: For cleaning and preprocessing the dataset  
- Power BI: To build the interactive dashboard  

## Dataset Source

The original dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/shubhammeshram579/bank-customer-churn-prediction).

Feel free to explore the cleaned data and Power BI dashboard to understand the factors influencing customer churn in banking!

