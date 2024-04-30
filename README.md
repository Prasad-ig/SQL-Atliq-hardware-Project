# SQL-Atliq-hardware-Project
# AtliQ Hardware Overview

**AtliQ Hardware :** stands as a prominent online retailer specializing in electronic products, operating through a variety of sales channels, including direct, distributor, and physical retail stores, with a robust online presence. Serving customers across the globe, AtliQ offers a diverse product catalog consisting of approximately 400 SKUs spanning over 10 categories, tailored to meet the needs of both personal and professional users. Accumulating a vast dataset of over 1 million sales records over 5 years, AtliQ aims to make strategic decisions to enhance the overall health of its global operations.

**Dataset Overview :**

The dataset includes two dimension tables for customer and product details, along with five fact tables containing information about actual sales quantity, product price, discounts, and forecasted sales quantities. The sales quantity and discount-related tables contain the largest volume of data, ranging from 1 to 2 million rows, while other tables vary from about 200 to 2000 rows.

# Project Tasks : 

**Gross Sales Analysis :** [SQL Gross sales analysis](https://github.com/MrinalBisht/SQL_AtliQ_Project/blob/main/SQL%20Project_gross%20sales.sql)
**Objective:** Develop a data table for a yearly sales report, presenting gross sales data (gross price * quantity sold) for a specific customer over a customizable period. Classify markets into "Gold" and "Silver" categories based on aggregated gross sales to identify top-performing products and markets within a specified timeframe.

**Tools Used:** MySQL for constructing data tables and a stored procedure for quick customization based on the interested market, product, or customer for a given period.
Market Share Analysis.
**Objective:** Analyze net sales by considering discounts given to customers based on royalty and product. Create SQL database views by joining multiple tables, including pre-invoice and post-invoice discounts, to generate interactive data tables. This data helps in understanding top-performing customers and products in terms of net sales.
**Tools Used:** SQL for creating database views and stored procedures for interactive data table generation. Data can be exported to CSV and visualized using tools like Excel.
# Supply Chain Performance Assessment :
**Objective:** Identify variances between forecasted sales quantity and actual sold quantity to improve demand forecast accuracy. Calculate forecast accuracy data (forecast accuracy = 100% - absolute error%) for analysis based on different criteria such as customer, product, or region.
**Tools Used:** SQL for analyzing variances and calculating forecast accuracy. Insights from this analysis facilitate improvements in demand forecast accuracy.

# SQL Skills Utilized
The projects involve various SQL skills, 
•SQL basics SELECT, WHERE, BETWEEN, GROUP BY, ORDER BY
•Joins LEFT, RIGHT, INNER, FULL, CROSS. 
•Advanced query techniques subqueries, CTEs, views, temporary tables.
•Database concepts fundamentals of ETL, data warehousing, OLAP, OLTP.
•Data engineering-specific topics indexes, triggers, events, user accounts & privileges.
•Procedural programming user-defined functions, stored procedures.
•Window functions (OVER, ROW_NUMBER, RANK, DENSE_RANK).
