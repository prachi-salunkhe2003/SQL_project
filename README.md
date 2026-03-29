# 🛒 Retail Sales Data Analysis (SQL Project)

## 📌 Overview

This project focuses on analyzing retail sales data using SQL. The goal is to extract meaningful business insights such as customer behavior, sales trends, and product performance.

The project covers:

* Data cleaning
* Data exploration
* Business problem solving using SQL queries

---

## 🗄️ Database Details

* **Database Name:** `sql_proj`
* **Table Name:** `retail_sales`

### 📊 Table Schema

| Column Name     | Data Type | Description           |
| --------------- | --------- | --------------------- |
| transactions_id | INT       | Unique transaction ID |
| sale_date       | DATE      | Date of sale          |
| sale_time       | TIME      | Time of sale          |
| customer_id     | INT       | Customer ID           |
| gender          | VARCHAR   | Customer gender       |
| age             | INT       | Customer age          |
| category        | VARCHAR   | Product category      |
| quantiy         | INT       | Quantity sold         |
| price_per_unit  | FLOAT     | Price per unit        |
| cogs            | FLOAT     | Cost of goods sold    |
| total_sale      | FLOAT     | Total sale value      |

---

## 🧹 Data Cleaning

* Checked for NULL values in key columns:

  * transaction_id, sale_date, sale_time
  * gender, category, quantity
  * cogs, total_sale

---

## 🔍 Data Exploration

* Total number of sales
* Total number of customers
* Unique product categories

---

## 📈 Business Questions & Analysis

### ✅ Q1: Sales on a specific date

* Retrieved all transactions on **2022-11-05**

### ✅ Q2: High quantity clothing sales

* Filtered transactions where:

  * Category = Clothing
  * Quantity ≥ 4
  * Month = November 2022

### ✅ Q3: Total sales by category

* Calculated total revenue and number of orders per category

### ✅ Q4: Average age of Beauty customers

* Found the average age of customers buying beauty products

### ✅ Q5: High-value transactions

* Retrieved sales where total sale > 1000

### ✅ Q6: Transactions by gender & category

* Analyzed purchasing patterns across gender and category

### ✅ Q7: Best-selling month each year

* Used window functions (RANK) to identify top-performing months

### ✅ Q8: Top 5 customers

* Ranked customers based on total purchase amount

### ✅ Q9: Unique customers per category

* Counted distinct customers for each category

### ✅ Q10: Sales by time shift

* Categorized sales into:

  * Morning (<12)
  * Afternoon (12–17)
  * Evening (>17)

---

## ⚙️ Tools & Technologies

* SQL (MySQL / PostgreSQL compatible)
* Window Functions
* Common Table Expressions (CTE)

---

## 🚀 How to Run the Project

1. Create the database:

```sql
CREATE DATABASE sql_proj;
```

2. Use the database:

```sql
USE sql_proj;
```

3. Create the table and run the provided SQL script

4. Execute queries to analyze the data

---

## 📊 Key Insights

* Identified top-performing product categories
* Found high-value customers
* Discovered peak sales time shifts
* Analyzed customer demographics

---

## 📈 Future Improvements

* Connect with visualization tools (Power BI / Tableau)
* Add more advanced analytics (customer segmentation)
* Automate reporting dashboards

---

## 👨‍💻 Author

Your Name
GitHub: https://github.com/prachi-salunkhe2003
