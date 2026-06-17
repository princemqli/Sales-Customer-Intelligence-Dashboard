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

## Overview

The Sales Performance Analysis Dashboard is an interactive Power BI solution developed to analyze sales performance, customer behavior, product performance, and regional trends across India.

The dashboard transforms raw business data into meaningful insights using Power Query, DAX calculations, and a Star Schema data model. It enables users to monitor KPIs, identify sales trends, evaluate customer segments, analyze regional performance, and perform detailed analysis through drillthrough functionality.

---

## Objectives

- Monitor overall sales and profitability
- Analyze customer purchasing behavior
- Identify top-performing products
- Evaluate regional sales performance
- Track YTD, YOY, and MOM growth
- Support data-driven decision making


---

## Dashboard Pages

### 1. Executive Overview
- Total Sales
- Total Profit
- Customer Count
- Sales Trend
- Category Analysis

### 2. Sales Analysis
- YTD Sales
- YOY Growth
- MOM Growth
- Brand Analysis
- Product Analysis

### 3. Customer Intelligence
- Customer Segmentation
- Top Customers
- Customer Distribution
- State Analysis

### 4. Regional Performance
- India Sales Map
- State Wise Sales
- State Wise Profit
- State Wise Returns

### 5. Drillthrough Details
- Customer Level Analysis
- Sales Trend
- Product Details
- Purchase History


---

## Data Model
<img width="1710" height="1107" alt="Data Modeling" src="https://github.com/user-attachments/assets/d7d21c4d-0a18-4c8e-9082-86f957579547" />


The project follows a Star Schema data model to ensure efficient reporting and analysis.

### Fact Tables
- Sales_Fact
- Returns_Fact

### Dimension Tables
- Customer_Dim
- Product_Dim
- Region_Dim
- Date_Dim

### Relationships
- Date_Dim → Sales_Fact
- Date_Dim → Returns_Fact
- Customer_Dim → Sales_Fact
- Product_Dim → Sales_Fact
- Region_Dim → Sales_Fact

---

## Power Query Transformations
<img width="1710" height="1107" alt="Customer_Dim" src="https://github.com/user-attachments/assets/3ed1dc88-53fc-4a82-b712-6a938951e255" />
<img width="1710" height="1107" alt="Date_Dim" src="https://github.com/user-attachments/assets/56b4dfb8-00fd-46de-945f-01a9801a9c5d" />
<img width="1710" height="1107" alt="Product_Dim" src="https://github.com/user-attachments/assets/1cd9dd08-9db6-4b89-8578-1a222a204ff4" />
<img width="1710" height="1107" alt="Region_Dim" src="https://github.com/user-attachments/assets/bad4e7b2-09c3-4949-ad3f-c963bfb45758" />
<img width="1710" height="1107" alt="Return_Fact" src="https://github.com/user-attachments/assets/708a6bad-8be2-466f-932c-d2943038ed1f" />
<img width="1710" height="1107" alt="Sales_Fact" src="https://github.com/user-attachments/assets/219c4d72-c69b-4b64-b714-0b6071d540b5" />






The following data transformation steps were performed in Power Query:

### Date_Dim
- Created YearMonth column
- Extracted Month Name
- Verified Date data types

### Customer_Dim
- Created Customer Full Name
- Created Customer Location

### Product_Dim
- Created Price Category
- Created Product Label

### Sales_Fact
- Calculated Profit Margin %
- Created Profit Category

### Returns_Fact
- Created Return Status

These transformations improved data quality, consistency, and reporting performance.

---

## DAX Measures
<img width="488" height="909" alt="Screenshot 2026-06-17 at 11 22 30 AM" src="https://github.com/user-attachments/assets/b538e5b1-8112-485e-9976-418ee285ffac" />
<img width="454" height="944" alt="Screenshot 2026-06-17 at 11 23 54 AM" src="https://github.com/user-attachments/assets/3f21aeff-fd60-44b7-8e5b-2fd4ba100a65" />



### Basic Measures
- Total Sales
- Total Profit
- Total Quantity
- Total Returns
- Customer Count
- Average Order Value
- Profit Margin %

### Time Intelligence Measures
- YTD Sales
- Previous Year Sales
- YOY Growth %
- Previous Month Sales
- MOM Growth %

### DAX Functions Used
- CALCULATE
- FILTER
- ALL
- SUMX
- COUNTX
- AVERAGEX
- SWITCH
- RELATED
- TOTALYTD
- SAMEPERIODLASTYEAR
- PREVIOUSMONTH

## Business Insights

- Maharashtra, Gujarat, and Delhi generated the highest sales compared to other states.

- A few products contributed a large share of overall revenue, making them the key drivers of business performance.

- Consumer customers generated more sales compared to other customer segments.

- Sales performance was not the same across all regions, showing opportunities for growth in underperforming areas.

- Monthly sales trends helped identify peak and low-performing periods during the year.

- Some product categories consistently performed better than others in terms of both sales and profit.

- Customer analysis helped identify top customers based on revenue contribution.

- Regional analysis highlighted states that delivered strong sales but lower profit margins.

- YTD, YOY, and MOM analysis provided a clear view of business growth and performance changes over time.

- The dashboard makes it easier to track KPIs and support business decisions using data rather than assumptions.





