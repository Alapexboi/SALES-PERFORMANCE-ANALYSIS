# Sales and Product performance Analysis: Identifying Key Drivers of Sales, Profitability and Growth
## [🌐 Portfolio](https://www.linkedin.com/in/alarape-abdulazeez) [🔗 Read Full Project On Medium](https://medium.com/@alarapeolayiwola/from-data-to-decisions-analyzing-sales-revenue-profitability-growth-d5d018f86aca)
# 🌼 Project Overview
A multinational retail company operating across eight countries and three continent sells electronics, gadgets and appliances. Despite strong sales activity across its markets, management lacked clear visibility into the key factors driving revenue, profitability, and product performance.
This project analyzes 62 months of transaction data to evaluate sales trends, product performance, profitability, and regional performance. The analysis focuses on identifying the factors influencing revenue growth and determining whether differences in performance are driven by product mix, profitability, or market concentration.

## Objective
Determine whether sales performance increased throughout the analysis period.
Identify the key products, categories, and markets driving revenue and profitability.
Evaluate product profitability by identifying products that fall below the target margin and those that contribute most to overall profit.
Provide data-driven recommendations to improve profitability and support business decision-making.
## 🧰 Tool
| Tool| Purpose|
|-----|--------|
| Power Query	| Cleaning and Transformation |
| Power Pivot	| Data Modelling and Visualization |
## Dataset Description
The dataset was obtained from Kaggle. It follows a star schema with one fact tables and three dimension tables.

| Tables|	Description| Rows|
|-------|------------|-----|
|fact_sales	|contains sales record across various territories	|62,884
|Dim_customer|	contains customers details	|15,266
|Dim_product|	Contains information about products offered by the business	|2517
|Dim_store| contains information about each stores location and its operational characteristics in the business.|67

## Data Workflow
Data Collection ↓ Data Cleaning ↓ Data Modeling ↓ Data Analysis ↓ Dashboard Development ↓ Insights & Recommendations

1. Data Collection: The dataset was obtained from Kaggle.
2. Data Cleaning: Ensure data quality, Checked for duplicated records and Promoted Headers
3. Data Transformation: Added Price and cost column into the sales table, calculated the total price and total cost in order to obtain total profit and calculate profit Margin.
4. Data Modeling: Created relationships between tables and designed a star schema for reporting.
5. Data Analysis: Created measures and explored sales, profitability, and Product performance trends.
6. Dashboard Development: Built a two page interactive Excel dashboards to visualize key metrics.
7. Reporting: Documented key findings and provided actionable recommendations.
## Data Model
This project presents a two-page Sales Analytics dashboard built in Excel for Identifying Key Revenue Drivers in a Global Electronics Retailer. The analysis focuses on sales performance, revenue trends, and product performance, turning retail sales data into Actionable Business Insights to support data-driven decision making and business growth.
