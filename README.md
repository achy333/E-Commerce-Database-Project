
This project is a SQL database design and query demonstration for managing an e-commerce-like system. Here's an explanation of each component:

Project Overview
The database contains tables for users, products, orders, and order details. It simulates a system where:

Users can place orders.
Orders consist of multiple products.
Product stock is managed, and order totals are calculated.
Structure



Database Creation
A database named SampleDB is created and used for storing all tables.
Tables
Users Table: Stores user information like ID, name, email, and account creation timestamp.
Products Table: Stores product information such as ID, name, price, and stock count.
Orders Table: Tracks orders, linking them to users, with timestamps and total amounts.
OrderDetails Table: Tracks the details of each order, including product IDs, quantities, and prices.



Relationships
Orders are linked to users using a foreign key (UserID).
Order details are linked to both orders and products using foreign keys (OrderID, ProductID).






