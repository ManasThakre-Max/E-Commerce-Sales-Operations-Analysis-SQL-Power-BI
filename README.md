# E-Commerce Sales & Operations Analysis

An interactive Power BI dashboard designed to analyze e-commerce sales performance, customers, sellers, payment methods, product categories, and delivery operations.

## 📌 Project Overview

This project analyzes e-commerce transaction data to identify important business trends and performance indicators.

The dashboard provides an interactive view of:

- Overall sales and revenue performance
- Monthly revenue trends
- Product category performance
- Seller and seller-city performance
- Payment method usage
- Delivery performance
- Customer and order statistics
- Revenue versus units sold

The project was developed using **Power BI** with data preparation, transformation, modeling, DAX calculations, and interactive dashboard design.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall e-commerce revenue and order performance
- Identify the highest-performing product categories
- Analyze seller performance by city and state
- Understand customer and order volumes
- Identify the most commonly used payment methods
- Evaluate delivery performance
- Analyze the relationship between revenue and units sold
- Build an interactive dashboard for business decision-making

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and calculations
- **Data Modeling** – Relationships and analytical model
- **CSV Dataset** – Source data

---

## 📊 Dashboard Pages

### 1. Executive Overview

Provides a high-level summary of the business.

Key metrics include:

- Total Revenue
- Average Order Value
- Total Sellers
- Total Products
- Total Customers
- Total Orders
- Monthly Revenue Trend

---

### 2. E-Commerce Sales & Operations Analysis

This page focuses on sales and operational performance.

Visualizations include:

- Revenue by Category
- Revenue by Seller State
- Orders by Payment Type
- Orders by Delivery Status

Interactive filters are also provided for:

- Seller State
- Payment Type

---

### 3. Seller & Product Performance

This page focuses on seller and product performance.

Visualizations include:

- Top 10 Seller Cities by Revenue
- Top Categories by Revenue
- Revenue vs Units Sold by Category
- Seller Performance Overview

---

## 📈 Key Insights

Some important observations from the analysis include:

- **Health & Beauty** is one of the strongest product categories by revenue.
- **São Paulo** generates significantly higher seller revenue compared with other seller states/cities.
- **Credit Card** is the dominant payment method.
- The majority of orders are delivered **On Time**.
- A small number of seller cities contribute a significant portion of total revenue.
- Higher units sold generally correspond to higher revenue, although performance varies across categories.

---

## 🔄 Data Analysis Workflow

```text
Raw Dataset
     ↓
Data Cleaning & Transformation
     ↓
Power Query
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
Interactive Power BI Dashboard
     ↓
Business Insights
📁 Project Structure
E-Commerce-Sales-Operations-Analysis/
│
├── Dashboard/
│   └── E-Commerce_Sales_Operations_Analysis.pbix
│
├── Dashboard_Screenshots/
│   ├── executive-overview.png
│   ├── sales-operations.png
│   └── seller-product-performance.png
│
├── dataset/
│   └── dataset files
│
└── README.md

🚀 How to Use
Download or clone this repository.
Open the .pbix file from the Dashboard folder using Power BI Desktop.
If required, update the dataset file path in Power Query.
Refresh the data.
Use the filters and interactive visuals to explore the analysis.

💡 Business Value

This dashboard can help business stakeholders:

Monitor revenue performance
Identify high-performing categories
Evaluate seller performance
Understand customer and order activity
Analyze payment preferences
Monitor delivery performance
Identify areas requiring operational improvement


👨‍💻 Author

Manas Thakre

Data Analytics | Power BI | SQL | Data Visualization


⭐ Project

If you find this project useful, feel free to explore the repository and dashboard.
### 3. Save README

After pasting:

**Ctrl + S**

Then PowerShell:

```powershell
git add README.md
git commit -m "Improve project README"
git push