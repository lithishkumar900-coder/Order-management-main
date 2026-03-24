📦 Order Management System (SQL Project)
📌 Project Overview

This project demonstrates an Order Management System using SQL.
It focuses on implementing relational database concepts and business queries used in real-world E-commerce and Retail systems.

The system manages:

Customers

Products

Orders

It uses JOIN operations and Subqueries to analyze order data.

🗂 Database Name
orderdb

📊 Tables Created
1️⃣ Customers
Column Name	Data Type
customer_id	INT (Primary Key)
name	VARCHAR(100)
email	VARCHAR(100)
city	VARCHAR(50)
2️⃣ Products
Column Name	Data Type
product_id	INT (Primary Key)
product_name	VARCHAR(100)
price	DECIMAL(10,2)
3️⃣ Orders
Column Name	Data Type
order_id	INT (Primary Key)
customer_id	INT (Foreign Key)
product_id	INT (Foreign Key)
quantity	INT
order_date	DATE
🔗 Relationships

One Customer can place multiple Orders.

One Product can appear in multiple Orders.

Orders table connects Customers and Products using Foreign Keys.

🧠 SQL Concepts Used

INNER JOIN

Subqueries

GROUP BY

COUNT()

SUM()

MAX()

ORDER BY

LIMIT

Aggregate Calculations

📝 Queries Implemented
1️⃣ Customer Order History

Displays:

Customer Name

Product Name

Quantity

Total Amount

Order Date

Concepts Used:

INNER JOIN

ORDER BY

Calculated Column (quantity × price)

2️⃣ Highest Value Order

Finds:

Order with maximum total amount

Concepts Used:

MAX()

Subquery

JOIN

3️⃣ Most Active Customer

Finds:

Customer who placed the highest number of orders

Concepts Used:

GROUP BY

COUNT()

ORDER BY DESC

LIMIT

4️⃣ Total Revenue (Bonus Query)

Calculates:

Total revenue generated from all orders

Concept Used:

SUM() with JOIN

💻 Tools Used

MySQL Workbench

MySQL Server

🚀 Real-Time Applications

This type of database system is used in:

E-commerce platforms

Retail billing systems

Inventory management

Sales reporting dashboards

🎯 Learning Outcomes

Through this project, I learned:

Designing relational databases

Implementing primary and foreign keys

Writing complex JOIN queries

Using subqueries for data analysis

Applying aggregate functions for business insights

📌 Author

Mellacheruvu Mohana S M Kapil Charan
B.Tech CSE – 3rd Year
Expected Graduation: 2027
