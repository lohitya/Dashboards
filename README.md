# Power BI Dashboards – Sales, Product, Consumer, and Order Fulfillment

📊 Overview
This repository showcases a suite of Power BI dashboards built using a transactions dataset. The aim is to generate actionable business insights across sales performance, product profitability, customer behavior, and store operations. The dashboards combine interactive visuals, calculated measures and columns, and professional design to support data-driven decision-making.

#  1. Sales Dashboard
KPIs:

    Total Sales
    
    Profit
    
    Total Orders
    
    Quantity Sold
    
    Total Customers
    
    Average Delivery Time

Visuals:

    Sales & Profit by Continent (Line Chart)
    
    Sales Growth % by Year (Line Chart, using calculated field and date table)
    
    Profit by Year (Line Chart)
    
    Sales & Profit by Category (Bar Chart)
    
    Country-wise Sales, Profit, Quantity (Matrix)

Slicers:

- Order Date

- Product Category

- Store Type (Online, Physical)

- Continent

- Country

Analysis:
This dashboard tracks store performance over time and across geographies. It highlights profitability trends, year-over-year growth, and category-level performance using a custom date table and DAX-based calculated fields.

# 2. Product Dashboard

KPIs:

    Average Cost (Measure)
    
    Average Price (Measure)
    
    Average Delivery Days (Measure)
    
    Total Sales
    
    Profit
    
    Quantity Sold

Visuals:

    Sales, Profit & Quantity by Category and Sub-Category (Matrix)
    
    Total Profit (Grand Total - Matrix)
    
    Sales by Product Brand (Tree Map)
    
    Product Profitability (Scatter Plot: Avg Cost vs. Avg Price, with reference lines)
    
    Top 5 / Bottom 5 Products by Sales (Column Chart, includes Profit and Quantity)

Slicers:

- Top 5 / Bottom 5 Products (Created using a Calculated Column),

Order Date

Analysis:
The Product Dashboard delivers deep insights into pricing, sales volume, and product-level profitability. The scatter plot enables pricing efficiency analysis, while dynamic segmentation highlights both bestsellers and underperforming products.

# 3. Consumer Dashboard

KPIs:

    Total Sales
    
    Total Profit
    
    Average Order Value (AOV)
    
    Total Customers
    
    Number of Orders
    
    Average Delivery Time

Slicers:

- Age Group,
  
- Store Type,
  
- Order Date,
  
- Customer Continent,
  
- Customer Gender

Visuals:

    Sales % by Continent (Column Chart)
    
    Sales by Gender (Column Chart)
    
    Customer Type (New vs. Returning - Column Chart)
    
    Sales by Age Group (Created using a Calculated Column)
    
    Country-wise Sales, Profit, and Orders (Matrix)

Analysis:
This dashboard explores consumer patterns by demographics and geography. Age groups and customer type (new/returning) are derived using calculated columns, enabling segmentation for marketing and retention strategies.

# 4. Order Fulfillment & Store Performance Dashboard

KPIs:

    Total Sales
    
    Profit
    
    Number of Orders
    
    Quantity Sold
    
    Average Order Value
    
    Total Customers

Slicers:
- Store Country,

- Order Date

Visuals:

    Orders by Year (Line Chart using Date Table)
    
    Orders by Store Type (Donut Chart – Online vs. Physical)
    
    Orders by Delivery Status (Donut Chart using Calculated Column)
    
    New Store Sales Performance (Based on "Months Since Opening" - Calculated Column)
    
    Customer Type (Returning vs. New - Column Chart using Calculated Column)

Analysis:
This dashboard evaluates store performance by format and delivery efficiency. It segments customers and identifies growth in new store performance, aiding operational and marketing strategy.

# 💼 Business Summary
This BI project analyzes transactional data across key business areas, aiming to support data-informed decisions:

✅ 1. Understand Store Performance
The Sales Dashboard evaluates store performance by continent and year, highlights profitable product categories, and visualizes year-on-year growth.

✅ 2. Evaluate Product Performance & Profitability
The Product Dashboard pinpoints top 5 and bottom 5 products by sales and highlights high-performing brands. A scatter plot visualizes each product’s average cost vs. average price, helping spot underpriced or overpriced products. 

✅ 3. Analyze Consumer Behavior
The Consumer Dashboard segments customers by gender, age group, and type (new vs. returning), providing insights for personalized engagement strategies.

✅ 4. Monitor Order Fulfillment & Store Operations
The Order Fulfillment Dashboard tracks delivery status, evaluates new store performance, and distinguishes between physical and online store performance.

