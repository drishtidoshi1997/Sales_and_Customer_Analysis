# 📊 Sales & Customer Performance Dashboard

[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)](https://www.tableau.com/)
[![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)]()

Interactive **Tableau dashboards** for analyzing year-over-year sales performance, product trends, and customer behavior. Enables sales managers and executives to make data-driven decisions on inventory, marketing, and customer retention.

---

## 🖼️ Dashboard Previews

| Sales Dashboard | Customer Dashboard |
|:---------------:|:------------------:|
| ![Sales Dashboard](Sales%20Dashboard.png) | ![Customer Dashboard](Customer%20Dashboard.png) |

*Click images to enlarge.*

---

## 💡 Key Insights

- **Sales grew 20.4%** to $733K, but profit growth lagged at **12.5%** – margin review needed.
- **Phones** and **Chairs** are top-performing subcategories – prioritize inventory and marketing.
- **60%+ of customers are one-time buyers** – massive re-engagement opportunity.
- **Top 10 customers generate $30K+ profit** – assign dedicated account managers.
- **Orders grew 28.3%** vs customer growth of 8.6% – existing customers buying more frequently.
- Weekly sales average **$14K**, profit average **$2K** – investigate weeks below average.

---

## 🛠️ Tech Stack

- **Data Source:** EU sales data (Orders, Customers, Location, Products)
- **Visualization:** Tableau Desktop – parameters, calculated fields, LOD expressions, dashboard actions
- **Data Processing:** Excel for initial data preparation

---

## 📁 Dataset

The dataset contains multiple tables in a star schema:

- **Orders** – fact table with sales, profit, quantity, order dates
- **Customers** – customer demographics
- **Location** – geographic data (region, state, city)
- **Products** – product categories and subcategories

Key measures: `Sales`, `Profit`, `Quantity`, `Order Count`, `Customer Count`

---

## 📂 Repository Structure

```
├── Sales Dashboard.png                    # Sales dashboard preview
├── Customer Dashboard.png                  # Customer dashboard preview
├── EU_Sales_Data/                          # Data source files (CSV)
│   ├── Orders.csv
│   ├── Customers.csv
│   ├── Location.csv
│   └── Products.csv
├── Sales_Customer_Dashboard.twbx           # Tableau workbook
└── README.md                                # This file
```

---

## 🚀 Getting Started

1. Clone the repository.
2. Open `Sales_Customer_Dashboard.twbx` in Tableau Desktop.
3. Use the year parameter (default 2023) to explore different time periods.
4. Interact with filters (product category, subcategory, region, state, city) to drill down.

---

## 📬 Contact

For questions or feedback, please open an [issue](../../issues) or reach out directly.

---

**#Tableau #DataVisualization #SalesAnalytics #CustomerAnalytics #KPI #Dashboard**
