📊 Vendor Performance Data Analytics Project

An end-to-end data analytics project that simulates a real-world retail/wholesale business scenario. This project leverages SQL, Python, and Power BI to analyze vendor performance, optimize inventory, and generate actionable business insights.

🚀 Project Overview

This project is designed to mirror industry-level analytics workflows, including:

Data Engineering (ETL Pipelines)
Exploratory Data Analysis (EDA)
Statistical Analysis & Hypothesis Testing
Business Intelligence Dashboarding

The goal is to help businesses make data-driven decisions related to vendors, pricing, and inventory management.

🎯 Business Objectives
🔍 Identify underperforming brands (low sales, high margin)
🏆 Find top-performing vendors contributing maximum revenue
📦 Analyze bulk purchase impact on unit cost
🔄 Measure inventory turnover to reduce holding costs
💰 Detect unsold capital locked in inventory
🏗️ Tech Stack
Layer	Tools Used
Data Storage	SQLite
Data Processing	Python (Pandas, NumPy)
Data Visualization	Power BI
Query Optimization	SQL (CTEs, Joins)
Analysis	Jupyter Notebook
🔄 Project Workflow
1. Data Engineering (ETL Pipeline)
Imported raw CSV files into SQLite database
Built automated Python scripts for:
Data extraction
Data transformation
Data loading
Implemented logging system for tracking execution
Optimized large datasets (~10M+ records) using SQL (CTEs & joins)
2. Exploratory Data Analysis (EDA)
Data cleaning:
Handled missing values
Removed inconsistencies in vendor names
Feature engineering:
Gross Profit = Sales - Purchase
Profit Margin (%)
Stock Turnover Ratio
Correlation analysis using heatmaps
3. Advanced Analytics
📌 Hypothesis Testing
Performed T-test to compare profit margins between vendor groups
Verified statistically significant differences
📌 Confidence Intervals
Calculated 95% confidence intervals for profit margins
📌 Bulk Purchase Analysis
Categorized orders into:
Small
Medium
Large
Found ~72% reduction in unit cost for bulk purchases
4. Power BI Dashboard

Key dashboard features:

📊 KPI Cards:
Total Sales: $441M
Total Purchase: $307M
Gross Profit: $134M
Profit Margin: 38.72%
Unsold Capital: $2.71M
🍩 Donut Chart:
Vendor contribution to total purchases
📈 Bar Charts:
Top vendors by sales
Top products by revenue
📉 Scatter Plot:
Identifies low-performing brands
⚠️ Risk Indicators:
Vendor dependency
Slow-moving inventory

📷 Dashboard Preview
📊 Key Insights
Top 10 vendors contribute ~65% of total purchases
Several brands show high margin but low sales → pricing issue
Bulk purchasing significantly reduces unit costs
$2.7M capital is stuck in slow-moving inventory
💡 Business Recommendations
📉 Price Optimization:
Reduce prices for high-margin, low-sales brands
🤝 Vendor Diversification:
Reduce dependency on top vendors
🎯 Targeted Marketing:
Promote underperforming brands
🧹 Inventory Clearance:
Launch discount campaigns for slow-moving products.
