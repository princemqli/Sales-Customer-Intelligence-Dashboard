# 1. Executive Overview Dashboard
<img width="1379" height="796" alt="Executive Overview Dashboard" src="https://github.com/user-attachments/assets/dcd2d552-866c-4a75-b8b9-3d5291fc1256" />

# 2. Sales Analysis Dashboard
<img width="1380" height="801" alt="Sales Analysis Dashboard" src="https://github.com/user-attachments/assets/fdfcec38-b725-49e8-a5d2-f786c2a1194e" />

# 3. Customer Intelligence Dashboard
<img width="1381" height="835" alt="Cutomer Intelligence Dashborad" src="https://github.com/user-attachments/assets/479f1c8a-fcff-4db5-85b0-be01e58c5636" />

# 4. Regional Perfomance Dashboard
<img width="1376" height="801" alt="Regional Perfromance Dashboard" src="https://github.com/user-attachments/assets/a073a150-c0f0-4a73-b263-824a6ddfb073" />

# 5.DrillThrough Details Dashboard
<img width="1377" height="802" alt="DrillThrough Details Dashboard" src="https://github.com/user-attachments/assets/915ba3ad-6a00-4b75-8251-b8814f06354b" />

# Sales Performance Analysis Dashboard

# Project Overview

This Power BI project analyzes sales performance, customer behavior, product performance, and regional trends across India. The dashboard is designed using a Star Schema model and includes interactive reports, KPIs, drillthrough functionality, and geographical analysis to support business decision-making.

Tools Used
Power BI Desktop
Power Query
DAX (Data Analysis Expressions)
Data Modeling
Drillthrough
Maps Visualization
Data Model

The project follows a Star Schema architecture.

Fact Tables
Sales_Fact
Returns_Fact
Dimension Tables
Customer_Dim
Product_Dim
Region_Dim
Date_Dim
Power Query Transformations

The following transformations were performed in Power Query:

Date_Dim
YearMonth Column
Month Name Column
Customer_Dim
Customer Full Name
Customer Location
Product_Dim
Price Category
Product Label
Sales_Fact
Profit Margin %
Profit Category
Returns_Fact
Return Status

These transformations improve data quality and reporting performance.

DAX Measures
Basic Measures
Total Sales
Total Profit
Total Quantity
Total Returns
Customer Count
Average Order Value
Profit Margin %
Advanced Measures
YTD Sales
Previous Year Sales
YOY Growth %
Previous Month Sales
MOM Growth %
High Profit Sales
Overall Sales
DAX Functions Used
CALCULATE
FILTER
ALL
SUMX
COUNTX
AVERAGEX
SWITCH
RELATED
TOTALYTD
SAMEPERIODLASTYEAR
PREVIOUSMONTH
Dashboard Pages
1. Executive Overview Dashboard
Purpose

Provides a high-level summary of business performance.

KPIs
Total Sales
Total Profit
Customer Count
Total Returns
Profit Margin %
Average Order Value
Visuals
Sales Trend Line Chart
Sales by Category Donut Chart
State Wise Sales Bar Chart
Top Products Chart
2. Sales Analysis Dashboard
Purpose

Analyzes product and sales performance over time.

KPIs
YTD Sales
YOY Growth %
MOM Growth %
Average Order Value
Visuals
Monthly Sales Trend
Sales by Brand
Category Wise Sales
Top 10 Products
Forecast Analysis
3. Customer Intelligence Dashboard
Purpose

Provides customer segmentation and customer behavior insights.

KPIs
Customer Count
Total Sales
Total Profit
Average Order Value
Visuals
Sales by Segment
Profit by Segment
Top 10 Customers
Customers by State
Customer Distribution Map
4. Regional Performance Dashboard
Purpose

Analyzes sales and profitability across different regions of India.

KPIs
Total Sales
Total Profit
Total Returns
Profit Margin %
Visuals
India Sales Map
State Wise Sales
State Wise Profit
State Wise Returns
5. Drillthrough Details Dashboard
Purpose

Provides detailed customer-level analysis.

Features
Drillthrough Navigation
Customer Purchase Details
Customer Sales Trend
Category Wise Sales
Segment Wise Sales
Visuals
KPI Cards
Detail Table
Line Chart
Donut Charts
Key Insights
Identified top-performing products and categories.
Analyzed customer purchasing behavior.
Evaluated regional sales and profit performance.
Monitored business growth using YTD, YOY, and MOM metrics.
Enabled detailed customer-level analysis through drillthrough functionality.
Business Benefits
Improved sales monitoring.
Better customer segmentation.
Regional performance tracking.
Data-driven decision making.
Interactive and user-friendly reporting experience.
Conclusion

This Sales Performance Analysis Dashboard provides a comprehensive view of sales, customers, products, and regional performance. By leveraging Power BI, Power Query, and DAX, the dashboard enables stakeholders to monitor KPIs, identify trends, and make informed business decisions through interactive and visually appealing reports.






