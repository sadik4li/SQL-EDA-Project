# 📊 SQL Exploratory Data Analysis (EDA) Project on Sales Data  

This project demonstrates an end-to-end **Exploratory Data Analysis (EDA)** process using **Microsoft SQL Server**. The goal was to uncover key insights and patterns from a sales dataset by analyzing customer demographics, product performance, and sales trends.  

---

## 🗂 Dataset Overview  
The dataset consists of three relational tables stored in a **star schema** format:  

- **`gold.fact_sales`** → Contains sales transactions, order dates, shipping dates, quantities, and amounts.  
- **`gold.dim_products`** → Product details such as category, subcategory, and product line.  
- **`gold.dim_customers`** → Customer demographics including gender, marital status, and country.  

By joining these tables, a comprehensive multi-dimensional analysis was performed.  

---

## 📑 Project Sections  

### 🔍 1. Database Exploration  
- Explored the schema and structure of the database.  
- Used `SELECT TOP` queries to sample records.  
- Checked for **null values** and ensured **data integrity** before deeper analysis.  

---

### 👥 2. Dimension Exploration  
Focused on the dimensional tables to understand customers and products:  
- **Customers (dim_customers):**  
  - Analyzed demographics (country, marital status, gender).  
- **Products (dim_products):**  
  - Examined categories, subcategories, and product lines to identify **popular** and **high-cost** items.  

---

### 📅 3. Date Exploration  
Analyzed temporal trends from `order_date`, `shipping_date`, and `due_date` in `fact_sales`:  
- Tracked **sales trends over time**.  
- Analyzed **order frequency**.  
- Measured **shipping lead time** (time between order and shipping).  

---

### 📊 4. Measure Exploration  
Calculated key sales metrics using aggregate functions:  
- **Total sales amount** across categories.  
- **Average sales price per product**.  
- **Total quantity sold** across time and product groups.  

---

### 🏆 5. Magnitude and Ranking  
Applied advanced SQL functions to rank and categorize data:  
- Ranked **top customers** by total sales.  
- Ranked **best-selling products** by revenue.  
- Used **CASE statements** and **window functions** for categorization and ranking within groups.  

---

## 🛠 Technologies Used  
- **Microsoft SQL Server** → Database storage and query execution.  
- **SQL** → Language for data exploration, aggregation, and ranking analysis.  

---

## 🚀 How to Use  
1. Set up a Microsoft SQL Server environment.  
2. Import the dataset tables (`fact_sales`, `dim_products`, `dim_customers`) into the **gold schema**.  
3. Run the SQL scripts in the repository to replicate the analysis.  

---

## 📌 Future Enhancements  
- Build **visual dashboards** (Power BI / Tableau) on top of the SQL queries.  
- Add **predictive insights** such as sales forecasting using SQL + ML integration.  
- Automate EDA queries for faster iteration on large datasets.  

---

## 📧 Contact  
For questions, feedback, or collaboration, please open an issue or reach out directly.  

---
