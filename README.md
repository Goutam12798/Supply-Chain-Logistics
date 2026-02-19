Supply Chain Analytics Dashboard

📌 Problem Statement

This dashboard helps the organization monitor and optimize its end-to-end supply chain operations including supplier performance, inventory levels, shipment efficiency, customer delivery performance, and revenue generation.

The objective of this project is to:

Analyze gross revenue, total revenue, and profit margins

Monitor inventory stock levels and inventory value

Track shipment quantity and delivery performance

Evaluate supplier performance based on lead time

Identify delay-prone shipment carriers

Measure perfect order percentage

Provide operational insights for improving supply chain efficiency

Since supply chain efficiency directly impacts revenue and customer satisfaction, this dashboard enables business leaders to:

Detect shipment delays and bottlenecks

Improve supplier lead time management

Optimize inventory stock levels

Monitor customer delivery performance

Increase overall profit margins

🛠️ Steps Followed
Step 1: Data Import

Imported raw supply chain dataset (CSV format) into Power BI Desktop.

Dataset includes:

Supplier information

Inventory details

Shipment data

Customer data

Revenue & Profit metrics

Step 2: Data Profiling & Cleaning

Opened Power Query Editor.

Enabled:

Column Distribution

Column Quality

Column Profile

Handled null values and corrected data types.

Removed duplicate and inconsistent records.

Step 3: Data Modeling

Created relationships between:

Supplier Table

Inventory Table

Shipment Table

Customer Table

Built star schema for optimized reporting.

Step 4: KPI Measures (DAX)

Created calculated measures for:

Gross Revenue

Total Revenue

Total Profit

Profit Margin %

Perfect Order %

Order Quantity

Shipment Quantity

Delivered Quantity

Inventory Value

Step 5: KPI Cards Added

Displayed key business metrics using Card visuals:

💰 Gross Revenue → 186.86M

💰 Total Revenue → 176.95M

💰 Total Profit → 48.56M

📊 Profit Margin → 27.44%

🎯 Perfect Order % → 75.29%

📦 Total Shipments → 8K

📦 Order Quantity → 129K

🏬 Inventory Value → 160K

🚚 Shipment Quantity → 3M

✅ Delivered Quantity → 187K

Step 6: Visualizations Implemented
📊 Bar Charts

Supplier by Average Lead Time

Inventory Stock by Product

Total Delay Shipments by Carrier

Total Revenue by Customer

🍩 Donut Charts

Order Quantity Distribution

Inventory Value Distribution

Shipment Quantity Distribution

Delivered Quantity Distribution

📈 Trend Analysis

Revenue contribution by major customers (Amazon, Flipkart, Best Buy, Samsung, etc.)

Step 7: Dashboard Design

Implemented dark theme professional UI

Structured into 4 operational segments:

Supplier

Inventory

Shipment

Customer

Used clear KPI segmentation for executive overview

Step 8: Publishing

Published report to Power BI Service

Enabled sharing and report access for stakeholders

📊 Insights

1️⃣ Revenue & Profitability Insights

Gross Revenue generated: 186.86M

Total Revenue: 176.95M

Total Profit: 48.56M

Profit Margin: 27.44%

👉 The company is maintaining a healthy profit margin, but revenue leakage between gross and net revenue should be analyzed further.

2️⃣ Supplier Performance

Average lead time varies across suppliers.

Some suppliers show consistently higher lead times, indicating potential delay risks.

Supplier performance directly impacts shipment delays and inventory availability.

3️⃣ Inventory Insights

Total Inventory Value: 160K

Certain products hold higher stock quantities (e.g., Galaxy series).

Overstock and slow-moving inventory can affect working capital.

4️⃣ Shipment & Delivery Performance

Shipment Quantity: 3M

Delivered Quantity: 187K

Perfect Order %: 75.29%

👉 Nearly 25% of orders are not perfectly delivered, indicating improvement areas in logistics.

5️⃣ Delay Analysis

Some carriers (e.g., Maersk, DHL, DB Schenker, FedEx) show higher delay counts.

Carrier performance monitoring can reduce operational disruptions.

6️⃣ Customer Revenue Insights

Top revenue-generating customers:

Amazon

Flipkart

Best Buy

MediaMart

Samsung

👉 Revenue concentration risk exists if dependency on top customers is high.

🎯 Business Recommendations

Improve supplier selection strategy based on lead time performance

Monitor delay-prone logistics carriers

Optimize inventory levels to reduce holding costs

Increase perfect order percentage above 85%

Diversify revenue across customers to reduce dependency risk

🧰 Tools & Technologies Used

Power BI

Power Query

DAX

Data Modeling (Star Schema)

Power BI Service

🚀 Conclusion

This Supply Chain Dashboard demonstrates the ability to:

Build end-to-end business intelligence solutions

Transform raw operational data into actionable insights

Design executive-level KPI dashboards

Perform operational performance analysis
