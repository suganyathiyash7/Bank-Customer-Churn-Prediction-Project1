# Bank Customer Churn Prediction
## 📝 Introduction
Customer churn refers to when a customer stops using a company's products or services. In the banking sector, minimizing churn is crucial to maintaining profitability. This project focuses on analyzing customer churn data to identify key patterns and build a business intelligence dashboard for insights and prediction.
## 📁 Folders & Files Description
###  1. Bank Customer Churn Prediction.csv
This is the main dataset used for analysis.
It contains customer demographic and financial data along with a column indicating whether the customer has churned.
Used for performing data cleaning, exploration, and modeling.
### 2. Bank Customer churn PowerBi.pbix
A Power BI dashboard file that visualizes insights from the data.
Contains multiple visuals such as charts, KPIs, and slicers for interactive analysis.
Useful for business users and stakeholders to understand churn drivers.
### 3. Bank Customer churn Prediction report Summary.docx
A Word document summarizing the findings, recommendations, and insights.
Includes interpretations of the dashboard and suggestions for churn reduction strategies.
Suitable for presentation or business reporting.
## 🪜 Project Workflow 
This project follows a structured analysis and visualization pipeline tailored for Power BI. Below are the key steps involved:
### 1.  Data Loading
* Imported the CSV file Bank Customer Churn Prediction.csv into Power BI.
* Verified column data types and initial data structure.
### 2.  Data Cleaning & Preprocessing
* Handled missing values (e.g., Gender filled using mode).
* Removed unnecessary fields like RowNumber, Surname, and CustomerId.
* Created new calculated fields using DAX (e.g., Churn Rate %).
* Verified consistency and corrected anomalies in columns like Balance and Tenure.
### 3.  Exploratory Data Analysis (EDA)
* Performed descriptive statistics to understand feature distributions.
* Identified high-churn segments by filtering on Geography, Gender, and IsActiveMember.
* Correlation and comparative analysis helped identify churn-prone customer profiles.
### 4.  Dashboard Creation in Power BI
* Created interactive visuals including:
      Churn vs Non-Churn comparison
      Gender and Geography-wise churn breakdown
      Age and Tenure distributions
      KPI cards showing total customers, churn count, and churn rate
* Added slicers for dynamic filtering by Geography, Gender, etc.
* Applied filters and sorting to highlight key customer segments.

##  Data Analysis Summary

* Total Records: 10,000 customers 
* Churned Customers: 2,037 (≈20.37%)
* Non-Churned Customers: 7,963
* Average Credit Score: 650.5
* Average Age: 38.9 years
* Average Tenure: 5 years
* Average Balance: ₹76,486
* Credit Card Holders: ~70.5%
* Active Members: ~51.5%

## Findings from the Dashboard & Analysis:

* Customers with lower tenure and zero balance are more likely to churn.
* Churn rate is higher among inactive members and non-credit-card holders.
* Age and salary alone do not directly drive churn but correlate when combined with account activity.
* Country-wise churn shows significant variation — for example, higher churn in Germany compared to France or Spain.

##  Column Descriptions (Spreadsheet)
| Column Name        | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| customer_id        | Unique identifier for each customer                                         |
| credit_score       | Credit score of the customer                                                |
| country            | Country of the customer (France, Germany, Spain)                            |
| gender             | Gender of the customer (Male/Female)                                        |
| age                | Age of the customer                                                         |
| tenure             | Number of years the customer has been with the bank                         |
| balance            | Account balance of the customer                                             |
| products_number    | Number of bank products the customer uses                                   |
| credit_card        | Whether the customer owns a credit card (1 = Yes, 0 = No)                   |
| active_member      | Whether the customer is an active member (1 = Yes, 0 = No)                  |
| estimated_salary   | Customer's estimated annual salary                                          |
| churn              | Target variable: 1 = Customer churned, 0 = Customer retained                |


### 🧾 Insight Generation & Summary Reporting
Captured major findings in the report (Bank Customer churn Prediction report Summary.docx)
Provided actionable recommendations such as:

Target loyalty programs at high-risk groups (e.g., inactive members, high-tenure customers in Germany).
Focus retention strategies on female customers and older demographics.

