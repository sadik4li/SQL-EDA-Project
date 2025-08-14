# SQL Exploratory Data Analysis (EDA) Project on Sales Data

This project demonstrates an end-to-end exploratory data analysis (EDA) process using Microsoft SQL Server. The goal was to uncover key insights and patterns from a sales dataset. The analysis focused on understanding customer demographics, product performance, and sales trends.

The dataset used for this project consists of three tables: gold.fact_sales, gold.dim_products, and gold.dim_customers. By joining these tables, I was able to perform a comprehensive analysis across various dimensions.

•Project Sections

Database Exploration
This section involved an initial exploration of the database schema and data types. I used SELECT TOP queries to get a quick look at the data structure and performed checks for null values and data integrity to ensure the tables were ready for analysis.

Dimension Exploration
I delved into the dimensional tables, gold.dim_customers and gold.dim_products, to understand the characteristics of our customers and products. 
This included:

Analyzing customer demographics such as country, marital status, and gender.

Examining product details like category, subcategory, and product line to identify popular or high-cost items.

Date Exploration
In this section, I focused on the temporal aspects of the sales data. I extracted and analyzed information from the order_date, shipping_date, and due_date columns in the gold.fact_sales table. Queries were written to identify:

Sales trends over time.

The frequency of orders.

The time taken between placing an order and shipping.

Measure Exploration
This part of the project focused on key metrics within the gold.fact_sales table. I used aggregate functions to calculate:

Total sales amount across different categories.

Average sales price per product.

Total quantity sold.

Magnitude and Ranking
This final section involved using advanced SQL functions to rank and categorize the data. Key analyses included:

Ranking customers by their total sales to identify top customers.

Ranking products by sales amount to identify best-selling products.

Using CASE statements and window functions to categorize sales performance and rank items within different groups.

•Technologies Used

Microsoft SQL Server: The primary database used for all data storage and query execution.

SQL: The language used for all exploratory queries and analysis.
