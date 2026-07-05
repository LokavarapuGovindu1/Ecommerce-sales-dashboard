# Requirements

This project is built entirely in **Microsoft Excel** — there are no Python/code dependencies to install. Below are the software and data requirements needed to open and run this dashboard.

## Software

| Requirement | Version / Notes |
|---|---|
| Microsoft Excel | Excel 2016 or later recommended (for full PivotTable, slicer, and Map Chart support) |
| Operating System | Windows or macOS (Map Chart feature requires Excel 2016+ with an internet connection for Bing map data) |
| Microsoft 365 (optional) | Recommended for the smoothest experience with slicers and dynamic PivotCharts |

## Data Source

- The dashboard expects an ecommerce transactional dataset (Excel `.xlsx` or CSV) containing fields such as:
  - Order Date, Ship Date
  - Sales, Profit, Quantity
  - Category, Sub-Category
  - Region, State, Segment
  - Order ID / Order Count
- Place your dataset inside the `data/` folder. If the PivotTables show blank or outdated values, update the data source range via **PivotTable Analyze → Change Data Source**.

## Opening the Project

1. Ensure Microsoft Excel is installed.
2. Open `EcommerceSalesDashboard.xlsx`.
3. If prompted to enable content/macros or external data connections, click **Enable**.
4. Go to **Data → Refresh All** to reload the latest data into all PivotTables and charts.

## Notes

- The **Sales by State** map chart requires an active internet connection the first time it renders (it uses Bing/TomTom map data).
- If you see `#REF!` errors on any KPI card, check that the corresponding cell formulas/calculated fields still reference valid ranges after any data updates.
- Slicers are linked to specific PivotTables — if you add new PivotTables, connect them to existing slicers via **Slicer → Report Connections**.
