# mysql-ecommerce-project
MySQL database schema design for an e-commerce application.

This repository contains the SQL script and Entity-Relationship (ER) diagram for a simple e-commerce database.

The database, named `ecommerce_db`, includes the following tables:

* `Categories`: Stores product categories.
* `Products`: Contains details about individual products, linked to categories.
* `Customers`: Stores customer information.
* `Orders`: Records customer orders, linked to customers.
* `OrderDetails`: A junction table that captures the many-to-many relationship between orders and products, detailing which products are in each order.
