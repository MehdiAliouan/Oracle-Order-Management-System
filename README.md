# Oracle Order Management System – SQL / PL/SQL Project

## 📌 Project Overview

This project simulates a transactional order management system built with Oracle SQL and PL/SQL.

The goal is to reproduce a real production-like environment where sales orders are processed through multiple automated steps (order creation, stock management, audit logging, analytics).

This project demonstrates strong SQL/PLSQL skills aligned with technical exploitation and support roles.

---

## 🏗 Architecture

The system includes:

- Clients
- Products
- Orders
- Order Items
- Audit Table
- Analytical Views
- Business Logic Package

---

## ⚙️ Technical Features

### 🔹 Database Design
- Relational schema with foreign keys
- Identity columns
- Referential integrity constraints

### 🔹 PL/SQL Business Logic
- Package `order_pkg`
  - Create order
  - Cancel order (with stock rollback)
  - Calculate total per client

### 🔹 Triggers
- Automatic stock update on order item insertion
- Audit trigger for order insert/delete operations

### 🔹 Views
- Aggregated view: total orders amount per client

### 🔹 Performance Optimization
- Index creation
- Execution plan analysis using `EXPLAIN PLAN`

### 🔹 Transaction Management
- COMMIT / ROLLBACK logic
- Controlled data consistency

---

## 🔍 Simulated Incident Handling

- Privilege error resolution (ORA-01031)
- Order recovery scenarios
- Data integrity verification after cancellation
- Stock reconciliation validation
