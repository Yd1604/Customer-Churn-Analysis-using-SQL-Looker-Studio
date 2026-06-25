
**Customer Churn Analysis using SQL & Looker Studio** 

_Project Overview_
This project analyzes customer churn using SQL in Google BigQuery and visualizes the results using Looker Studio. The objective of the project is to identify the factors contributing to customer churn and provide business recommendations that could help improve customer retention.

_Business Problem_
Customer churn is one of the biggest challenges for subscription-based businesses.

The company wants to understand:
How many customers have churned?
Which customer groups are most likely to churn?
Which services are associated with higher churn?
What actions can help reduce customer churn?

_Tools Used_


Google BigQuery
SQL
Looker Studio
GitHub

_Dataset_
Dataset: IBM Telco Customer Churn Dataset
The dataset contains information about over 7,000 customers, including:

_Customer demographics_
Contract type
Internet service
Monthly charges
Tenure
Churn status

_Project Workflow_

Step 1: Data Loading
Created a BigQuery project.
Imported the customer churn CSV dataset into Google BigQuery.
Checked data types and validated the dataset.

Step 2: Data Exploration
Explored the dataset to understand:
Number of customers
Customer attributes
Churn distribution
Available business variables

Step 3: SQL Analysis
SQL queries were written to answer key business questions such as:
Total customers
Total churned customers
Customer churn rate
Churn by contract type
Churn by internet service
Average monthly charges of churned customers
Churn by senior citizen status

_SQL techniques used:_
SELECT
WHERE
GROUP BY
ORDER BY
COUNT()
AVG()
COUNTIF()
ROUND()

_Step 4: Dashboard Development_
A dashboard was created in Looker Studio to present the analysis visually.
Dashboard includes:
Total Customers
Churn Rate
Average Monthly Charges
Churn by Contract Type
Churn by Internet Service
Monthly Charges by Churn Status
Churn by Senior Citizen

_Key Findings_
The analysis identified several customer churn patterns:
Month-to-month contracts experienced the highest customer churn.
Fibre Optic customers had the highest number of churned customers.
Customers with higher monthly charges were more likely to churn.
Certain customer segments showed higher churn risk than others.

_Business Recommendations_
Based on the analysis, the following recommendations were made:
Encourage customers to move from month-to-month contracts to longer-term contracts through loyalty rewards and discounts.
Investigate customer satisfaction and pricing for Fibre Optic services.
Offer bundled plans and promotional discounts to customers with higher monthly charges.
Develop targeted customer retention campaigns for high-risk customer groups.

_Skills Demonstrated_

SQL Data Analysis
Google BigQuery
KPI Reporting
Data Cleaning
Data Aggregation
Customer Analytics
Dashboard Development
Business Insights
Data Storytelling
