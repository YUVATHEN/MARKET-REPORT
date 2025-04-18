# 📊 Market Report

This Power BI project analyzes sales performance for Maven Market using historical transaction data from 1997–1998. It involved complete data preparation, modeling, and interactive reporting, following best practices in business intelligence.

## 🔧 Data Transformation (Power Query)
- Connected and transformed 7+ CSV files, including Customers, Products, Stores, Calendar, Returns, and Transactions (1997 & 1998).
- Performed column merges, calculated fields, conditional logic, and null replacements.
- Applied consistent data types and region-specific formatting (English - United States).
- Used grouping, statistical tools, and cleanup to prepare a clean, analysis-ready dataset.

## 🧹 Data Modeling
- Designed a star schema with lookup tables (Customers, Products, Stores, Calendar, Regions) and fact tables (Transactions, Returns).
- Ensured all relationships had proper cardinality (1:*), single filter direction, and no bi-directional ambiguity.
- Created inactive relationships for advanced time intelligence.
- Hid unnecessary fields for a cleaner Report View.

## 🧠 DAX Calculations
- Created calculated columns (e.g., Current Age, Price Tier, Years Since Remodel).
- Built over 15 custom measures including:
  - 🛆 Quantity Sold / Returned
  - 💵 Total Revenue, Cost, Profit, and Profit Margin
  - 🔁 Return Rate
  - 📈 YTD & Rolling 60-Day Revenue
  - 🎯 Revenue Targets and Last Month Comparisons

## 📊 Report Building
- Interactive matrix visual to explore performance by product brand.
- KPI cards for Current Month Transactions, Profit, and Returns with dynamic targets.
- Geo-mapping of transactions by city and country with drill-downs and slicers.
- Time-series analysis via column charts for weekly revenue trends.
- Gauge visual for Revenue vs. Target comparison.
- Bookmarks and buttons for storytelling (e.g., Portland hits 1,000 sales in Dec).
- Conditional formatting, Top N filtering, and rich UX features for storytelling.

## 📌 Key Insights
- **Total Transactions:** 113,668
- **Total Profit:** $449,627
- **Average Profit Margin:** 59.94%
- **Return Rate:** 1.00%
- **Current Month Profit:** $71,682 vs Goal $67.87K (+5.6%)

