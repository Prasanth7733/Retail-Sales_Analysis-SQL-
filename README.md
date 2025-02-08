# Retail Sales Analysis SQL Project

## Project Overview

This project is designed to help beginners develop their SQL skills by analyzing retail sales data. The project involves setting up a retail sales database, performing exploratory data analysis (EDA), and answering specific business questions using SQL queries. It’s a great starting point for those looking to build a strong foundation in data analysis and SQL.

## Objectives

1. **Database Setup**: Create and populate a retail sales database with the provided sales data.
2. **Data Cleaning**: Identify and handle missing or null values in the dataset.
3. **Exploratory Data Analysis (EDA)**: Perform basic data exploration to understand the dataset's structure and characteristics.
4. **Business Analysis**: Use SQL to derive insights and answer key business questions related to sales performance, customer behavior, and product trends.

## Project Structure

### 1. Database Setup

- **Database Creation**: A database named `p1_retail_db` is created to store the retail sales data.
- **Table Creation**: A table named `retail_sales` is designed to store transaction details, including sale dates, customer information, product categories, quantities, prices, and total sales.

### 2. Data Exploration & Cleaning

- **Record Count**: Determine the total number of records in the dataset.
- **Customer Count**: Identify the number of unique customers in the dataset.
- **Category Count**: List all unique product categories available in the dataset.
- **Null Value Handling**: Check for null values in the dataset and clean the data by removing incomplete records.

### 3. Data Analysis & Findings

The project focuses on answering key business questions through SQL queries. These include analyzing sales trends, identifying top-performing categories, understanding customer demographics, and evaluating high-value transactions. The analysis provides actionable insights into sales performance and customer behavior.

---

## Business Questions

The following business questions are addressed in this project:

1. **Daily Sales Analysis**: Retrieve all sales transactions made on a specific date (e.g., '2022-11-05').
2. **Category-Specific Sales**: Identify transactions where a specific category (e.g., 'Clothing') had a high quantity sold (e.g., more than 4 units) during a particular month (e.g., November 2022).
3. **Total Sales by Category**: Calculate the total sales for each product category.
4. **Customer Demographics**: Find the average age of customers who purchased items from a specific category (e.g., 'Beauty').
5. **High-Value Transactions**: Identify all transactions where the total sale amount exceeds a specific threshold (e.g., 1000).
6. **Gender-Based Sales**: Determine the total number of transactions made by each gender in each product category.
7. **Monthly Sales Trends**: Calculate the average sales for each month and identify the best-selling month in each year.
8. **Top Customers**: Identify the top 5 customers based on their total purchase amounts.
9. **Unique Customers per Category**: Find the number of unique customers who purchased items from each category.
10. **Sales by Time Shift**: Categorize sales into shifts (Morning, Afternoon, Evening) and analyze the number of orders placed during each shift.

---

## Key Insights

- **Customer Demographics**: The dataset includes customers from diverse age groups, with sales distributed across categories such as Clothing and Beauty.
- **High-Value Transactions**: The analysis identifies transactions with significant total sales, highlighting premium purchases.
- **Sales Trends**: Monthly sales trends are analyzed to identify peak seasons and periods of high demand.
- **Customer Insights**: The project identifies top-spending customers and the most popular product categories, offering valuable insights for targeted marketing strategies.

## Reports

- **Sales Summary**: A comprehensive report summarizing total sales, customer demographics, and category performance.
- **Trend Analysis**: Insights into sales trends across different months and time shifts.
- **Customer Insights**: Reports on top customers and unique customer counts per category, helping businesses understand their customer base better.

## Conclusion

This project provides a hands-on introduction to SQL for data analysis, covering database setup, data cleaning, exploratory data analysis, and business-driven SQL queries. The insights derived from this analysis can help businesses make informed decisions by understanding sales patterns, customer preferences, and product performance.

## How to Use

1. **Clone the Repository**: Clone this project repository from GitHub to your local machine.
2. **Set Up the Database**: Run the SQL scripts provided in the `database_setup.sql` file to create and populate the database.
3. **Run the Queries**: Use the SQL queries provided in the `analysis_queries.sql` file to perform your analysis.
4. **Explore and Modify**: Feel free to modify the queries to explore different aspects of the dataset or answer additional business questions.

This project is an excellent resource for beginners to practice SQL and gain experience in analyzing real-world retail sales data. Happy analyzing!
