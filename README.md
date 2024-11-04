# Data Analytics Capstone: LITA Data Analytics Program

Welcome to my capstone project repository for the **Ladies in Tech Africa (LITA) Data Analytics Program**. This repository contains two comprehensive projects that demonstrate my skills in data analysis, SQL querying, Excel analysis, and Power BI dashboard creation.

## Project List

1. **[Sales Performance Analysis for a Retail Store](https://docs.google.com/spreadsheets/d/1nBpXfXZp7FbpqnfdgArWI661lFPYcjCM/edit?usp=drive_link&ouid=107432719510832986174&rtpof=true&sd=true)**: Analysis of sales performance data to provide insights into top-selling products, regional sales trends, and more.
2. **[Customer Segmentation for a Subscription Service](https://docs.google.com/spreadsheets/d/1O4IjF1rU5grY1X9E4lZ1L2dKhNisbe3S/edit?usp=drive_link&ouid=107432719510832986174&rtpof=true&sd=true)**: Analysis of customer data to segment and understand customer behavior, subscription types, and cancellation trends.

Each project folder contains:
- **Data**: The datasets used for analysis.
- **SQL Queries**: SQL scripts for data extraction and insight generation.
- **Excel Analysis**: Excel files with data manipulations, calculations, and initial reports.
- **Power BI**: Interactive Power BI dashboards visualizing key insights.

## Tools Used
- **Microsoft Excel**: Data exploration, pivot tables, formula-based calculations.
- **SQL**: Database querying, filtering, aggregation, and data transformation.
- **Power BI**: Interactive data visualization and reporting.

Explore each project folder for detailed documentation, SQL scripts, and Power BI dashboards.

# Project 1: Sales Performance Analysis for a Retail Store

## Summary
In this project, I analyzed the sales performance of a retail store to uncover insights about top-selling products, regional performance, and monthly trends. The goal was to create a Power BI dashboard that highlights these findings.

### Data Overview
- **Dataset**: The `sales_data.csv` file contains information on product sales, regions, and dates.
- **Source**: Data was sourced from a sample sales dataset for training purposes.

### Analysis Workflow

1. **Excel Analysis**
   - Used pivot tables to explore sales data by product, region, and month.
   - Calculated key metrics such as average sales per product and total revenue by region.
   - Created additional reports for insights.

2. **SQL Analysis**
   - Loaded data into SQL Server and ran queries for:
     - Total sales by product category
     - Number of transactions per region
     - Highest-selling product by total sales value
     - Monthly sales totals for the current year
     - Top 5 customers by total purchase amount
     - Percentage of total sales by region
     - Products with no sales in the last quarter

   See `[SQL_Queries/Sales_Performance_Queries.sql](https://drive.google.com/file/d/1av7Sx6mV0Ofds3ZmZfIZ320nsextDQYz/view?usp=drive_link), [https://drive.google.com/file/d/1ZRA_X8eTMWCJJ_-9RNt3hKRKKfulvEmR/view?usp=drive_link)` for the full list of queries.

3. **Power BI Dashboard**
   - Built an interactive dashboard featuring:
     - Sales overview with monthly trends
     - Top-performing products
     - Regional performance breakdowns
   - Dashboard file: `PowerBI/Sales_Performance_Dashboard.pbix`

### Key Insights
- **Top-selling products** were identified across all regions.
- **Regional performance** analysis revealed areas with the highest sales.
- **Monthly sales trends** showed peak sales periods, which can inform future marketing and inventory strategies.

---

### Files in This Folder
- `Data/sales_data.csv`: Sales data for analysis.
- `SQL_Queries/Sales_Performance_Queries.sql`: SQL scripts to extract insights.
- `Excel_Analysis/Sales_Analysis.xlsx`: Excel analysis with pivot tables and metrics.
- `PowerBI/Sales_Performance_Dashboard.pbix`: Power BI dashboard visualizing key findings.

# Project 2: Customer Segmentation for a Subscription Service

## Summary
This project involved analyzing customer data for a subscription service to identify segments and trends. The goal was to create a Power BI dashboard to visualize customer behaviors, subscription types, and trends in cancellations and renewals.

### Data Overview
- **Dataset**: The `customer_data.csv` file includes information on customers, subscription types, and subscription durations.
- **Source**: Data was sourced from a sample dataset provided for training purposes.

### Analysis Workflow

1. **Excel Analysis**
   - Used pivot tables to analyze customer data and find subscription patterns.
   - Calculated average subscription duration and identified popular subscription types.
   - Generated additional reports for insights.

2. **SQL Analysis**
   - Loaded data into SQL Server and ran queries for:
     - Total number of customers per region
     - Most popular subscription type by customer count
     - Customers who canceled within 6 months
     - Average subscription duration
     - Customers with subscriptions longer than 12 months
     - Total revenue by subscription type
     - Top 3 regions by subscription cancellations
     - Total number of active and canceled subscriptions

   See `SQL_Queries/Customer_Segmentation_Queries.sql` for the full list of queries.

3. **Power BI Dashboard**
   - Built an interactive dashboard with visualizations for:
     - Customer segments
     - Subscription trends, including cancellations
     - Key insights with slicers for interactive analysis
   - Dashboard file: `PowerBI/Customer_Segmentation_Dashboard.pbix`

### Key Insights
- **Subscription type popularity** highlighted key segments for targeted marketing.
- **Cancellation trends** identified regions and customer types with high cancellation rates.
- **Renewal analysis** provided insights into average subscription durations and customer retention.

---

### Files in This Folder
- `Data/customer_data.csv`: Customer data for analysis.
- `SQL_Queries/Customer_Segmentation_Queries.sql`: SQL scripts to extract insights.
- `Excel_Analysis/Customer_Segmentation_Analysis.xlsx`: Excel analysis with pivot tables and calculations.
- `PowerBI/Customer_Segmentation_Dashboard.pbix`: Power BI dashboard visualizing key insights.

