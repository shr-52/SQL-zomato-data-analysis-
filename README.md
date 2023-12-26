
Zomato SQL Project

This repository contains the SQL queries and their corresponding questions and answers for the Zomato SQL Project. The project involves analyzing data related to Zomato, a food delivery platform, to gain insights into customer behavior and popular food items.

SQL Questions 

Q1. What is the total amount each customer spends on Zomato? 

This query calculates the total amount spent by each customer on Zomato by joining the sales and product tables and grouping the results by the userid. 

Q2. How many days has each customer visited Zomato? 

This query determines the number of days each customer has visited Zomato by counting the distinct created_date entries in the sales table for each userid. 

Q3. What was the first product purchased by each customer? 

This query retrieves the first product purchased by each customer based on the earliest created_date in the sales table for each userid. 

Q4. What is the most purchased item on the menu, and how many times has it been purchased by all customers? 

This query identifies the most purchased item on the menu by counting the occurrences of each product_id in the sales table and selecting the one with the highest count. 

Q5. Which item was the most popular for each customer? 

This query finds the most popular item for each customer by counting the occurrences of each product_id for each userid in the sales table and selecting the one with the highest count.
Zomato SQL Project



