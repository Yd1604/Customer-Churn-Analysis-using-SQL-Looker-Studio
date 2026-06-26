# Customer Churn Analysis using SQL & Looker Studio

## Project Overview

This project analyzes customer churn using **SQL in Google BigQuery** and visualizes the results using **Looker Studio**.

The objective of this project is to identify the factors contributing to customer churn and provide data-driven business recommendations that can help improve customer retention.



## Business Problem

Customer churn is one of the biggest challenges for subscription-based businesses. Losing existing customers can directly impact revenue and long-term business growth.

This project aims to answer the following business questions:

- How many customers have churned?
- Which customer groups are most likely to churn?
- Which services are associated with higher churn?
- What actions can help reduce customer churn?



## 🛠️ Tools Used

- Google BigQuery
- SQL
- Looker Studio
- GitHub



## Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains information for over **7,000 customers**, including:

- Customer Demographics
- Contract Type
- Internet Service
- Monthly Charges
- Customer Tenure
- Churn Status



## Project Workflow

### Step 1: Data Loading

- Created a Google BigQuery project.
- Imported the customer churn CSV dataset.
- Validated the dataset and verified data types.



### Step 2: Data Exploration

Performed an initial exploration of the dataset to understand:

- Total number of customers
- Customer demographics
- Churn distribution
- Available business variables



### Step 3: SQL Analysis

SQL queries were written to answer key business questions, including:

- Total Customers
- Total Churned Customers
- Customer Churn Rate
- Churn by Contract Type
- Churn by Internet Service
- Average Monthly Charges of Churned Customers
- Churn by Senior Citizen Status

### SQL Techniques Used

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- COUNT()
- AVG()
- COUNTIF()
- ROUND()



### Step 4: Dashboard Development

An interactive dashboard was created using **Looker Studio** to present the analysis visually.

### Dashboard Includes

- Total Customers
- Churn Rate
- Average Monthly Charges
- Churn by Contract Type
- Churn by Internet Service
- Monthly Charges Analysis
- Churn by Senior Citizen



## Key Findings

The analysis revealed several customer churn patterns:

- Month-to-month contract customers experienced the highest churn.
- Fiber Optic customers showed the highest number of churned customers.
- Customers with higher monthly charges were more likely to leave the service.
- Certain customer segments demonstrated a higher risk of churn than others.


## Business Recommendations

Based on the findings, the following recommendations were identified:

- Introduce loyalty rewards and discounts to encourage customers to move from month-to-month contracts to long-term contracts.
- Review pricing strategies and customer satisfaction for Fiber Optic services.
- Offer bundled packages and promotional discounts to customers with higher monthly charges.
- Develop targeted customer retention campaigns for high-risk customer groups.



## Skills Demonstrated

This project demonstrates the following technical and analytical skills:

- SQL Data Analysis
- Google BigQuery
- Data Cleaning
- Data Aggregation
- KPI Reporting
- Customer Analytics
- Dashboard Development
- Data Visualization
- Business Insights
- Data Storytelling
