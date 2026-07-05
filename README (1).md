# 📊 Ecommerce Sales Analysis Dashboard

An interactive Excel dashboard that analyzes ecommerce sales performance across categories, sub-categories, regions, and time — giving a complete view of sales, profit, and order trends to support data-driven business decisions.

![Dashboard Overview](screenshots/dashboard-overview.png)

---

## 📌 Overview

This dashboard consolidates raw ecommerce transactional data into a single-page executive view, tracking key business metrics (Sales, Profit, Quantity, Orders, Profit Margin) alongside their year-over-year growth trends. Built entirely in **Excel** using PivotTables, PivotCharts, and slicers, it enables stakeholders to drill down into performance by category, sub-category, state, and customer segment interactively.

## ✨ Features

- 📈 **KPI Summary Cards** — Sales, Profit, Quantity, Number of Orders, and Profit Margin with YoY growth sparklines
- 📊 **Sales & Profit Analysis** — Monthly trend of sales (bar) vs. profit (line) across the year
- 🗂️ **Category-Wise Profit** — Compares profit increase/decrease across Furniture, Office Supplies, and Technology
- 🍩 **Category-Wise Sales Share** — Donut chart showing percentage contribution of each category to total sales
- 🏆 **Top 5 Sub-Categories by Sales** — Ranked horizontal bar chart (Copiers, Tables, Chairs, Phones, Machines)
- 🗺️ **Sales by State** — Map chart visualizing sales distribution across the US
- 🎛️ **Interactive Filters** — Slicers for Year, Region, and Customer Segment

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Dashboard & Visualization | Microsoft Excel (PivotTables, PivotCharts, Map Charts) |
| Data Modeling | Excel Power Query, Power Pivot |
| Data Source | Excel (.xlsx) ecommerce transactional dataset |

## 📂 Project Structure

```
ecommerce-sales-dashboard/
├── EcommerceSalesDashboard.xlsx   # Main Excel dashboard file
├── data/                          # Source dataset(s) used in the dashboard
├── screenshots/
│   └── dashboard-overview.png
├── .gitignore
├── requirements.md
├── LICENSE
└── README.md
```

> **Note:** Add your `.xlsx` dashboard file and source dataset to the project root / `data` folder before pushing to GitHub — see `requirements.md` for setup details.

## 🚀 Getting Started

1. Install **Microsoft Excel** (see `requirements.md` for version details).
2. Clone this repository:
   ```bash
   git clone https://github.com/LokavarapuGovindu1/ecommerce-sales-dashboard.git
   cd ecommerce-sales-dashboard
   ```
3. Open `EcommerceSalesDashboard.xlsx` in Excel.
4. If prompted, enable data connections/macros and refresh all PivotTables (**Data → Refresh All**).
5. Use the **Year**, **Region**, and **Segment** slicers on the right to explore the data interactively.

## 📊 Key Insights Captured

- Total sales of **$22,97,200.86** across **37,873** units sold
- Category-wise sales split: **Technology 52.93%**, **Office Supplies 21.39%**, **Furniture 25.68%**
- **Copiers** lead as the top-performing sub-category by sales, followed by Tables and Chairs
- Regional sales concentration visualized via the interactive US state map

## 🧗 Challenges & Learnings

- Structured multiple KPI cards with sparkline trends and calculated fields for YoY growth.
- Used Power Query to clean and transform raw transactional data before building PivotTable relationships between categories, regions, and time.
- Balanced visual density on a single-page dashboard while keeping it readable and interactive through slicers.

## 🔮 Future Improvements

- [ ] Add a dedicated sheet for customer segment-level deep dive
- [ ] Add trendline/forecasting for future sales using Excel's forecast sheet
- [ ] Fix outstanding `#REF!` errors in YoY growth calculations
- [ ] Convert to a Power BI version for live web sharing

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Connect

**Lokavarapu Govindu**
[LinkedIn](https://linkedin.com/in/lokavarapugovindu) • [GitHub](https://github.com/LokavarapuGovindu1)
