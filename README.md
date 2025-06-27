# Loss-Monitoring-Dashboard
A Power BI dashboard that tracks business loss due to discounts by comparing expected vs. actual revenue, product cost, and net loss. Includes visual trends, sales breakdowns, and interactive filters

## Overview
This Loss Monitoring Dashboard built in Power BI provides insights into the financial impact of product discounts on business performance. It compares:
- Expected Revenue (without discount)
- Actual Revenue (after discount)
- Product Cost
- Net Loss

### The dashboard also features:

- Monthly loss trends
- Discount impact analysis
- Online vs. retail sales comparison
- Interactive filters by product category
- Tooltips to explain loss calculation for better clarity

This report helps decision-makers identify where discounts are affecting profitability and take data-driven actions to reduce unnecessary loss.

Sales Data (Power BI Sample Dataset)
This dataset represents fictional retail sales data designed for analysis, reporting, and dashboard creation using tools like Power BI, Excel, or SQL. It includes product-level transactions, customer profiles, discounts, costs, and sales channels.

## File/Table Name
 #### sales_data

### Columns Overview

1. **Column Name-** Data Type	Description
2. **Product_ID-** Integer	Unique identifier for each product sold.
3. **Sale_Date	Date-** The date on which the transaction occurred.
4. **Sales_Rep	Text-** Name of the sales representative who completed the sale.
5. **Region-** Text	Geographical region of the sale (e.g., North, South, East, West).
6. **Quantity_Sold-** Integer	Total number of units sold in a transaction.
7. **Product_Category-** Text	Type/category of the product (e.g., Furniture, Clothing, Food, Electronics).
8. **Unit_Cost-** Decimal Cost price per unit of the product.
9. **Unit_Price-**	Decimal	Selling price per unit of the product.
10. **Customer_Type-**	Text	Indicates whether the customer is New or Returning.
11. **Discount	Decimal (%)-**	Discount offered as a percentage on the transaction.
12. **Payment_Method-**	Text	Mode of payment used (e.g., Cash, Credit Card, Bank Transfer).
13. **Sales_Channel	Text-**	Sales channel used: Online or Retail.
14. **Region_and_Sales_Rep-**	Text	Concatenated field of region and sales rep (e.g., West-Bob).


## Dashboard Features
The Loss Monitoring Dashboard is built in Power BI to help businesses identify and analyze financial losses incurred due to product discounts. It provides a visually intuitive and interactive view of how discounts impact overall profitability.

### Key Functionalities:

1. **Expected vs. Actual Revenue-**
    Displays what revenue would have been without discounts (expected revenue) compared to the actual revenue after applying discounts. This helps highlight the financial impact of discounting strategies.

3. **Actual Product Cost Tracking-**
     Shows how much it costs the company to produce or acquire the products, allowing users to directly compare cost against revenue.

4. **Net Loss Calculation-**
The dashboard computes loss as:
Loss = Actual Revenue (after discount) – Actual Product Cost
This provides a real-time snapshot of how much money is being lost due to discounting.

5. **Online vs. Retail Sales Breakdown-**
Bar chart visualization comparing performance across online and retail sales channels. This allows stakeholders to understand which sales channel contributes more to losses or revenue.

6. **Total Quantity Sold-**
A KPI card shows the total volume of products sold, providing operational context to revenue and loss metrics.

7. **Monthly Loss Trend-**
Line chart illustrating how loss fluctuates over time. It helps identify patterns, seasonal trends, or specific periods with significant financial impact.

8. **Profit/Loss vs. Discount Analysis-**
Scatter or line visual showing the correlation between discount percentage and profit/loss outcomes, offering insights into how different levels of discounting affect margins.

9. **Interactive Product Category Filters-**
Users can dynamically filter visuals and KPIs based on product categories. This feature allows deeper analysis for specific segments of the business.

10. **Tooltip for Loss Explanation-**
A custom tooltip is integrated into the “Loss” card to explain how the loss is calculated and why it matters. This enhances the dashboard’s usability, especially for non-financial stakeholders.

### Key Insights 

The dashboard offers powerful insights that enable data-driven decision-making:

- **Discounting Directly Impacts Revenue**
  By comparing expected vs. actual revenue, users can see how much potential revenue is lost due to discounts.

- **Losses Occur When Discounted Revenue < Cost**
  Even with high sales volume, if the discount is too aggressive, the revenue may not cover the cost, leading to a net loss.

- **Channel-Specific Analysis**
- The Online vs. Retail comparison may reveal that one sales channel consistently outperforms the other or contributes more to losses, guiding future channel strategies.

- **Seasonal or Campaign-Driven Loss Spikes**
  Monthly loss trends can help detect spikes during sales campaigns, end-of-season clearances, or peak discount periods.

- **Discount Thresholds That Erode Profit**
The discount impact analysis can reveal tipping points—specific discount percentages that begin to harm profitability—helping set better discount policies.

- **Targeted Decision-Making**
  Product category filters enable managers to drill into underperforming segments and develop more targeted corrective actions.


## Tools & Technologies Used
Tool / Technology	Purpose
-  **Power BI Desktop-**	Core platform used to build, model, and visualize the interactive dashboard
- **DAX (Data Analysis Expressions)-** Used for creating calculated measures (e.g., loss, expected revenue) and custom tooltips
- **Power BI Visualizations-**	Native charts and visuals including KPI cards, line graphs, bar charts, and slicers for user interaction
- **Kaggle Dataset (Sales Data)-**	Dataset used as the primary data source. Downloaded from Kaggle.com for simulation of sales, discounts, revenue, and cost
- **Power Query Editor-**	Utilized for transforming, cleaning, and preparing raw data before loading into the Power BI model
- **Power BI Filters & Slicers-**	Enabled filtering by product categories and sales channels for focused analysis

The project leverages Power BI's native capabilities with no external plugins or third-party visuals.


## Visualizations Included
This dashboard incorporates a variety of intuitive and informative visuals to help users understand revenue, cost, and discount-driven losses:

Visualization Type and	Description
- **KPI Cards-**	Display key metrics such as Expected Revenue (No Discount), Actual Revenue (With Discount), Product Cost, Loss, and Quantity Sold
- **Line Chart-**	Shows Monthly Loss Trend to identify seasonal patterns or spikes related to discounts
- **Bar Chart-**	Compares Online vs. Retail Revenue and Loss for evaluating channel performance
- **Stacked Column Chart-**	Visualizes how discounts affect Profit or Loss across different discount ranges
- **Scatter Plot / Line Graph (optional)-**	Displays correlation between discount percentages and resulting loss/profit (if included)
- Slicer / Filter Pane	Allows filtering by Product Category for focused, segment-level insights
- Tooltip (Custom)	Added to the “Loss” card to explain the loss calculation and highlight the impact of discounts versus cost

The visuals are interactive and update dynamically based on user selection and filters.

