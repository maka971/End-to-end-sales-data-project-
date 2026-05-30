# 📊 End-to-End Sales Analytics | Power BI

> Transforming raw sales data into actionable business intelligence through an interactive Power BI dashboard.

---

## 🧭 Overview

This project demonstrates a complete end-to-end Sales Analytics solution built using **Power BI**, **SQL**, **Excel**, and advanced data modeling techniques. The goal was to give stakeholders a centralized, real-time view of sales performance — eliminating manual reporting and enabling faster, data-driven decisions.

---

## 🎯 Business Objective

Stakeholders needed a single dashboard to monitor performance across regions, products, customer segments, and sales reps. Key KPIs required:

- Revenue growth & profit margins
- Sales trends over time
- Customer behavior & segmentation
- Product and regional performance

---

## ❓ Stakeholder Questions Answered

| # | Question |
|---|----------|
| 1 | What are total sales, profit, and order volumes over time? |
| 2 | Which products and categories generate the highest revenue and profit? |
| 3 | Which regions and markets are performing best and worst? |
| 4 | Who are the top-performing sales representatives? |
| 5 | What are the monthly and yearly sales trends? |
| 6 | Which customer segments contribute the most revenue? |
| 7 | Are there declining products or underperforming regions needing attention? |

---

## 🛠️ Tools & Technologies

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## 🧹 Data Preparation & Modeling

- Imported raw sales data from multiple sources
- Cleaned and transformed data using **Power Query**
- Removed duplicates, handled missing values, standardized formats
- Built a **Star Schema** data model for optimal performance
- Established relationships between fact and dimension tables

### 📐 DAX Measures Developed

| Measure | Description |
|---------|-------------|
| Total Sales | Aggregate revenue across all transactions |
| Total Profit | Net profit after deducting costs |
| Profit Margin % | Profitability ratio per product/region |
| Year-over-Year Growth | Revenue comparison across years |
| Average Order Value | Mean revenue per order |
| Customer Lifetime Value | Long-term customer revenue contribution |

---

## 📊 Dashboard Features

### 🗂️ Executive Summary
- Total Revenue, Profit, and Orders
- Profit Margin % and Sales Growth %

### 📈 Sales Performance Analysis
- Monthly and yearly sales trends
- Revenue by region and country
- Product category performance
- Top-selling products

### 👥 Customer Analysis
- Customer segmentation breakdown
- Revenue contribution by customer type
- Repeat customer analysis

### 🏆 Sales Team Performance
- Revenue by sales representative
- Target achievement tracking
- Top and bottom performer identification

### 🗺️ Geographic Analysis
- Interactive maps for regional sales distribution
- Market performance comparison

---

## 🔍 Key Findings

### 1. 💰 Revenue Concentration
A small number of products generated the majority of total revenue — indicating heavy dependency on a limited portfolio.

### 2. 🌍 Regional Performance Gap
Certain regions consistently outperformed others, revealing opportunities to replicate winning strategies across underperforming markets.

### 3. 📅 Seasonal Sales Patterns
Sales peaked during specific months, highlighting seasonal demand trends useful for inventory and marketing planning.

### 4. 👤 Customer Value Distribution
A small percentage of customers contributed a significant share of total revenue — underscoring the importance of targeted retention efforts.

### 5. 📉 Profitability Variations
Several high-revenue products delivered low profit margins, pointing to pricing inefficiencies or cost-management opportunities.

---

## 💡 Business Recommendations

| Area | Recommendation |
|------|----------------|
| **Product Strategy** | Focus marketing on high-margin products; review pricing for low-profit, high-volume items |
| **Regional Performance** | Investigate top-performing regions and replicate strategies in lagging markets |
| **Customer Retention** | Build loyalty programs for high-value customers; increase engagement with repeat buyers |
| **Sales Forecasting** | Use historical trends and seasonality for accurate demand forecasting |
| **Team Performance** | Set KPI benchmarks; provide coaching to underperforming reps |

---

## 📌 Business Impact

| Before | After |
|--------|-------|
| Manual, time-consuming reporting | Real-time automated dashboard |
| Siloed data across teams | Centralized single source of truth |
| Reactive decision-making | Proactive, data-driven strategy |
| Limited visibility into trends | Full trend analysis and forecasting |

---

## 📁 Project Structure

```
sales-analytics-powerbi/
│
├── 📂 data/
│   ├── raw/               # Original source data
│   └── processed/         # Cleaned and transformed data
│
├── 📂 dashboard/
│   └── SalesAnalytics.pbix  # Main Power BI file
│
├── 📂 sql/
│   └── queries.sql          # SQL scripts used for data extraction
│
├── 📂 docs/
│   └── data_dictionary.md   # Column definitions and schema overview
│
└── README.md
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/sales-analytics-powerbi.git
   ```

2. **Open the `.pbix` file** in Power BI Desktop

3. **Connect your data source** via Power Query (update connection strings as needed)

4. **Refresh the data** and explore the dashboard

---

## 📬 Contact

Feel free to connect or reach out for collaboration opportunities:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)][([https://linkedin.com/in/your-profile](https://www.linkedin.com/in/mutyaba-sulah-525510203/))



---

*Built as part of a data analytics portfolio. Open to feedback and collaboration.*
