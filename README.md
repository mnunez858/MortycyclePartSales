Motorcycle Parts Sales Analysis

Introduction
Welcome to the Motorcycle Parts Sales Analysis project! In this project, we'll be analyzing the sales data of a company that sells motorcycle parts. The company operates three warehouses in the area, selling both retail and wholesale, and offers various payment methods including credit cards, cash, and bank transfer.

Project Objective
The objective of this project is to analyze the sales data provided by the company and calculate net revenue for each product line, grouped by month and warehouse. We'll focus specifically on "Wholesale" orders to understand wholesale revenue variations over time and across warehouses.

Data Provided
The company has provided a dataset containing the sales data. The dataset includes the following columns:

order_id: Unique identifier for each order.
order_date: Date of the order.
product_line: Product line of the item sold.
warehouse: Warehouse from which the item was sold.
order_type: Type of order (e.g., "Retail", "Wholesale").
payment_method: Payment method used for the order (e.g., "Credit Card", "Cash", "Bank Transfer").
order_amount: Total amount of the order.
Analysis Steps
To achieve our objective, we'll follow these steps:

Connect to the Database: Connect to the provided PostgreSQL database.
Retrieve Data: Retrieve the sales data from the database.
Filter Data: Filter the data to include only "Wholesale" orders.
Calculate Net Revenue: Calculate net revenue for each product line, considering payment method fees.
Group Data: Group the results by month and warehouse.
Analysis: Analyze the data to understand revenue variations over time and across warehouses.
Tools Used
PostgreSQL: For querying the provided database.
