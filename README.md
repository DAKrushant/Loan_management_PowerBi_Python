# 📊 Loan Management Analytics Dashboard
By: Krushant Shah

A clean and professional Power BI dashboard designed to analyze loan portfolio performance, branch collections, DPD behaviour, and operational insights across multiple months.

## 📝 Project Overview

  - This dashboard helps stakeholders:
  - Track loan collection trends across branches
  - Analyze OD (Overdue) demand vs OD collection
  - Understand DPD patterns and loan risk segments
  - Identify high-performing and low-performing branches
  - Monitor joining, exit, and attrition activities
  - Review loan product distribution and principal balance
  - Gain a 360° analytical view of the loan management system

It provides a detailed single-view operational and financial analysis for decision-makers.


## 🧹 Data Preparation (Python + SQL)
### Python (Data Cleaning)

  - Removed incorrect and invalid rows
  - Cleaned and standardized text and numeric fields
  - Fixed inconsistent date formats
  - Merged multiple monthly datasets (May–Aug 2024)
  - Created derived fields (Month-Year, Risk Bucket, etc.)

## SQL (Data Modeling & Transformation)

  - Loaded cleaned datasets into MySQL
  - Created structured relational tables
  - Performed joins across portfolio, collections, and branch tables
  - Built aggregated SQL views for Power BI
  - Added DPD, OD, and Principal Balance calculations

## 📊 Power BI Dashboard Features
### Key KPIs

Average DPD
Total Closing Balance
Total Joining & Total Exit
Active Loans
Total Collection
Closed Loans

### Visuals Included
  - Monthly Joining, Exit & Transfer trends
  - Branch-wise Advanced vs Regular Collection
  - OD Collection vs OD Demand
  - Loan Amount by Branch
  - Overall Collection by Branch
  - Loan Status Distribution (Pie Chart)
  - Principal Balance by State (Donut Chart)

<img src="Dashboard Image/dashboard.png" width="500">

## 🔍 Insights Generated

  - Zalod branch shows highest loan amount and collections
  - Rishta loan type represents over 50% of total portfolio
  - Principal balance evenly distributed across major states
  - Average DPD is stable but indicates areas needing improvement
  - Collections achieved over 7 billion across months
  - Active loans exceed 2 million

## 📂 Datasets Used

  - Attrition_By_Branch_Data
  - Collection_May_2024
  - Collection_Jun_2024
  - Collection_Jul_2024
  - Collection_Aug_2024
  - Portfolio_Report_May_2024
  - Portfolio_Report_Jun_2024
  - Portfolio_Report_Jul_2024
  - Portfolio_Report_Aug_2024

## 🧩 Tools & Technologies

  - Python (Pandas, NumPy)
  - MySQL (Data Transformation)
  - Power BI (Dashboard & DAX)
  - Excel / CSV (Raw Data Sources)

## ✅ Conclusion

This Loan Management Analytics Dashboard delivers actionable insights into loan performance, risk behaviour, branch efficiency, and customer trends.
The end-to-end pipeline (Python → SQL → Power BI) ensures data accuracy, scalability, and professional reporting.
