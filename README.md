# Super Store Sales  

***Sales-Performance-Analysis***

A retail company ("Global Superstore") operates across multiple regions in the United States, selling products in three main categories: Furniture, Office Supplies, and Technology. The management has observed fluctuating profits despite consistent sales growth. Some orders show losses due to high discounts, shipping delays, and unprofitable product lines.

The leadership team wants data-driven insights to answer the following key business questions:

***Tools used:-***

1. mySQL
2. power BI

   
***Task_01:*** Sales & Profitability

1. KPI:
   a) Total Sales = SUM(Sales)
   b) Total Profit = SUM(Profit)
   c) Profit Margin % = SUM(Profit) / SUM(Sales) × 100
   d) Average Sales per Order = SUM(Sales) / COUNT(DISTINCT Order ID)
   e) Average Profit per Order = SUM(Profit) / COUNT(DISTINCT Order ID)
   f) Sales per Customer = SUM(Sales) / COUNT(DISTINCT Customer ID)
  
2. What are the overall sales, profit, and profit margins?
3. Which products, categories, and sub-categories are the most and least profitable?
4. Are there any loss-making products that should be discontinued?

***Task_02:*** Customer Insights

1. KPI:
   a) Total Customers = COUNT(DISTINCT Customer ID)
   b) Sales per Customer Segment (Consumer, Corporate, Home Office)
   c) Top 10 Customers by Sales
   d) Customer Retention Rate (repeat orders vs. one-time customers)
   e) Average Profit per Customer
  
2. Who are the top 10 customers by sales and profit?
3. How do different customer segments (Consumer, Corporate, Home Office) perform in terms of revenue and profit?
4. What is the customer retention rate (repeat vs. one-time customers)?

***Task_03:*** Regional & Market Insights

1. KPI
   a) Sales by Region (West, East, South, Central)
   b) Profit by Region
   c) Sales by State/City
   d) Top 5 Cities by Sales
   e) Least Profitable States
   
2. Which regions, states, and cities are the most profitable?
3. Which areas consistently generate losses?
4. How does shipping mode and delivery time impact customer satisfaction and profitability?

***Task_04:***Discount & Shipping Impact

1. KPI:
   a) Sales by Ship Mode (Standard, Second Class, etc.)
   b) Profitability by Ship Mode
   c) Average Discount Given
   d) Sales Lost due to High Discounts (where Discount > 0.3 and Profit < 0)

1. How do discount levels affect profitability?
2. Are high discounts driving sales or eroding profits?
3. Which shipping modes are most cost-effective and profitable?

***Task_05:*** Time-based Performance

1. KPI:
   a) Monthly Sales Trend
   b) Year-over-Year Growth
   c) Quarterly Profit Margin
   d) Seasonal Peaks (festive/holiday sales spikes)
   e) Average Delivery Days = DATEDIFF(Ship Date, Order Date)

2. What are the monthly/quarterly/yearly sales and profit trends?
3. Are there any seasonal peaks in demand?
4. How has the company’s growth rate changed over time?

***Task_06:*** Order & Product performance

1. KPI:
   a) Total Orders = COUNT(DISTINCT Order ID)
   b) Total Quantity Sold = SUM(Quantity)
   c) Average Order Value (AOV) = SUM(Sales) / COUNT(DISTINCT Order ID)
   d) Most Sold Product (by Quantity)
   e) Top Selling Product (by Sales)
   f) Most Profitable Product
   g) Loss-Making Product (negative profit)

2. How many total orders were placed?
3. What is the average order value (AOV) = Sales ÷ Orders?
4. Which order had the highest sales value?
5. Which order had the highest profit?
6. Which order resulted in a loss (negative profit)?
7. What is the average quantity per order?
8. What is the distribution of order sizes (small: 1–2 items, medium: 3–5, large: 6+)?
9. Which customers place the largest orders (by sales/quantity)?
10. What percentage of orders use each ship mode (Standard, Second Class, First Class, Same Day)?
11. Do faster shipping modes correspond to higher or lower profits?
12. What is the total number of products sold?
13. Which product generated the highest sales?
14. Which product generated the highest profit?
15. Which product incurred the highest loss?
16. What is the average sales per product?
17. Which sub-category has the highest sales?
18. Which sub-category has the lowest profit margin?
19. What is the profitability of each category (Furniture, Office Supplies, Technology)?
20. Which products have high sales but low profits (possible discount problem)?
21. Which products have low sales but high profit margin (hidden gems)?
22. How many products are sold at a loss overall?
23. Which 10 products account for the highest % of total revenue (Pareto 80/20 rule)?
24. Which products are fast-moving (ordered frequently) vs. slow-moving (rarely ordered)?
25. What is the average discount per product/sub-category?
26. Do products with high discounts actually result in higher sales volume?
27. Are large orders more profitable than small ones?
28. Which product bundles (often ordered together) generate the most revenue?
29. What is the average order size per category?
30. How does discount level per order affect profitability?
31. Which products drive repeat orders (customer loyalty)?


***Dashboard prepared using power bI***

1. Executive Overview Dashboard (CEO / Top Management) :
   
   🔹 Purpose: Quick view of company performance
   
2. Sales Performance Dashboard (Sales Manager) :
   
   🔹 Purpose: Track revenue & orders
   
3. Profitability Dashboard (Finance / Strategy) :
   
   🔹 Purpose: Identify what drives or hurts profit
   
4. Order & Product Performance Dashboard (Product Manager) :
   
   🔹 Purpose: Monitor product & order efficiency
   
5. Customer Insights Dashboard (Customer Relationship Team) :
    
   🔹 Purpose: Understand customer value & retention
  
6. Regional & Market Dashboard (Regional Manager):
    
   🔹 Purpose: Focus on geography performance
   
7. Shipping & Discount Dashboard (Operations / Logistics) :
    
   🔹 Purpose: Optimize delivery & discount strategy




