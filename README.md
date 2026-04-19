 📊 Customer Churn Analysis Project
 
 Overview

This project performs end-to-end analysis of customer churn using Python, SQL, and Power BI. The goal is to identify key drivers of churn and provide actionable business insights to improve customer retention.

Tools & Technologies
Python (Pandas, NumPy, Scikit-learn)
SQL (MySQL)
Power BI (Data Visualization)

 - Project Structure
   
 -Data/
Contains raw dataset (`churn.csv`) used for analysis.

-Jupyter notebooks/
Includes Jupyter Notebook for:
* Data cleaning
* Exploratory Data Analysis (EDA)
* Feature understanding

-SQL/
Contains SQL queries used to:
* Calculate churn rate
* Analyze churn by payment method
* Perform aggregations for business insights

-Dashboard/
* Power BI Dashboard (`.pbix`)
* Dashboard screenshot (`.pdf`)

📈 Key Insights

🔹 Customer Behavior
* Month-to-month contract customers have the highest churn rate compared to long-term contracts
* Customers with shorter tenure (new customers) are significantly more likely to churn
* Long-term customers show strong retention patterns

🔹 Revenue & Charges
* Customers with higher monthly charges have a higher probability of churn
* Lower charge segments show relatively stable retention
* Pricing strategy plays a key role in churn behavior

🔹 Payment Methods
* Customers using electronic check show the highest churn
* Automatic payment methods (credit card, bank transfer) show better retention
* Payment convenience directly impacts customer loyalty

🔹 Service-Based Insights
* Fiber optic users tend to churn more than DSL users
* Customers without additional services (security/backup) show higher churn

📈 SQL Analysis Highlights
* Calculated overall churn rate using aggregation functions
* Used CASE WHEN logic to segment churned vs retained customers
* Grouped customers by payment method to identify high-risk segments

📈 Python Analysis Highlights
* Cleaned missing and inconsistent data
* Converted categorical variables for analysis
* Performed exploratory data analysis to identify patterns
* Built a basic predictive model (Logistic Regression)

📈 Power BI Dashboard Features
* KPI Card showing overall churn rate
* Contract-wise churn comparison
* Tenure-based churn trends
* Payment method distribution
* Charges-based churn segmentation
* Interactive filters (Contract, Gender, Internet Service)


This project demonstrates how data can be used to identify churn drivers and support strategic decision-making. The combination of Python, SQL, and Power BI provides a complete analytics workflow from raw data to business insights.
