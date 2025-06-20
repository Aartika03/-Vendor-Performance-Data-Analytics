# -Vendor-Performance-Data-Analytics

This project presents an end-to-end data analytics pipeline for evaluating vendor performance using real-world purchase and sales data. It involves data ingestion, data transformation, statistical analysis, and Power BI dashboard visualization to generate actionable insights.

**Objective**
To evaluate and visualize vendor performance metrics such as:
Purchase & sales contribution
Profit margins
Stock turnover ratios
Freight costs
Confidence intervals for performance
Vendor segmentation (Top vs Low)

**Tools & Technologies**
Python (Pandas, NumPy, Seaborn, Matplotlib, SQLite)
Power BI for interactive dashboards
Jupyter Notebook for exploratory analysis
SQL for data querying
Logging for traceability
Git for version control

**Dataset (Download)**
Due to GitHub file size limits, the full dataset is hosted externally:
Link to download: https://drive.google.com/drive/folders/1Yx0sGz271qLV7KoZ2jCACF-lWC7HZ9r3?usp=drive_link

**Pipeline Stages**
Data Ingestion
Load data from multiple CSV/SQL sources
Store in SQLite database
Data Cleaning & Transformation
Null handling, data type correction
Feature engineering (e.g., GrossProfit, ProfitMargin)
Analytics & Statistics
Vendor segmentation (Top vs Low)
Confidence interval computation
Pareto charts, histograms
Power BI Dashboard
Interactive vendor insights
Filters for brands, time period, and purchase/sales categories

