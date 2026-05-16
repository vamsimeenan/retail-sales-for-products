# Retail Sales & Inventory Intelligence System

## Project Overview
End-to-end retail analytics solution for a mobile phone and laptop retailer.
Covers 5 stores, 10 staff, 200 customers, 1000 orders, 30 products.

## Phase 1 — Data Preparation
- Generated 9 structured CSV datasets using Python (Faker + random)
- Tables: brands, categories, products, stores, staffs, customers, orders, order_items, stocks
- Total transactions: 2536 order line items

## Phase 2 — SQL Analysis
- Database: MySQL retail_db
- 10 analytical views created (store sales, staff performance, brand revenue, etc.)
- Key finding: all views available for Power BI connection

## Phase 3 — Python Analysis
- Total Revenue: ₹342,239,240
- Total Orders: 1,000 | Customers: 200 | Products: 30
- KMeans segmentation: High Value / Mid Value / Low Value customers
- 10 charts generated covering brands, categories, stores, staff, trends

## Phase 4 — Power BI Dashboard
- Connected to MySQL retail_db views
- KPI cards, bar charts, line trends, slicers built
- Drill-down by store, brand, date, category

## Key Insights
1. Revenue distributed across 5 stores with staff performance tracked
2. 2 product categories (mobiles & laptops) — laptops drive higher revenue
3. Customer segmentation shows 3 distinct spending tiers
4. Monthly trends show seasonal order patterns
5. Stock levels vary by store — some products near zero

## Tools Used
Excel (data review) | MySQL 9.6 | Python 3.11 | Power BI Desktop
