# 🇧🇷 Brazil E-Commerce Dashboard

An interactive Power BI dashboard built using the Brazilian Olist E-Commerce dataset to analyze revenue trends, customer behavior, payment patterns, delivery performance, and category-level business insights using advanced DAX and relational data modeling.

# 📊 Dashboard Preview

## Main Dashboard

![Main Dashboard](Page%201.png)

## Drill-Through Analysis Page

![Drill Through Dashboard](Page%202.png)

# 🧩 Data Model

![Data Model](Data%20model.png)

# 📌 Project Overview

This project was developed to simulate a real-world Business Intelligence reporting solution for an e-commerce platform.

The dashboard provides:
- Executive KPI monitoring
- Product category analysis
- Customer review analysis
- Delivery performance tracking
- Payment behavior insights
- Geographic sales distribution
- Interactive drill-through reporting

The project also demonstrates advanced Power BI concepts including:
- Relational Data Modeling
- Drill-through Navigation
- Advanced DAX
- Context-aware filtering
- `TREATAS()` for indirect filter propagation
- Interactive slicers and dynamic analysis

# 📂 Dataset Information

Dataset Used:
- Brazilian Olist E-Commerce Dataset

The dataset contains:
- 100K+ Orders
- 99K+ Customers
- Multiple payment methods
- Product category translations
- Seller and customer location data
- Review and delivery information

# 🧠 Data Modeling

The dashboard follows a relational star-schema-inspired model.

### Fact Tables
- Orders
- Order Items
- Payments
- Reviews

### Dimension Tables
- Products
- Customers
- Sellers
- Translation
- Date Table
- Geolocation

### Advanced Modeling Concepts Used
- One-to-many relationships
- Bidirectional filtering
- Context transition
- Filter propagation handling
- Multi-grain analysis
- Drill-through context handling

# 📈 KPIs Tracked

The dashboard tracks:

| KPI | Value |
|---|---|
| Total Revenue | 13.59M |
| Total Orders | 99K |
| Total Customers | 99.4K |
| Average Review Score | 4.10 |
| Average Delivery Time | 12.5 Days |
| Average Order Value | 137.85 |

# 🚀 Features

## Main Dashboard
- Monthly Sales Trend
- Top Revenue Generating Categories
- State-wise Revenue Analysis
- Payment Method Distribution
- Delivery Time vs Review Analysis

## Drill-Through Analysis Page
Interactive category-level deep analysis including:

- Revenue by selected category
- Orders by customer state
- Payment behavior by category
- Review score vs delivery time
- Dynamic slicer-based exploration

# 🧮 Advanced DAX Concepts Used

## Measures
- Revenue Analysis
- Average Order Value
- Delivery Time Analysis
- Review Aggregation
- Distinct Order Calculations

## Advanced Functions
- `CALCULATE()`
- `DISTINCTCOUNT()`
- `AVERAGEX()`
- `DATEDIFF()`
- `TREATAS()`

# 🔍 Business Insights

Key insights discovered from the dashboard:

- Longer delivery times significantly reduce customer review scores.
- Credit cards dominate customer payment behavior.
- Revenue generation is concentrated heavily in specific Brazilian states.
- Certain product categories exhibit strong regional demand patterns.
- Delivery efficiency has a direct impact on customer satisfaction.

# 🛠️ Tools & Technologies

- Power BI
- DAX
- Power Query
- Data Modeling
- Relational Database Concepts

# 💡 Skills Demonstrated

- Data Cleaning & Transformation
- Relational Data Modeling
- Advanced DAX Calculations
- Drill-Through Navigation
- Dashboard Design
- Business Storytelling
- Interactive Reporting
- Analytical Thinking

# 📁 Project Structure

```bash
Brazil-Ecommerce-Dashboard/
│
├── Dashboard.pbix
├── README.md
├── Page 1.png
├── Page 2.png
├── Data model.png
└── Dataset/
```

# 🎯 Project Outcome

This project demonstrates the ability to:
- Build scalable Power BI dashboards
- Handle complex filter propagation issues
- Perform category-level analytical reporting
- Design executive-level BI dashboards
- Translate raw transactional data into business insights

# 👨‍💻 Author

## Subhankar Dutta

Aspiring Data Analyst skilled in:
- Power BI
- SQL
- Python
- Data Analytics
- Business Intelligence
