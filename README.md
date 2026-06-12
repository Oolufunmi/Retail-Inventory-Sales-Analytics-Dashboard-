# Retail Inventory & Sales Analytics Dashboard | Microsoft Excel

An interactive Retail Inventory & Sales Analytics Dashboard built in Microsoft Excel to help retailers monitor inventory levels, evaluate sales performance, track profitability, and identify inventory trends across multiple store locations.

This project demonstrates how raw retail transaction data can be transformed into an executive reporting solution using Power Pivot, Pivot Tables, Pivot Charts, and interactive slicers. The dashboard enables business users to monitor key performance indicators, identify high-performing products, evaluate store performance, and make informed inventory decisions without manually reviewing thousands of transaction records.

---

# Dashboard Preview

<p align="center">
  <img src="<img width="1318" height="766" alt="dashboard" src="https://github.com/user-attachments/assets/ca70d284-e25e-4135-bb5d-d7f83f019e8a"

---

# Project Overview

Retail businesses process hundreds or even thousands of inventory and sales transactions every month. While the data contains valuable insights, manually analyzing spreadsheets can be time-consuming and often leads to delayed decision-making.

The objective of this project was to develop an interactive reporting solution capable of transforming raw transactional data into meaningful business insights through automated calculations and interactive visualizations.

The dashboard was designed to answer common business questions such as:

- Which stores generate the highest revenue?
- Which products contribute most to sales?
- How healthy is the current inventory?
- Which product categories require replenishment?
- How are sales trending over time?
- Which products are driving profitability?

---

# Business Problem

Retail managers often struggle with:

- Scattered inventory records across multiple locations
- Limited visibility into product performance
- Manual sales reporting
- Difficulty identifying inventory shortages
- Time-consuming monthly reporting processes

This dashboard centralizes inventory and sales reporting into a single interactive interface, making it easier for business users to monitor operations and make data-driven decisions.

---

# Solution

Using Microsoft Excel and Power Pivot, I developed a dashboard that consolidates retail transaction data into an interactive reporting solution.

The solution provides:

- Executive KPI cards
- Interactive filtering using slicers
- Automated sales analysis
- Inventory monitoring
- Store performance analysis
- Monthly sales trend reporting
- Product performance tracking

---

# Tools & Technologies

- Microsoft Excel
- Power Pivot
- Pivot Tables
- Pivot Charts
- Slicers
- Excel Formulas
- Data Modeling
- Data Visualization

---

# Data Model

The dashboard is powered by a relational data model created using Power Pivot.

<p align="center">
<img src="images/data-model.png" width="700">
</p>

### Tables

- Product Master
- Retail Transactions

### Relationship

```
Product Master (1)
        │
        │
        ▼
Retail Transactions (*)
```

The data model eliminates duplicate product information while enabling efficient aggregation and analysis across inventory and sales records.

---

# Dashboard Features

## Executive KPIs

The dashboard provides instant visibility into key business metrics including:

- Total Revenue
- Total Profit
- Total Inventory
- Inventory Health
- Top Selling Product
- Monthly Revenue Trend

---

## Interactive Reporting

Users can explore the data using interactive slicers.

Available filters include:

- Store
- Product
- Product Category
- Month

These filters allow users to quickly analyze business performance across different dimensions without modifying the underlying dataset.

---

## Analytical Visualizations

The dashboard includes several visual reports including:

- Revenue by Product Category
- Revenue by Store
- Monthly Revenue Trend
- Inventory Health Distribution
- Top Selling Products
- Store Performance Comparison

Each visualization updates dynamically based on user selections.

---

# Dashboard Screenshots

## Executive Dashboard

<p align="center">
<img src="images/dashboard.png" width="900">
</p>

---

## Power Pivot Data Model

<p align="center">
<img src="images/data-model.png" width="700">
</p>

---

## Pivot Table Analysis

<p align="center">
<img src="images/pivot-table.png" width="700">
</p>

---

# Business Insights

The dashboard helps decision-makers answer important business questions such as:

- Which products generate the highest revenue?
- Which stores consistently outperform others?
- Which inventory categories require restocking?
- How has revenue changed over time?
- Which products contribute most to profitability?
- What is the overall health of inventory?

---

# Skills Demonstrated

This project demonstrates practical experience in:

- Data Cleaning
- Data Modeling
- Power Pivot
- Pivot Tables
- Pivot Charts
- Dashboard Design
- KPI Development
- Data Visualization
- Business Intelligence
- Inventory Analytics
- Sales Analytics
- Retail Performance Reporting

---

# Repository Structure

```
Retail-Inventory-Sales-Dashboard/

│── Dashboard.xlsx
│── README.md

├── images/
│   ├── dashboard.png
│   ├── data-model.png
│   ├── pivot-table.png

└── screenshots/
```

---

# Why This Project Matters

This project demonstrates how Microsoft Excel can be used as a Business Intelligence platform rather than just a spreadsheet application.

By combining Power Pivot, relational data modeling, Pivot Tables, and interactive dashboards, the solution transforms raw retail data into meaningful business insights that support inventory management, sales monitoring, and operational decision-making.

The techniques used in this project can be adapted to retail stores, wholesalers, supermarkets, pharmacies, e-commerce businesses, and other organizations that rely on inventory and sales data to drive business performance.

---

# About Me

**Olufunmilola Olaewe**

Data Analyst | Excel | Power BI | SQL

I build interactive dashboards and reporting solutions that help businesses transform raw data into actionable insights.

- LinkedIn: *(Add your LinkedIn profile)*
- Upwork: *(Add your Upwork profile)*
- Portfolio: *(Add your portfolio link)*
