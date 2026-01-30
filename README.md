Project Overview
This project simulates a real-world business scenario where sales data is analyzed end-to-end to support commercial decision-making.
Using the Northwind database, the project covers:

Data extraction and aggregation using SQL Server
Advanced analysis using Python (customer segmentation and forecasting)
Data visualization using Power BI
The objective is to understand customer behavior, identify patterns, and estimate future sales trends.

Business Questions

  How are sales distributed over time?
  What types of customers exist based on purchasing behavior?
  Which factors influence sales performance?
  What are the expected sales trends for upcoming periods?

Tools & Technologies

  SQL Server (SSMS) – data extraction and transformation
  Python – Pandas, NumPy, scikit-learn, Matplotlib
  Power BI – dashboards and KPIs
  GitHub – project versioning and documentation

Project Workflow

  SQL – Data Preparation
  Joined operational tables (Orders, Order Details, Customers)
  Calculated business metrics:
  Total sales
  Order frequency
  Average ticket
  Aggregated data by customer and month
  
  Python – Advanced Analysis
  Customer clustering based on purchasing behavior
  Sales trend analysis
  Sales forecasting using historical data
  
  Power BI – Visualization
  Interactive dashboards
  KPIs and trends
  Customer segmentation insights
  Power BI – Visualization

Repository Structure
    northwind-sales-analysis/
    │
    ├── sql/
    │   └── sales_analysis.sql
    │
    ├── python/
    │   ├── data_extraction.ipynb
    │   ├── customer_clustering.ipynb
    │   └── sales_forecasting.ipynb
    │
    ├── bi/
    │   ├── powerbi_dashboard.pbix
    │   └── screenshots/
    │
    ├── data/
    │   └── sample_output.csv
    │
    └── README.md

Key Insights (to be updated)
Identified distinct customer segments based on sales behavior
Detected sales trends and seasonality patterns
Estimated future sales using time series forecasting

How to Use This Project

  Run the SQL scripts in SQL Server (SSMS)
  Load the extracted data into Python notebooks
  Review analytical results and visual outputs
  Open the Power BI dashboard for final insights

Notes

  This project focuses on analysis and decision support, not on production deployment.
  Power BI dashboards are provided as .pbix files and screenshots.
  Python notebooks are intended for analytical exploration.



