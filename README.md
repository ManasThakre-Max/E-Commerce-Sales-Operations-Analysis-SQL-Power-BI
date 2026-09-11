# 📊 E-Commerce Sales & Operations Analysis

Interactive Power BI dashboard analyzing sales performance, seller operations, payment behavior, and delivery efficiency for a large e-commerce dataset.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📋 Overview

This project analyzes the **Brazilian E-Commerce Public Dataset by Olist**, covering orders, customers, sellers, products, payments, and reviews. Raw transactional data was cleaned and modeled in Power Query, then transformed into a 3-page interactive Power BI dashboard to surface actionable business insights across sales, sellers, and delivery operations.

**Goals:**
- Track revenue and order trends over time
- Identify top-performing product categories and seller regions
- Analyze customer payment preferences
- Evaluate delivery performance
- Build a self-serve dashboard for business decision-making

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard design & visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Calculated measures & KPIs |
| **Data Modeling** | Relationships across orders/customers/sellers/products |

---

## 📁 Dataset

**Source:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Includes: orders, customers, sellers, products, payments, reviews, product categories, delivery details, and geolocation data.

---

## 📌 Dashboard Pages

### 1️⃣ Executive Overview
High-level snapshot of business health.
- **KPIs:** Total Revenue · Avg. Order Value · Total Sellers · Total Products · Total Customers · Total Orders
- **Visuals:** Monthly revenue trend, overall performance indicators

![Executive Overview](Dashboard_Screenshots/executive-overview.png)

### 2️⃣ Sales & Operations Analysis
Deep dive into sales performance and operational metrics.
- **Visuals:** Revenue by category, revenue by seller state, orders by payment type, orders by delivery status
- **Interactive filters:** Seller State, Payment Type

![Sales & Operations Analysis](Dashboard_Screenshots/sales-operations.png)

### 3️⃣ Seller & Product Performance
Seller- and category-level performance breakdown.
- **Visuals:** Top 10 seller cities by revenue, top categories by revenue, revenue vs. units sold by category, seller performance table (city, state, revenue, orders, units sold)

![Seller & Product Performance](Dashboard_Screenshots/seller-product-performance.png)

---

## 💡 Key Insights

- A small number of product categories drive a disproportionate share of revenue.
- Seller performance varies significantly by location — **São Paulo** is the strongest market.
- **Credit cards** are the dominant payment method among customers.
- The majority of orders were delivered on time.
- Monthly revenue and order trends reveal clear seasonal patterns.

---

## 🔄 Workflow

```
Raw Dataset → Data Cleaning (Power Query) → Data Modeling → DAX Measures → Interactive Dashboard → Business Insights
```

---

## 📂 Project Structure

```
E-Commerce-Sales-Operations-Analysis/
│
├── Dashboard/
│   └── E-Commerce Sales & Operations Analysis.pbix
│
├── Dashboard_Screenshots/
│   ├── executive-overview.png
│   ├── sales-operations.png
│   └── seller-product-performance.png
│
├── dataset/
│   └── E-Commerce dataset files (CSV)
│
└── README.md
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open the `.pbix` file from the `Dashboard/` folder in **Power BI Desktop**.
3. Refresh the data connections if prompted.
4. Explore all three dashboard pages using the interactive filters.

---

## 📈 Business Value

This dashboard turns raw transactional data into a decision-support tool that helps stakeholders:
- Monitor overall sales performance
- Identify high-performing categories and regions
- Compare seller performance at a glance
- Understand customer payment behavior
- Evaluate delivery reliability
- Make faster, data-driven decisions

---

## 👨‍💻 Author

**Manas Thakre**
Data Analytics · Power BI · Data Visualization

[GitHub](https://github.com/ManasThakre-Max)
