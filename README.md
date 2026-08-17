# Sales and Product performance Analysis: Identifying Key Drivers of Sales, Profitability and Growth
## [🌐 Portfolio](https://www.linkedin.com/in/alarape-abdulazeez) [🔗 Read Full Project On Medium](https://medium.com/@alarapeolayiwola/from-data-to-decisions-analyzing-sales-revenue-profitability-growth-d5d018f86aca)
# 📝 Project Overview
A multinational retail company operating across eight countries and three continent sells electronics, gadgets and appliances. Despite strong sales activity across its markets, management lacked clear visibility into the key factors driving revenue, profitability, and product performance.
This project analyzes 62 months of transaction data to evaluate sales trends, product performance, profitability, and regional performance. The analysis focuses on identifying the factors influencing revenue growth and determining whether differences in performance are driven by product mix, profitability, or market concentration.

# Objective
The main objective of this analysis was to identify the company’s key product-level revenue and sales drivers.

The analysis focused on four major areas:
* Top 5 products by units sold
* Revenue by product category
* Relationship between units sold and revenue
* Relationship between units sold and revenue

These analyses were selected because they provide both a volume perspective and a financial perspective on product performance.
# 🧰 Tool
| Tool| Purpose|
|-----|--------|
| Power Query	| Cleaning and Transformation |
| Power Pivot	| Data Modelling and Visualization |
# Dataset Description
The dataset was obtained from Kaggle. It follows a star schema with one fact tables and three dimension tables.

| Tables|	Description| Rows|
|-------|------------|-----|
|fact_sales	|contains sales record across various territories	|62,884
|Dim_customer|	contains customers details	|15,266
|Dim_product|	Contains information about products offered by the business	|2517
|Dim_store| contains information about each stores location and its operational characteristics in the business.|67

# Data Workflow
Data Collection ↓ Data Cleaning ↓ Data Modeling ↓ Data Analysis ↓ Dashboard Development ↓ Insights & Recommendations

1. Data Collection: The dataset was obtained from Kaggle.
2. Data Cleaning: Ensure data quality, Checked for duplicated records and Promoted Headers
3. Data Transformation: Added Price and cost column into the sales table, calculated the total price and total cost in order to obtain total profit and calculate profit Margin.
4. Data Modeling: Created relationships between tables and designed a star schema for reporting.
5. Data Analysis: Created measures and explored sales, profitability, and Product performance trends.
6. Dashboard Development: Built a two page interactive Excel dashboards to visualize key metrics.
7. Reporting: Documented key findings and provided actionable recommendations.
# Data Model
<img width="736" height="356" alt="Screenshot 2026-08-16 140037" src="https://github.com/user-attachments/assets/4a7123b7-861b-4e23-b9b1-0ffd0acc60ad" />

# 📌 Key Insights
## 1. Executive Summary
<img width="750" height="423" alt="Screenshot 2026-08-10 071741" src="https://github.com/user-attachments/assets/3bc95d24-495f-4b54-bc45-f85c8f43139f" />

*  Sales grew strongly from 2016 to 2019, increasing by 6.86%, 72.32%, and 42.81% respectively. However, sales declined by 49.11% in 2020, reversing the previous growth trend. This significant decline highlights the need to investigate the factors affecting performance and develop strategies to improve sales resilience.
* Revenue performance was concentrated in a few key markets, with the United States generating the highest country-level revenue. This indicates that business growth is largely dependent on established markets, creating potential exposure if performance in these countries declines.
## 2. Product Performance
<img width="822" height="398" alt="Screenshot 2026-08-12 185334" src="https://github.com/user-attachments/assets/11ed6568-c1a6-418d-a6d2-3edd37dc10c2" />

* The report indicates that the business maintained an overall profit margin of approximately 42% during the analysis period. Computers were the strongest contributor to revenue and profit, accounting for approximately 35%, while desktop products also dominated the top-performing products by quantity sold and revenue.
* Several high revenue products were not among the most profitable products.
# 🎗️ Recommendations
| Priority | Recommendation	| Business Impact	| Suggested Owner|
|----------|----------------|-----------------|----------------|
|High	|Prioritize high-performing products, especially Computers|	Improves profitability and margin performance	|Product Manager/Finance Team
|High	|Review high-volume, low-revenue products|	Improves profitability and ensures strong sales volumes translate into better revenue and margins.|Pricing Team/Commercial Team
|Medium	|Expand marketing efforts into lower performing countries|	Reduce market concentration and drive growth|Sales & Marketing Team
|Medium	|Reassess under-performing product|	Reduce cost and improves product portfolio management	|Product Team/Finance Team

# Author
Alarape Abdulazeez - Data Analyst

# 🔗 Connect With Me
* [LinkedIn](http://linkedin.com/in/alarape-abdulazeez)
* [Email](alarapeolayiwola@gmail.com)
* [Medium](https://medium.com/@alarapeolayiwola)
