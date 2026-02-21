# 📊 Sales & Customer Performance Dashboard

[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)](https://www.tableau.com/)

Interactive **Tableau dashboards** for analyzing year-over-year sales performance, product trends, and customer behavior. Enables sales managers and executives to make data-driven decisions on inventory, marketing, and customer retention.

---

## 🖼️ Dashboard Previews

| Sales Dashboard | Customer Dashboard |
|:---------------:|:------------------:|
| ![Sales Dashboard](Sales%20Dashboard.png) | ![Customer Dashboard](Customer%20Dashboard.png) |

*Click images to enlarge.*

---

## 💡 Key Insights

- **Sales:** $733K ▲20.4% YoY | **Profit:** $93K ▲12.5% | **Quantity:** 12K ▲26.8%
- **Top subcategories:** Phones & Chairs drive highest volume.
- **Customer loyalty gap:** 60%+ are one‑time buyers → re‑engagement opportunity.
- **Top 10 customers** generate $30K+ profit → assign account managers.
- **Orders grew 28.3%** vs customers (8.6%) – existing buyers are purchasing more frequently.
- Weekly averages: Sales $14K, Profit $2K – weeks below average need investigation.

---

## ⚙️ Key Features

- **Dynamic year selection** – parameter‑driven (2020‑2023) for instant YoY comparison.
- **Global filters** – drill down by product category, subcategory, region, state, city.
- **Cross‑filtering** – click any chart to highlight related data across dashboards.
- **Modular KPI tiles** – sparklines with min/max highlights and YoY % change.
- **Above/below average flags** – quickly spot weekly performance outliers.

---

## 🛠️ Tech Stack

- **Visualization:** Tableau Desktop – parameters, calculated fields, LOD expressions, dashboard actions
- **Data Source:** EU sales data (CSV files)

---

## 📁 Dataset

The dataset consists of four CSV files in a star schema:

- **Orders.csv** – fact table with sales, profit, quantity, order dates
- **Customers.csv** – customer demographics
- **Location.csv** – geographic data (region, state, city)
- **Products.csv** – product categories and subcategories

The `.twbx` file includes an extract of this data.

---

## 📂 Repository Structure

```
├── Datasets/
│   ├── Customers.csv
│   ├── Location.csv
│   ├── Orders.csv
│   └── Products.csv
├── Sales Dashboard.png
├── Customer Dashboard.png
├── Sales & Customer Dashboards.twbx
└── README.md
```


**#Tableau #DataVisualization #SalesAnalytics #CustomerAnalytics #KPI #Dashboard**
