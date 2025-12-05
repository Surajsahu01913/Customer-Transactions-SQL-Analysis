# Customer-Transactions-SQL-Analysis
A comprehensive SQL analytics project based on a retail transactional dataset containing Customers, Transactions, and Product Category information. This project explores 15+ real-world business questions using advanced SQL techniques such as joins, grouping, ranking, window functions, subqueries, CTEs, and date-based analysis.


🛒 Retail Transactions SQL Analysis Project
This project focuses on analyzing a retail dataset using SQL to derive insights on customer behavior, revenue performance, product categories, store types, and transaction trends.
It includes 15+ real-world SQL queries demonstrating expertise in joins, aggregations, date functions, window functions, CTEs, ranking, and subquery-based analysis.

📁 Project Structure
├── SQL_PROJECT_3.sql   # Main SQL script with all queries
└── README.md           # Documentation for GitHub

🛢️ Database Tables
1. Customer Table
Contains customer demographic information:customer_id,gender,city_code,DOB

2. prod_cat_info Table
Stores product category & subcategory details:prod_cat_code,prod_cat,prod_subcat_code,prod_subcat

3. Transactions Table
Contains retail transaction-level details:transaction_idcust_id,prod_cat_code,prod_subcat_code,store_type,qty,total_amt,tran_date

🧠 Skills Demonstrated

This project uses key SQL concepts including:

✔ INNER JOIN & table relationships
✔ GROUP BY & HAVING
✔ Aggregations (SUM, AVG, COUNT, MAX, MIN)
✔ Date functions (DATEDIFF, DATEADD, MAX date lookup)
✔ Window functions (DENSE_RANK)
✔ CTEs (WITH clause)
✔ Subqueries & nested SELECTs
✔ Conditional logic using CASE
✔ Ranking & top-N analysis

📊 Business Analysis Questions Solved
1. Most frequently used transaction channel
2. Count of male vs female customers
3. City with the highest customer count
4. Number of product sub-categories under Books
5. Maximum quantity ever ordered
6. Net total revenue from Electronics & Books
7. Customers with more than 10 transactions (excluding returns)
8. Combined revenue from Electronics & Clothing in flagship stores
9. Revenue from male customers in Electronics by sub-category
10. Top 5 subcategories by percent sales & returns
11. Revenue from customers aged 25–35 in last 30 days
12. Product category with highest returns in last 3 months
13. Store-type with max sales amount & quantity sold
14. Categories with average revenue above overall average
15. Avg & total revenue by subcategory for top 5 categories by quantity sold
🚀 How to Execute the Project

Download the project file:
SQL_PROJECT_3.sql

Open it in your preferred SQL environment:

SQL Server Management Studio (SSMS)

Azure Data Studio

DBeaver

Any SQL IDE supporting SQL Server syntax

Create and select the database:

CREATE DATABASE SQL_PROJECT_3;
USE SQL_PROJECT_3;


Run the queries section by section.

🎯 Project Purpose

This SQL project is designed to:

Strengthen SQL query-writing skills

Practice real-world analytics on retail domain data

Understand customer and sales patterns

Build a strong portfolio project for resumes or interviews

👤 Author

Suraj Sahu
SQL | Data Analytics | Python
