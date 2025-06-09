# SQL-Python-Ecommerce-Project

**Project Title:**
“E-Commerce Data Analysis: Leveraging SQL and Python for Business Insights”

Project Overview:
This project is centered on analyzing a comprehensive E-Commerce transactional dataset using a combination of SQL (MySQL) and Python. The dataset emulates a real-world marketplace scenario, involving multiple stakeholders like customers, sellers, products, orders, payments, and geolocations. The objective is to derive meaningful business insights by building a SQL-powered analytics engine and visualizing data-driven outcomes using Python.

The project is segmented into three tiers of analytical difficulty — Easy, Intermediate, and Hard — allowing a progressive demonstration of data extraction, transformation, and deep analysis skills.

**Workflow: Step-by-Step Execution**
 
**Step 1: Data Acquisition and Preparation**

Multiple .csv files including:

customers.csv, orders.csv, products.csv, sellers.csv, order_items.csv, payments.csv, geolocation.csv

Each file contains tabular data relevant to different e-commerce operations.




**Step 2: Database Integration with MySQL**

A custom Python script (csv_to_sql.py) was created to automate:

Reading .csv files with Pandas

Inferring column data types

Creating and initializing tables dynamically in a MySQL database

Cleaning column names (removal of special characters)

Inserting the data from CSVs into SQL using mysql-connector




**Step 3: Jupyter Notebook Analysis**

The main analytical component was built using a Jupyter Notebook titled python+sql_ecommerce.ipynb.

It connects to the MySQL database using mysql.connector.

Each business question is answered using SQL queries.

Results are extracted using Python, processed with Pandas, and visualized using Matplotlib and Seaborn.




# Structure of Analysis

The analysis is broken into 15 business questions, organized by difficulty:

🟢 Easy-Level Insights (Q1–Q5)
Focus: Data extraction and summarization

List of unique cities where customers are located

Count of orders in 2017

Total sales per product category

Percentage of installment payments

Number of customers per state (visualized with bar chart)



🟡 Intermediate-Level Insights (Q6–Q10)
Focus: Multi-table joins, conditional aggregation

Orders per month (2018)

Average products per order by city using CTE

Revenue contribution % by category

Correlation between product price and frequency

Seller revenue ranking using DENSE_RANK()



🔴 Advanced-Level Insights (Q11–Q15)
Focus: Window functions, retention, moving averages

Moving average of customer order values

Monthly cumulative sales trends

Year-over-year growth rate of total revenue

Customer retention rate (within 6 months)

Top 3 high-spending customers per year using partitioned ranking




**Key Features:**

This project showcases dynamic SQL table creation, efficient ETL with Python, advanced SQL queries (CTEs, window functions), and integrated visualizations. Its tiered question structure, real-world e-commerce context, and clean modular code make it both analytically rich and professionally impactful.




**Conclusion:**
This project demonstrates capability to:

Handle raw data ingestion, cleaning, and database setup

Write complex SQL queries for meaningful business analysis

Use Python for visualization and post-query processing

Break down a problem in tiered levels of complexity

Integrate multiple technologies into a unified, production-like pipeline
