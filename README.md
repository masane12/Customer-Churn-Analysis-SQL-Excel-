# Bank Customer Churn Analysis

This project analyzes bank customer data to identify key factors responsible for customer churn. The analysis is performed using SQL, Excel, and Power BI, with the goal of generating actionable insights and building an interactive dashboard.

---

## Project Overview

The main objective of this project is to understand customer behavior and identify patterns that lead to churn.

- Analyze customer trends and behavior  
- Identify high-risk customers  
- Generate insights to improve retention strategies  

This analysis helps reduce customer acquisition costs and improve overall business performance.

---

## Problem Statement

The bank is facing a high churn rate, which is increasing the cost of acquiring new customers.

The objective is to:

- Identify key factors driving churn  
- Detect customers likely to leave  
- Support data-driven decision-making for retention  

---

## Data Source

- Domain: Banking  

- Dataset Files:
  - Bank_Churn.csv  
  - CustomerInfo.csv  
  - ActiveCustomer.xlsx  
  - CreditCard.xlsx  
  - ExitCustomer.xlsx  
  - Gender.xlsx  
  - Geography.xlsx  

- Dataset Size: 10,000 customer records (4 years)

---

## Data Dictionary (Key Features)

- CustomerId: Unique identifier (not used for analysis)  
- CreditScore: Higher score indicates lower churn probability  
- Geography: Customer location  
- Gender: Demographic information  
- Age: Younger customers show higher churn tendency  
- Tenure: Number of years with the bank  
- Balance: Account balance of the customer  
- NumOfProducts: Number of bank products used  
- HasCrCard: Credit card ownership (1 = Yes, 0 = No)  
- IsActiveMember: Activity status (1 = Active, 0 = Inactive)  
- EstimatedSalary: Customer income  
- Exited: Target variable (0 = Retained, 1 = Churned)  

---

## Data Cleaning and Preparation

- Removed duplicate records  
- Eliminated irrelevant columns  
- Standardized data types  
- Handled missing values  
- Cleaned text fields  
- Ensured consistent formatting for dates and numbers  

---

## Data Modeling

- Implemented a Star Schema model  
- Created relationships between fact and dimension tables  
- Fact Table: Customer Churn  
- Dimension Tables: Geography, Gender, Customer Info  
- Modeling performed using Power BI and Power Pivot  

---

## Project Workflow

- Requirement gathering  
- Data collection (Excel, CSV, SQL)  
- Data cleaning and transformation  
- Data modeling  
- Dashboard creation in Power BI  
- DAX calculations  
- Report publishing and sharing  

---

## Dashboard

The Power BI dashboard includes:

- Total Customers  
- Churn Rate (%)  
- Active vs Inactive Customers  
- Churn by Geography, Gender, and Age  
- Customer segmentation  
- Trend analysis  

---

## Key Insights

- Total Customers: 10,000  
- Churn Rate: 20.37% (above industry average)  
- Retention Rate: 79.63%  
- Active Customers: 51.51%  

### Key Observations

- Customers aged 35–45 have higher churn  
- Customers with 1–2 products are more likely to leave  
- Inactive customers show significantly higher churn  
- Germany has the highest churn rate (~32%)  
- Most customers leave within 4–5 years  
- Higher churn observed among customers with lower credit scores  

---

## Recommendations

- Improve customer service and issue resolution  
- Introduce loyalty and reward programs  
- Increase customer engagement through personalized offers  
- Focus on activating inactive customers  
- Apply customer segmentation for targeted strategies  
- Promote cross-selling and upselling  
- Use predictive models to identify at-risk customers  

---

## Tools and Technologies

- SQL – Data extraction and querying  
- Excel – Data cleaning and preprocessing  
- Power BI – Data visualization and dashboard creation  
