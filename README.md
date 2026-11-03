
# Retail Sales Analysis

## Project Overview
The **Retail Sales Analysis** project uses SQL to analyze retail business data and answer important business questions related to customers, products, orders, sales, and revenue.

The goal of this project is to practice SQL queries and understand how data can support business decision-making.

## Objectives
- Analyze customer distribution across cities.
- Calculate sales and quantity sold for products.
- Identify top-performing products.
- Analyze sales by customer, city, and product category.
- Find customers with multiple orders.
- Identify products that have never been ordered.
- Calculate average order value and most recent order dates.

## Database Tables
The project uses the following tables:

- `customers` — customer details and city information.
- `products` — product details, categories, and product IDs.
- `orders` — order details, quantities, sales amounts, and order dates.

## SQL Concepts Used
- SELECT
- WHERE
- INNER JOIN
- LEFT JOIN
- GROUP BY
- HAVING
- Aggregate functions: SUM, COUNT, AVG, MAX
- ORDER BY
- LIMIT
- COALESCE
- NULL handling

## Business Questions
1. How many customers are in each city?
2. What is the total sales amount for each product?
3. What is the total quantity sold for each product?
4. How much has each customer spent?
5. What is the total sales amount for each product category?
6. What is the total sales amount for each city?
7. Which cities have sales greater than 5,000?
8. Which products have a total quantity sold greater than 2?
9. Which customers have placed more than one order?
10. What are the top 3 products by total sales?
11. Which customer has spent the highest total amount?
12. Are there any products that have never been ordered?
13. Which categories have revenue greater than 5,000?
14. What is the average order value for each customer?
15. What is the most recent order date for each customer?

## Key Finding
All products in the dataset have been ordered at least once. Therefore, the query used to identify products that have never been ordered returns an empty result. This is an expected result, not a SQL error.

## Tools
- MySQL
- MySQL Workbench

## Project Files
- `retail_sales_analysis.sql` — SQL queries used for the analysis.


