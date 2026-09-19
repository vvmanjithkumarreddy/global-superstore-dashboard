# Global Superstore Sales Dashboard

Three-page Power BI dashboard analyzing sales, profit, and delivery performance across the Global Superstore dataset.

## Overview
- **Dataset**: Global Superstore (orders, sales, profit, delivery, customer, and regional data)
- **Tools**: Power BI, Power Query, DAX
- **Objective**: Track sales/profit against target, break down performance by region/market/delivery type, and surface country-level geographic patterns

## Pages

### 1. Sales Overview
KPI cards (Sales, Profit, Orders, Customers), monthly Sales/Profit trend, Sales Target KPI with a Profit-vs-Target gauge, Profit and Sales by Market, Category/Segment slicers.
![Sales Overview](screenshots/01-sales-overview.png)

### 2. Category & Regional Breakdown
Total Sales by Year, Orders by Delivery Type, Sales by Region, Orders by Delivery Status.
![Category and Regional Breakdown](screenshots/02-category-regional-breakdown.png)

### 3. Geographic Analysis
Total Profit by Country and Total Sales by Country, plotted on maps.
![Geographic Analysis](screenshots/03-geographic-analysis.png)

## Key Insights
- [Fill in: which region/market drives the most profit vs. sales]
- [Fill in: how delivery status/type affects order volume]
- [Fill in: whether the sales target is being met]

## Data Modeling Notes
- Custom fields (`order_day_type`, `delivery_status`) derived for delivery performance analysis
- Filters applied at report level on Country and Market

## How to Explore
Download `dashboard/global_superstore.pbix` and open in Power BI Desktop, or view the screenshots above for a static walkthrough.
