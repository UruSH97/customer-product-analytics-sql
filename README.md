# Customer & Product Analytics – SQL Reporting Views

Customer & Product Analytics using SQL Designed and implemented SQL-based reporting views for customer and product analytics. Engineered KPIs such as AOV, customer segmentation, recency, and performance tiers to aid strategic decision-making. Employed dimensional modeling, aggregation logic, and time-based analysis on sales data.

---

## Project Overview

### Customer Analytics View

A reporting layer focused on understanding customer behavior and lifetime value.

**Key Features:**
- Segmentation by age group and purchasing behavior (VIP, Regular, New)
- Metrics:
  - Total orders, total sales, quantity purchased
  - Product category and item diversity
  - Recency of last order (in days/months)
  - Average order value (AOV)
  - Monthly spend trends
  - Customer lifespan (months between first and most recent order)

### Product Performance View

Analyzes how individual products perform over time and across customer segments.

**Key Features:**
- Classification of products into High-, Mid-, and Low-Performers based on sales revenue
- Metrics:
  - Total sales and quantity sold
  - Number of unique customers per product
  - Average selling price
  - Revenue per order containing the product
  - Monthly revenue trends
  - Product lifespan (active months between first and last sale)

---

## Skills Demonstrated

- Advanced SQL techniques (joins, CTEs, case statements, subqueries)
- KPI development (AOV, recency, segmentation scores)
- Time-based analysis (customer and product lifespans, recency metrics)
- Dimensional modeling using a star schema (fact and dimension tables)
- Business logic implementation and validation through SQL

---

## Technical Stack

- Microsoft SQL Server for data processing and analysis
- Git for version control
- Schema design:
  - fact_sales
  - dim_customers
  - dim_products

---

## Real-World Applications

The logic and structure used in this project apply directly to:
- Customer Relationship Management (CRM) platforms
- Sales and revenue dashboards for executives
- Product lifecycle and performance tracking
- Marketing segmentation and campaign targeting

---

## Contributions

Suggestions for improvement are welcome. If you’d like to enhance a metric, refactor logic, or extend the scope, feel free to open an issue or submit a pull request.

---

Let me know if you want to include example queries, sample data, or schema diagrams.
