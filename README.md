Adidas Sales Performance Dashboard
<img width="1549" height="640" alt="Screenshot 2026-02-13 155240" src="https://github.com/user-attachments/assets/55da92b3-03b9-40b7-9ad6-c284a00b6316" />

An interactive Excel-based sales analytics dashboard for Adidas, visualizing revenue trends, product performance, and regional distribution across global markets in 2024.
 Dashboard Overview
The dashboard provides a comprehensive view of Adidas sales data through dynamic charts and KPI cards, with month-based filtering for time-period analysis.
Key Metrics (2024)
MetricValueTotal Revenue₹5,073,981,028Total Units Sold762,533Average Discount14.985%

📁 Project Structure
adidas_sales/
│
├── adidas_sales.xlsx          # Main workbook with raw data + dashboard
│   ├── Sheet1                 # Raw transaction data
│   └── Dashboard              # Pivot-based interactive dashboard
│
└── README.md                  # Project documentation

📋 Dataset
The dataset (Sheet1) contains individual sales transactions with the following columns:
ColumnDescriptionProduct_IDUnique identifier for each transaction (e.g., A0001)Product_NameName of the product (e.g., Gym Bag, Ultraboost, Samba)CategoryProduct category — Accessories, Apparel, or ShoesPrice_INRUnit price in Indian RupeesUnits_SoldNumber of units sold in the transactionDiscount_%Discount applied (ranging from 5% to 25%)RevenueNet revenue after discountRegionSales region (Australia, Canada, Germany, India, UK, USA)Sales_DateDate of transaction (YYYY-MM-DD format)MonthAbbreviated month name (Jan–Dec)

📈 Dashboard Visualizations
1. Monthly Sales Trend (Line Chart)
Tracks total revenue month-over-month from January to December 2024. Helps identify seasonal peaks and dips across the year.
2. Category Wise Revenue (Bar Chart)
Compares total revenue across the three product categories:

Accessories — ₹1,825,246,783
Apparel — ₹1,675,386,692
Shoes — ₹1,573,347,553

3. Top 10 Products (Horizontal Bar Chart)
Ranks the top-performing products by revenue. Highlights include Training Tank, Headband, and Gym Bag as top earners.
4. Region Wise Revenue (Pie Chart)
Shows revenue distribution across six global regions: Australia, Canada, Germany, India, UK, and USA.
5. Month Slicer (Interactive Filter)
A panel on the right allows filtering all charts by selecting one or more months (Jan–Dec), enabling focused time-period analysis.

Tools Used

Microsoft Excel — PivotTables, PivotCharts, Slicers, and conditional formatting
Data Source — Synthetic Adidas sales transaction data (2024)


How to Use

Open adidas_sales.xlsx in Microsoft Excel (2016 or later recommended).
Navigate to the Dashboard sheet.
Use the Month slicer on the right side to filter data by specific months.
All charts update dynamically based on the selected filter.


 Notes

All prices and revenues are in Indian Rupees (INR).
The dataset covers the full calendar year 2024.
Regions covered: Australia, Canada, Germany, India, UK, USA.
Product categories: Accessories, Apparel, Shoes.
Discounts range from 5% to 25% across transactions.
ShareContentadidas_sales_ (1).xlsxxlsx
