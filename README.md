CSC70000000 - Sales and Profit Analysis

Team Members and Skills

Ahmad Jassim – Good at writing Python code
Jassim Mohammed – Skilled in debugging errors in programs
Hamad Mahmoud – Can build web pages using HTML and CSS
Hamad Khalid – Understands loops and conditions in programming
About the Project

This project focuses on Sales and Profit Analysis using a dataset available on Kaggle. The goal is to analyze different aspects such as time, product categories, customer segments, discounts, and their impact on sales and profit.

Dataset Description

The dataset used is named StoreSaleData.csv, which includes:

Time-period data (Order Date, Ship Date)
Sales and Profit data
Product and Pricing information
Customer details (location, ID, name)
The data is read using the pandas library in Python:

import pandas as pd

data = pd.read_csv("StoreSaleData.csv", encoding='latin-1')
Column Descriptions:
Row ID – Unique ID for each row
Order ID – Unique Order ID for each customer
Order Date – Date when the order was placed
Ship Date – Date when the product was shipped
Ship Mode – Mode of shipping selected by the customer
Customer ID – Unique ID of the customer
Customer Name – Name of the customer
Segment – Customer segment (e.g., Consumer, Corporate, Home Office)
Country – Customer’s country
City – Customer’s city
State – Customer’s state
Postal Code – Customer’s postal code
Region – Customer’s region
Product ID – Unique product ID
Category – Category of the product
Sub-Category – Sub-category of the product
Product Name – Name of the product
Sales – Sales amount
Quantity – Number of items sold
Discount – Discount applied
Profit – Profit or loss incurred
Tools Used

Python
Pandas
Jupyter Notebook / VS Code
GitHub
Kaggle
