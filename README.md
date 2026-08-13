# Smart Retail Business Intelligence and Demand Forecasting System

## 📌 Project Overview

The **Smart Retail Business Intelligence and Demand Forecasting System** is an end-to-end Data Analytics and Business Intelligence project designed to transform retail business data into meaningful insights for better decision-making.

The project simulates a real-world retail business environment using a realistic dummy dataset containing information about customers, products, categories, suppliers, branches, employees, orders, and order details.

The project integrates **SQL, Python, Excel, and Power BI** to perform data storage, data cleaning, analysis, visualization, business intelligence, inventory analysis, and demand forecasting.

---

## 🎯 Project Motivation

Retail businesses generate large amounts of data through sales transactions, customers, products, suppliers, branches, and inventory operations.

However, raw data alone does not provide useful business insights.

The main motivation of this project is to build a complete analytics solution that can help a retail business:

- Understand sales performance
- Identify high-performing products and categories
- Analyze customer purchasing behavior
- Monitor inventory levels
- Identify products requiring additional stock
- Analyze supplier and product pricing
- Compare branch performance
- Estimate future product demand
- Support data-driven business decisions

---

## 🎯 Project Objectives

The major objectives of this project are:

- Design a structured retail database using SQL
- Create relationships between multiple business entities
- Perform data cleaning and preprocessing using Python
- Analyze retail data using SQL and Python
- Build interactive Power BI dashboards
- Develop business KPIs and analytical measures using DAX
- Analyze customer and product performance
- Monitor inventory and stock requirements
- Perform demand forecasting using historical sales data
- Create an interactive supplier-wise product price lookup
- Provide actionable business insights

---

# 🏗️ Project Architecture

The project follows an end-to-end data analytics workflow:

**Dummy Retail Dataset**

↓

**Excel**

↓

**SQL / MySQL Database**

↓

**Python – Data Cleaning & Analysis**

↓

**Power BI Data Model**

↓

**DAX & Power Query**

↓

**Interactive Dashboards**

↓

**Business Insights & Demand Forecasting**

---

# 🗄️ Database Design

The retail database contains **8 interconnected tables**:

1. Customers
2. Products
3. Categories
4. Suppliers
5. Branches
6. Employees
7. Orders
8. Order_Details

These tables are connected using primary keys and foreign keys to create a structured relational database.

### Key Relationships

- Customers → Orders
- Employees → Orders
- Branches → Orders
- Orders → Order_Details
- Products → Order_Details
- Categories → Products
- Suppliers → Products

This relational structure allows business information to be analyzed across different dimensions such as customers, products, suppliers, branches, and sales transactions.

---

# 🐍 Python Data Analysis

Python is used as part of the data preprocessing and analytical workflow.

### Python is used for:

- Data loading
- Data cleaning
- Handling missing values
- Removing duplicate records
- Data validation
- Data transformation
- Exploratory Data Analysis
- Identifying sales patterns
- Preparing analysis-ready datasets

### Libraries Used

- Pandas
- NumPy
- Matplotlib

---

# 🧮 SQL Analysis

SQL is used to manage and analyze the retail database.

### SQL is used for:

- Database creation
- Table creation
- Primary key definition
- Foreign key relationships
- Data insertion
- Data validation
- Joining multiple tables
- Aggregation
- Filtering and sorting
- Business analysis queries

### Example Business Questions

- What are the top-selling products?
- Which categories generate the highest sales?
- Which branches perform best?
- Which customers purchase the most?
- Which products have low stock?
- Which suppliers provide specific products?
- What are the monthly sales trends?
- Which products require additional inventory?

---

# 📊 Power BI Data Model

The cleaned and structured data is connected to Power BI to create a centralized analytical model.

Power BI is used for:

- Data modeling
- Relationships
- Power Query transformations
- DAX calculations
- KPI creation
- Interactive filtering
- Data visualization
- Dashboard development

The model allows users to interact with the dashboards dynamically.

For example, when a user selects a particular category such as **Baby Care**, the related visuals and KPIs automatically update to show information relevant to that category.

---

# 📈 Power BI Dashboards

## 1. Executive Dashboard

The Executive Dashboard provides a high-level overview of the retail business.

It focuses on important business KPIs and overall performance.

### Key analysis includes:

- Total Sales
- Total Orders
- Total Customers
- Total Products
- Overall business performance
- Category performance
- Sales trends

This dashboard is mainly designed for management to quickly understand the current business situation.

---

## 2. Customer Analysis Dashboard

The Customer Analysis Dashboard focuses on customer purchasing behavior.

### Key analysis includes:

- Customer purchase patterns
- Customer contribution to sales
- Customer distribution
- Purchase trends
- Customer-level performance

This helps the business understand customer behavior and identify valuable customer segments.

---

## 3. Inventory Analysis Dashboard

The Inventory Analysis Dashboard focuses on stock availability and inventory requirements.

### Key analysis includes:

- Current stock
- Product-wise inventory
- Stock availability
- Low-stock products
- Inventory requirements
- Quantity required for replenishment

This dashboard helps inventory managers identify products that may require additional stock.

---

## 4. Sales Analysis Dashboard

The Sales Analysis Dashboard provides detailed sales performance analysis.

### Key analysis includes:

- Sales trends
- Product-wise sales
- Category-wise sales
- Branch-wise performance
- Monthly sales
- Top-performing products

Interactive filters allow users to analyze specific categories, products, branches, or time periods.

For example, selecting the **Baby Care** category dynamically updates the dashboard to display the sales and performance information related to that category.

---

## 5. Demand Forecasting Dashboard

The Demand Forecasting Dashboard focuses on estimating future product requirements based on historical sales patterns.

The dashboard compares:

- Historical quantity sold
- Last 3 months quantity
- Predicted quantity
- Current stock
- Quantity to purchase

A prediction table is included to help identify products that may require additional inventory.

### Example

If the predicted demand for a product is higher than its current stock, the dashboard calculates the approximate **Quantity to Purchase**.

This helps the business prepare inventory before stock shortages occur.

---

## 6. Supplier-Wise Product Price Lookup

The Supplier-Wise Product Price Lookup is an interactive dashboard designed to quickly identify product and supplier information.

Users can select:

- Product
- Supplier

Based on the selected product and supplier, the dashboard dynamically displays relevant information such as:

- Selected Product
- Unit Price
- Supplier
- Current Stock
- Product-related information

This makes it easier to compare supplier-wise product pricing and support purchasing decisions.

---

# 🔄 Interactive Dashboard Features

The Power BI solution provides interactive analysis through:

- Slicers
- Filters
- Cross-filtering
- Dynamic KPIs
- Product selection
- Category selection
- Supplier selection
- Drill-down analysis
- Interactive tables

For example, selecting a category changes the values across the relevant visuals, allowing users to analyze that category without manually changing individual charts.

---

# 🧰 Tools & Technologies

### Database & Querying
- MySQL
- SQL

### Programming & Data Analysis
- Python
- Pandas
- NumPy
- Matplotlib

### Data Preparation
- Microsoft Excel
- Power Query

### Business Intelligence
- Microsoft Power BI
- DAX

---

# 📁 Project Structure

```text
Smart-Retail-Business-Intelligence-and-Demand-Forecasting-System
│
├── README.md
│
├── SQL
│   ├── Database_Creation.sql
│   ├── Table_Creation.sql
│   ├── Relationships.sql
│   └── Business_Analysis_Queries.sql
│
├── Python
│   ├── Data_Cleaning.ipynb
│   └── Exploratory_Data_Analysis.ipynb
│
├── Dataset
│   └── Retail_Dataset.xlsx
│
├── PowerBI
│   └── Smart_Retail_Business_Intelligence.pbix
│
├── Screenshots
│   ├── Executive_Dashboard.png
│   ├── Customer_Analysis.png
│   ├── Inventory_Analysis.png
│   ├── Sales_Analysis.png
│   ├── Demand_Forecasting.png
│   └── Supplier_Wise_Product_Price_Lookup.png
│
└── Documentation
    └── Project_Report.pdf
