# Supply-Chain-Analytics
# Introduction
This project provides a data-driven analysis of delivery performance for a fictional company, Atliq Mart. The company has provided several CSV files that contain information about customers, products, dates, targets, and order details. The goal of this project is to create a dataframe that summarizes the delivery performance of each customer and compares it to the assigned targets.
# Prerequisites
 To run this project, you will need the following software.
Python 3.x
Pandas library
Matplotlib library (optional, for visualization).
# Project Structure
 The project consists of the following files:

analysis.py: the main Python script that performs the data analysis and produces the final dataframe.
dim_customers.csv: a CSV file that contains information about customers, including their unique identifier, name, and city.
dim_products.csv: a CSV file that contains information about products, including their name, unique identifier, and category.
dim_date.csv: a CSV file that contains information about dates, including the date at the daily level, date at the monthly level, and week number of the year.
dim_targets_orders.csv: a CSV file that contains target data at the customer level, including the customer's unique identifier, ontime target percentage, infull target percentage, and otif target percentage.
fact_order_lines.csv: a CSV file that contains information about orders and each item inside the orders, including the order ID, order placement date, customer ID, product ID, order quantity, agreed delivery date, actual delivery date, and delivered quantity.
fact_orders_aggregate.csv: a CSV file that contains information about OnTime, InFull, and OnTime Infull information aggregated at the order level per customer, including the order ID, customer ID, order placement date, on-time flag, in-full flag, and otif flag.
# Conclusion
This project demonstrates how to use Python and Pandas to perform a data-driven analysis of delivery performance for a fictional company. The final dataframe provides valuable insights into the delivery performance of each customer and helps the company identify areas for improvement.
