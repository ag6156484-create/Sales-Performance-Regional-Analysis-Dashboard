# Sales-Performance-Regional-Analysis-Dashboard
End to end sales &amp; profitability Analysis: Automated data cleaning, lookup integrations , calculated metrics , and interactive dashboards to uncover regional revenue trends and profit margins.

📌 Project Overview
This project presents an End-to-End Sales Performance & Regional Analysis built in Microsoft Excel to track business metrics, customer purchasing patterns, and regional profitability.
Starting from raw tabular data, I performed data cleaning, integrated multiple tables using dynamic lookup functions, and engineered key financial features (Gross Profit and Profit Margin %). The transformed data was modeled into dynamic, interactive dashboards to highlight actionable strategic insights—such as identifying a 12% revenue drop in 2018 and evaluating product-level profit performance across regions

Business Questions:
1. What is the average gross profit margin across the entire product catalog?
2. How has the revenue trended year-over-year (YOY) from 2014 to 2018?
3. Which specific period experienced a sales downtum , and what was the percentage decline in performance ?
4. Which geographical region contributes the highest share to overall revenue?
5. Which top performing states drive the bulk of regional sales & profitability?
6. How do profit margin vary across different product SKUs and which products shows margin compression?


Data Preprocessing & Pipeline (Excel)
Data Cleaning: Cleaned raw data by identifying missing values, correcting data types, standardizing date formats, and eliminating duplicate records.

Data Integration (LOOKUP Functions): Used VLOOKUP / XLOOKUP to merge disparate dimension tables (Customer, Product, Regional details) into a central fact dataset.

Feature Engineering: Created calculated metrics to drive financial analysis:

Gross Profit: Calculated as [Total Sales / Revenue] - [Total Product Cost].

Profit Margin (%): Calculated as ([Gross Profit] / [Total Revenue]) * 100.

📈 Key Business Insights
Revenue Trend & 2018 Decline: Annual revenue was consistent (~$167M–$171M) between 2014 and 2017, but saw a sharp 12.05% drop in 2018 ($148.37M), indicating product-level drop-offs or operational bottlenecks.
Regional Drivers: The West region accounts for 36% of total revenue, followed by South (27%), Midwest (20%), and Northeast (17%). California and Illinois generated the highest sales volume.
Profitability & Product Margins: Product 1 contributes the highest gross profit ($10.23M) maintaining a strong 39% margin. Profit margins decline to ~34% on lower-performing SKUs like Product 180, signaling a potential cost-renegotiation need.
Customer Distribution: Profitability across key accounts remains well-distributed, mitigating revenue dependency on any single buyer.
