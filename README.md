#  Business Problem
After 2019, a consumer company began experiencing a decline in both sales and profit across all operating regions. While the business had seen steady growth in previous years, recent performance has been inconsistent and lacks clear explanation.

Leadership is increasingly concerned and wants to understand what is driving the downturn. Specifically, they lack visibility into:

    Which product categories and individual products are still performing well
    
    Which offerings are underperforming or dragging overall profitability down
    
    How customer behavior is shifting by segment, location, and order type
    
    Whether operational issues — particularly delivery delays — are affecting revenue or satisfaction?

**Business Objective**

The goal is to create an end-to-end Power BI reporting solution that:

Uncovers the root causes behind the decline

Highlights growth opportunities

Supports targeted interventions in product strategy, customer engagement, and operational improvement
    
    
#  1. Sales Dashboard
KPIs:

    Total Sales, Profit, Total Orders, Quantity Sold,Total Customers, Average Delivery Time


Insights:

Between 2019 and 2021, although overall sales steadily declined across all regions, profit margins remained strong, with all product categories generating over 50% profit relative to sales during this period.

-  This suggests that the issue is not directly tied to pricing or cost inefficiencies, but may stem from a drop in demand, market shifts, or reduced volume, especially in underperforming categories or regions.

Visuals:

    Sales & Profit by Continent (Line Chart)
    
    Sales Growth % by Year (Line Chart, using calculated field and date table)
    
    Profit by Year (Line Chart)
    
    Sales & Profit by Category (Bar Chart)
    
    Country-wise Sales, Profit, Quantity (Matrix)

Slicers:

- Order Date, Product Category,Store Type (Online, Physical),Continent, Country


# 2. Product Dashboard

KPIs:

    Average Cost (Measure), Average Price (Measure), Average Delivery Days (Measure), Total Sales, Profit, Quantity Sold

**Insights:**

Drastic Decline in Quantity Sold Post-2019:

There has been a significant drop in the quantity of products sold across all categories since 2019, which has led to a steep decline in both sales and profit — even though average prices and profit margins remained relatively stable.

This suggests that the issue is volume-driven, rather than pricing or cost-related.

Potential Contributing Factors:

- Low Product Visibility: Products may not be reaching the right audiences due to ineffective marketing or suboptimal placement on online platforms or in stores.

- Rising Market Competition: Competitor brands may have introduced more innovative or better-priced alternatives, capturing customer attention and loyalty.

- Shifting Customer Preferences: Existing product offerings may no longer align with what customers are actively seeking post-2019, especially in a fast-moving consumer electronics market.

Visuals:

    Sales, Profit & Quantity by Category and Sub-Category (Matrix)
    
    Total Profit (Grand Total - Matrix)
    
    Sales by Product Brand (Tree Map)
    
    Product Profitability (Scatter Plot: Avg Cost vs. Avg Price, with reference lines)
    
    Top 5 / Bottom 5 Products by Sales (Column Chart, includes Profit and Quantity)

Slicers:

- Top 5 / Bottom 5 Products (Created using a Calculated Column),

Order Date


# 3. Consumer Dashboard

KPIs:
 
    Total Sales, Total Profit, Average Order Value (AOV), Total Customers, Number of Orders, Average Delivery Time

**Consumer Insights**

Senior Segment Drives Sales:
The 65+ age group contributes the highest share of total sales, making them the most valuable customer segment in the current landscape.

Gender-Based Contribution:
While sales are relatively balanced, male customers show a slightly higher contribution to overall sales.

Loyal Customers = Higher Profitability:
Returning customers account for over 70% of both sales and profit, indicating strong retention but limited new customer acquisition.

Limited New Customer Growth (2019–2021):
Only 27% of customers were new during this period, highlighting a potential challenge in expanding the customer base.

Data Gap in Marketing:
No available marketing data limits the ability to assess promotional effectiveness or customer acquisition channels.

**Recommendations**

Prioritize the 65+ Segment:
Develop tailored experiences, product bundles, or loyalty programs that cater to this high-value demographic to reinforce retention and lifetime value.

Reignite New Customer Acquisition:
Conduct qualitative or survey-based research to identify what younger customers seek in electronics and why they may not be purchasing.

Build Targeted Marketing Strategies:
Invest in capturing and analyzing marketing campaign data. Use it to improve outreach to younger demographics and optimize return on marketing spend.

Slicers:

 Age Group, Store Type, Order Date, Customer Continent, Customer Gender

Visuals:

    Sales % by Continent (Column Chart)
    
    Sales by Gender (Column Chart)
    
    Customer Type (New vs. Returning - Column Chart)
    
    Sales by Age Group (Created using a Calculated Column)
    
    Country-wise Sales, Profit, and Orders (Matrix)


# 4. Order Fulfillment & Store Performance Dashboard

KPIs:

    Total Sales, Profit, Number of Orders ,Quantity Sold, Average Order Value, Total Customers

Insights:

Majority of orders(77%) are from physical stores. This shows the client needs a good online presence, brand imaging and marketing stratergy since no of oreders has been declining .

Slicers:

Store Country, Order Date

Visuals:

    Orders by Year (Line Chart using Date Table)
    
    Orders by Store Type (Donut Chart – Online vs. Physical)
    
    Orders by Delivery Status (Donut Chart using Calculated Column)
    
    New Store Sales Performance (Based on "Months Since Opening" - Calculated Column)
    
    Customer Type (Returning vs. New - Column Chart using Calculated Column)



# Executive Insights & Recommendations

- Post-2019, sales declined across all regions despite strong profit margins, pointing to demand issues rather than pricing inefficiencies.

- Product volume sold dropped significantly, suggesting reduced consumer interest or low visibility in a competitive market.

- The 65+ age group drives the highest sales, highlighting an opportunity to deepen engagement with this segment.

- New customer acquisition is weak (only 27%), while returning customers contribute over 70% of revenue and profit.

- Most orders (77%) come from physical stores, indicating underperformance and low adoption of the online channel.

- Lack of marketing data limits understanding of campaign impact or acquisition effectiveness.

# Recommendations:
- Focus on improving product visibility, revitalizing underperforming categories, and enhancing the online store experience. 
- Tailor offerings for senior customers and design marketing strategies to attract and convert new customer segments.
- Begin capturing marketing and campaign data for better ROI tracking.
