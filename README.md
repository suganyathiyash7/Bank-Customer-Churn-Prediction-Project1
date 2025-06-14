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
### 1. 📥 Data Loading
* Imported the CSV file Bank Customer Churn Prediction.csv into Power BI.
* Verified column data types and initial data structure.
### 2. 🧹 Data Cleaning & Preprocessing
* Handled missing values (e.g., Gender filled using mode).
* Removed unnecessary fields like RowNumber, Surname, and CustomerId.
* Created new calculated fields using DAX (e.g., Churn Rate %).
* Verified consistency and corrected anomalies in columns like Balance and Tenure.
### 3. 📊 Exploratory Data Analysis (EDA)
* Performed descriptive statistics to understand feature distributions.
* Identified high-churn segments by filtering on Geography, Gender, and IsActiveMember.
* Correlation and comparative analysis helped identify churn-prone customer profiles.
