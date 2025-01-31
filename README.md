# Dashboards_PowerBi
📊 Power BI Sales Analysis Dashboard

Overview

This project focuses on cleaning, analyzing, and visualizing a sales dataset using Power BI. The goal is to extract meaningful insights and enhance decision-making through interactive dashboards.

🔹 Data Cleaning Steps

Removed missing values from critical columns (InvoiceNo, StockCode, InvoiceDate).

Replaced missing CustomerID values with "Unknown".

Converted data types (Quantity → Integer, InvoiceDate → Date/Time).

Removed duplicate records for data accuracy.

📊 Data Analysis & Visualization

DAX Measures Used:

Total Sales: SUMX(Quantity * UnitPrice)

Total Orders: DISTINCTCOUNT(InvoiceNo)

Average Order Value (AOV): Total Sales / Total Orders

Customer Count: DISTINCTCOUNT(CustomerID)

Visuals Created:

Pie Chart – Sales distribution by top products & customers

Bar Chart – Monthly sales trends

KPI Cards – Key metrics (Total Sales, Orders, AOV, Customer Count)

Table View – Invoice-wise breakdown

Themes & Customization:

Applied a custom color theme for enhanced readability.

Used data labels & sorting for better insights.

🔍 Key Insights

Identified top-selling products contributing the highest revenue.

Analyzed customer segmentation based on purchasing patterns.

Visualized sales trends across months & regions.

🚀 Conclusion

This project demonstrates the power of Power BI in transforming raw data into actionable insights. The use of DAX, interactive visuals, and custom themes enhances the analytical capabilities of the dashboard.

📢 Feel free to contribute, suggest improvements, or share your thoughts!

#PowerBI #DataAnalytics #DataCleaning #DAX #DataVisualization

