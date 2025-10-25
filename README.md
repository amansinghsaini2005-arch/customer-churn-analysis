📊 Customer Churn Analysis

This project analyzes customer churn data to understand factors that influence customer retention and loss. Using Python and data visualization libraries, we explore demographic, service-related, and contract-based variables to uncover key insights.

🧠 Objective

The goal of this project is to:

Identify the characteristics of churned vs. retained customers.

Explore how different features (like contract type, payment method, internet service, etc.) impact churn.

Build visualizations to highlight patterns in customer behavior.

🗂️ Dataset

File: Customer Churn.csv
Total Rows: 7,043
Total Columns: 21

Key Columns:
Column	Description
customerID	Unique ID for each customer
gender	Male or Female
SeniorCitizen	1 if senior citizen, 0 otherwise
Partner	Whether the customer has a partner
Dependents	Whether the customer has dependents
tenure	Number of months with the company
PhoneService	Whether customer has phone service
InternetService	Type of internet service
Contract	Type of contract (Month-to-month, One year, Two year)
PaymentMethod	Customer’s payment method
MonthlyCharges	The amount charged per month
TotalCharges	Total amount charged
Churn	Whether the customer has churned (Yes/No)
🧹 Data Cleaning

Replaced missing or blank values in TotalCharges with 0.

Converted TotalCharges from string to float.

Checked for and removed duplicate records.

Verified there were no null values in the dataset.

📈 Exploratory Data Analysis (EDA)
Performed using:

pandas, numpy for data manipulation

matplotlib, seaborn for data visualization

Key Visuals:

📊 Count of Customers by Churn

🥧 Percentage of Churned Customers

👵 Churn by Senior Citizen

📆 Tenure Distribution by Churn

📑 Churn by Contract Type

💳 Churn by Payment Method

🌐 Churn by Internet and Online Services

📉 Insights

Customers with month-to-month contracts are more likely to churn.

Electronic check payment method shows higher churn rates.

Customers with short tenure tend to leave more frequently.

Senior citizens have a higher churn percentage.

Customers using fiber optic internet churn more often than DSL.

⚙️ Technologies Used

Python 3

pandas

numpy

matplotlib

seaborn

Jupyter Notebook / VS Code
