#  Bank Customer Analysis – Interactive Excel Dashboard

##  Project Overview

The **Bank Customer Analysis** project is an end-to-end data analysis project developed using Microsoft Excel to explore customer demographics, account balances, loan information, contact history, and subscription outcomes.

The project goes beyond traditional chart-based reporting by providing an **interactive, Power BI-style Excel dashboard** that enables users to explore customer data, monitor key performance indicators (KPIs), and understand business trends through visual summaries.

The objective is to transform raw banking data into meaningful insights that can support customer segmentation, marketing analysis, and data-driven business decisions.

##  Business Objective

The primary objective is to understand the bank's customer profile, identify important customer segments, analyze account balance patterns, and explore factors associated with subscription outcomes.

The analysis focuses on answering questions such as:

- Which job categories contribute the largest number of customers?
- Which education groups have higher average account balances?
- How do customer demographics relate to banking and loan characteristics?
- How does call duration vary across months?
- How do subscription outcomes differ across customer segments?

##  Tools & Technologies

- **Microsoft Excel** – Data cleaning, analysis, formulas, pivot tables, charts, and dashboard development.
- **Excel Formulas** – COUNT, AVERAGE, MAX, COUNTBLANK, and VLOOKUP.
- **Pivot Tables** – Customer segmentation and summary analysis.
- **Interactive Dashboard Features** – User-driven data exploration through dashboard filters and controls.
- **Data Visualization** – Charts and KPI cards for clear presentation of findings.

##  Dataset Overview

The project uses a bank marketing dataset containing approximately **45,211 customer records** and 17 columns.

The dataset includes:

- **Customer Demographics:** Age, job, marital status, and education.
- **Financial Information:** Account balance and credit default status.
- **Loan Information:** Housing loan and personal loan status.
- **Campaign Details:** Contact type, contact day, contact month, call duration, and number of contacts.
- **Previous Campaign History:** Previous contact days, previous contact count, and previous campaign outcome.
- **Subscription Outcome:** Whether the customer subscribed to the offered banking product.

##  Data Cleaning & Preparation

The following data preparation steps were performed:

- Reviewed the raw dataset and created a working copy.
- Renamed column headers to meaningful names.
- Standardized column naming and formatting for better readability.
- Identified a missing value in the Education column using COUNTBLANK.
- Used VLOOKUP to retrieve the corresponding education value from the available reference data.
- Prepared the cleaned dataset for analysis and dashboard reporting.

##  Key Performance Indicators (KPIs)

The dashboard includes KPI cards to provide a quick overview of the dataset:

1. **Total Customers:** 45,211
2. **Average Account Balance:** Approximately 1,362.27
3. **Maximum Account Balance:** 102,127
4. **Average Call Duration:** Approximately 258.16
5. **Total Subscriptions:** A KPI included in the dashboard; the final value should reflect only customers with a positive subscription outcome.

*Note: The average balance and maximum balance are expressed in the dataset's account-balance units. Call duration is expressed in the dataset's duration units, typically seconds.*

##  Dashboard Visualizations

The workbook includes charts and pivot-table summaries for customer and campaign analysis, including:

- **Customers by Job:** Compares customer counts across professions.
- **Average Balance by Education:** Examines average account balances across education groups.
- **Subscriptions by Marital Status:** Compares subscription outcomes by marital status.
- **Average Call Duration by Month:** Explores differences in average call duration across campaign months.

The dashboard combines visualizations with KPI cards and interactive controls, providing a more engaging experience than a static collection of charts.

##  Business Insights

The current analysis highlights the following findings:

- **Customer Segmentation:** Blue-collar customers form the largest job category, with 9,732 records.
- **Education and Account Balance:** Customers with tertiary education have an average account balance of approximately 1,758.42 in the current analysis.
- **Campaign Analysis:** Comparing call duration across months can help identify variations in campaign activity.
- **Subscription Analysis:** Segmenting subscription outcomes by marital status can help explore differences between customer groups.

These findings describe patterns in the dataset and should not be interpreted as proof of causation.

##  Workbook Structure

The Excel workbook is organized into the following sections:

- **Raw Data:** Original dataset.
- **Copy of Raw Data:** Reference copy used during preparation.
- **Main Data:** Working dataset for analysis.
- **KPI (Formula Based):** KPI calculations using Excel formulas.
- **KPI & Pivot Tables:** Pivot-table summaries and business questions.
- **Charts:** Individual visualizations.
- **Dashboard:** Consolidated KPI cards and interactive reporting.
- **Business Insight Questions:** Business questions and documented findings.
- **Notes:** Documentation of data cleaning and analytical steps.

##  Key Skills Demonstrated

- Data cleaning and preparation
- Excel formulas and lookup functions
- Pivot-table analysis
- KPI creation and reporting
- Customer segmentation
- Data visualization and dashboard design
- Interactive dashboard development
- Business question formulation
- Translating data into actionable insights

## Conclusion

This project demonstrates how Microsoft Excel can be used as a business intelligence tool to clean data, analyze customer behavior, calculate KPIs, and build an interactive dashboard.

By combining data preparation, analytical summaries, visualizations, and interactive reporting, the project showcases practical data analytics skills relevant to Data Analyst, MIS Analyst, and Business Intelligence roles.

**Project Focus:** Turning raw banking data into an interactive, insight-driven dashboard for better customer and campaign analysis.
