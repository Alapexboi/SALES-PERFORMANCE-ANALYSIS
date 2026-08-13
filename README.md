# Sales and Product performance Analysis: Identifying Key Drivers of Sales, Profitability and Growth
🌐 Portfolio 🔗 Read Full Project On Medium
🌼 Project Overview
A company operating across six countries and ten regions sells bikes, clothing, and accessories. Despite strong sales activity across its markets, management lacked clear visibility into factors driving revenue and profitability. While sales volume appeared to increase over time, revenue growth did not always rise at the same rate, making it difficult to identify the factors influencing business performance. This project analyzes 30 months of transaction data to evaluate sales trends, product profitability, customer behavior, and regional performance. The analysis aims to determine whether gaps in revenue performance are linked to product mix, profitability, customer purchasing patterns, or market concentration. The findings revealed a growing number of low-margin products within the portfolio, a heavy reliance on the bike category for revenue generation, and revenue concentration in a small number of key markets.

Objective
Determine whether sales performance increased throughout the analysis period.
Identify the key products, categories, customers, and markets driving revenue and profitability.
Evaluate product profitability by identifying products that fall below the target margin and those that contribute most to overall profit.
Analyze customer and regional performance to understand their impact on business growth.
Provide data-driven recommendations to improve profitability and support business decision-making.
🧰 Tool
Tool	Purpose
Power Query	Cleaning and Transformation
Power BI	Data Modelling and Visualization
Dataset Description
The dataset was obtained from Kaggle. It follows a star schema with one fact tables and six dimension tables.

Tables	Description	Rows
fact_sales	contains sales record across various territories	56,046
Dim_customers	contains customers details	18,148
Dim_products	Contains information about products offered by the business	293
Dim_product category	records of available product category	4
Dim_Product subcategory	Information about various subcategory	37
Dim_terriotry	Contains territory information	10
Dim_date	Date covering Jan 1st 2015 to Dec 31st 2017	1096
Data Workflow
Data Collection ↓ Data Cleaning ↓ Data Modeling ↓ Data Analysis ↓ Dashboard Development ↓ Insights & Recommendations

Data Collection: The dataset was obtained from Kaggle.
Data Cleaning: Ensure data quality, Checked for duplicated records, Replaced M with "Male" and F with "Female", and Promoted Headers
Data Transformation: Concatenate the first name and last name to get the full name, Added Price and cost column into the sales table, calculated the total price and total cost in order to obtain total profit and calculate profit Margin.
Data Modeling: Created relationships between tables and designed a star schema for reporting.
Data Analysis: Created DAX measures and explored sales, profitability, and customer trends.
Dashboard Development: Built a three page interactive Power BI dashboards to visualize key metrics.
Reporting: Documented key findings and provided actionable recommendations.
Data Model
This project presents a two-page Sales Analytics dashboard built in Excel for Identifying Key Revenue Drivers in a Global Electronics Retailer. The analysis focuses on sales performance, revenue trends, and product performance, turning retail sales data into Actionable Business Insights to support data-driven decision making and business growth.
