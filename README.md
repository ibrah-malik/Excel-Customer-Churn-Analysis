# Analyzing Customer Churn in Excel: Databel Case Study

## Project Overview
This project focuses on analyzing customer churn for a fictitious telecommunications provider called Databel. By investigating a detailed dataset, the goal is to uncover the primary reasons for customer attrition and provide actionable insights to improve retention.

## Files in this Repository
* **`source_data.xlsx`**: The initial dataset containing customer dimensions and unformatted measures.
* **`final_insights.xlsx`**: The completed Excel workbook featuring data preparation, calculated pivot tables, and the final interactive dashboard.

## Business Problem
It is typically easier to retain existing customers than to attract new ones, making churn reduction a major priority. The objective of this analysis is to:
* Calculate the overall churn rate.
* Identify key demographic and contractual drivers of churn.
* Provide recommendations to reduce customer attrition.

## Data Analysis Process
1. **Data Preparation & Checking:** Converted raw data into tabular formats, checked for duplicates, and created calculated columns using nested IF statements (e.g., converting "Yes/No" churn labels into binary 1/0 for mathematical analysis).
2. **Exploratory Data Analysis (EDA):** Used PivotTables to investigate churn across various dimensions, including demographics, contract types, data consumption, and international plans.
3. **Data Visualization:** Built dynamic visuals including combo charts, stacked column charts, and categorical matrixes to highlight key trends.
4. **Dashboard Creation:** Consolidated key performance indicators (KPIs) and visual insights into a cohesive "Overview" dashboard sheet for easy stakeholder communication.

## Key Insights
* **Overall Churn:** The baseline churn rate for Databel is 26.86%. This represents 1,796 churned customers out of 6,687 total customers.
* **Competitor Impact:** The most common reasons for customers leaving are related to competitors offering better devices and better offers.
* **Demographics:** While making up a smaller portion of the base, customers classified as senior citizens have a churn rate of almost 40%.
* **Contract Types:** Customers on Month-to-Month contracts exhibit the highest churn rates.
* **Data Plans:** Customers on an unlimited data plan generally churn more often, particularly those who are paying for the unlimited plan but consuming less than 5 GB of data.
