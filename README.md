# Database-Application
Cafe Shop Management System

## Overview

This project is a Cafe Shop Management System developed as part of the CS 306 First Assignment. The system aims to organize and track the ordering process in franchise branches of a cafe. It manages information about the cafe shop, waiters, customer orders, bills, and menu items. The system simplifies the order and billing process while tracking waiter performance and cafe inventory.

## Features and Functionalities

### Cafe Shop
- **Shop Details:** Comprehensive information about the cafe shop, including ShopID, name, location, and contact information.

### Waiter Management
- **Waiter Profiles:** Efficient management of the cafe's team of waiters, including WaiterID, first and last names, wages, and working hours.

### Menu Item Inventory
- **Menu Item Listings:** Up-to-date list of the cafe's menu items, each associated with attributes such as item name, cost, and quantity in stock.

### Table Management
- **Order Recording:** Recording and management of customer orders, capturing information like the responsible waiter, order date, OrderID, and Quantity.

### Order Item Tracking
- **Individual Menu Items Ordered:** Tracking of the individual menu items ordered, recording OrderItemID, OrderID, ItemID, and quantity ordered.

### Bill Generation
- **Bills for Customer Orders:** Generation of bills for customer orders, including total amount due, tip amount, payment method, time, and date.

### Inventory Tracking
- **Quantity in Stock:** Management of inventory by tracking the quantity in stock for each menu item, including item cost and item ID.

## Participation Constraints

- Table served by only one waiter (One-to-Many Relationship).
- Waiters only work in one cafe (One-to-Many Relationship).
- Menu Items and Table Orders (Many-to-Many Relationship).
- Table Order Generates Only One Bill (One-to-One Relationship).
- Each bill linked to a waiter, ensuring every order is served by one waiter.
- Every table is assigned to a single waiter to avoid multiple attendants.
- Bills can't exist without a table association.
- Every table order linked to a specific table.

## Relational Model (Create Table Statements)

SQL `CREATE TABLE` statements at the SQL file
