📊 Inventory & Sales Analytics Dashboard

An end-to-end data analytics project focused on transforming raw inventory and sales data into actionable business insights.  
This project analyzes product performance, inventory health, and supplier contribution to support smarter business decisions.

📌 Project Overview
This project simulates a real-world retail business scenario where inventory and sales data are analyzed to improve operational efficiency and revenue performance.
Using SQL for data preparation, Excel for initial handling, and Power BI for visualization, the dashboard provides a comprehensive view of business performance across multiple dimensions.

🎯 Objectives / Problem Statement

Businesses often struggle with:
- Stockouts leading to lost sales  
- Overstock increasing holding costs  
- Poor visibility into product performance  
- High dependency on limited suppliers  

 🎯 This project aims to:
- Identify inventory risks (low stock, overstock, dead stock)  
- Analyze product-level revenue performance  
- Evaluate supplier contribution and dependency  
- Enable data-driven decision-making
- 
 📊 Key Features / KPIs
 💰 Total Revenue  
 📦 Total Units Sold  
 ⚠️ Low Stock Count  
 📉 Overstock Count  
 🧊 Dead Stock Count  
 🏆 Top & Bottom Performing Products  
🚚Supplier Revenue Contribution  
📊 Category wise Revenue Distribution  

🛠️ Tools & Technologies Used
SQL Data cleaning, transformation, and analysis  
Excel – Data preprocessing  
Power BI – Dashboard creation and visualization  

 📂 Dataset Description
The dataset consists of:
Product Data: product name, category  
Sales Data sales volume, revenue  
Inventory Data: stock quantity, stock status  
Supplier Data: supplier name and product mapping  
This dataset enables multi-dimensional analysis across sales, inventory, and supplier performance.

🗃️ SQL Queries & Data Preparation
SQL was used to transform raw data into analysis-ready datasets and extract key business insights.
🔹 Key SQL Contributions:
- Cleaned and structured raw datasets  
- Created calculated fields for analysis  
- Identified low stock, overstock, and dead stock products  
- Aggregated revenue and sales metrics  
- Enabled efficient data modeling for Power BI
- 
🔸 Sample SQL Queries
1. Identifying Low Stock Products
sql
SELECT product_name, stock_quantity
FROM inventory
WHERE stock_quantity < 50;
<img width="856" height="404" alt="image" src="https://github.com/user-attachments/assets/7fc3642d-3d16-4eed-b171-3e19cf9f9139" />


📈 Dashboard Insights
~ Fruits & Vegetables contribute the highest share of revenue (~26%).
~ Multiple products are at risk of stock-out, impacting potential sales.
~ Overstock and dead stock items increase storage and holding costs.
~ A few suppliers contribute a large portion of revenue, indicating dependency risk.
~ Significant gap exists between top-performing and low-performing products.
💡 Key Learnings
~ Writing efficient SQL queries for data analysis
~ Data cleaning and transformation techniques
~ Building interactive dashboards in Power BI
~ Understanding business problems through data
~ Converting data into actionable insights
~ Improving data storytelling skills

📷 Dashboard Preview
<img width="889" height="500" alt="image" src="https://github.com/user-attachments/assets/d2ed5d69-6d2e-478d-9f16-fbcbd63e5134" />



🔗 Connect with Me
If you found this project interesting or have feedback, feel free to connect with me on LinkedIn.


