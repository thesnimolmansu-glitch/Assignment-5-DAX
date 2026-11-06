1. Data Modeling
 Established relationships between the ⁠List of Orders⁠, ⁠Order Details⁠, and ⁠Sales target⁠ datasets prior to performing analysis and data visualization.
2. Calculated Columns (DAX)
 Category Type: Combined ⁠Category⁠ and ⁠Sub-Category⁠ into a single column in the ⁠Order Details⁠ table.
 Revenue per Order: Calculated total revenue using ⁠[Amount] * [Quantity]⁠ per order in ⁠Order Details⁠.
 Sales Category: Categorized each order as 'Above Average' or 'Below Average' based on the ⁠Amount⁠ value.
3. Calculated Measures (DAX)
 Order Count: Counts total orders from the ⁠Order Details⁠ table.
 Average Profit in Delhi: Measures average profit specifically for orders placed in Delhi.
 Year-to-Date (YTD) Sales: Calculates cumulative sales from the earliest order date up to each order date.
 Visualizations Created
1. Sales Target Achievement by Category: Clustered column chart comparing actual sales with target sales across categories.
2. Max Profit Margin by Sub-Category: Donut chart analyzing the highest profit margin per product sub-category.
3. Monthly Sales Trend: Line chart illustrating monthly sales performance over time.
4. Comparison of Profit and Quantity by Sub-Category: Scatter chart showing the correlation between profit and total quantity sold per sub-category.
5. Comparison of Total Sales Amount and Target:
 Single Cards: Total sales vs. sales target for quick comparison.
 Multi-Row Card: Minimum sales target for each segment.
6. Sales Performance Matrix: Matrix visual showing sales performance by category across months.
7. Geographic Sales Analysis: Map visual displaying regional sales patterns across cities.
8. Sales Distribution by Sub-Category: Treemap showcasing product sales distribution.
9. Order Count Analysis by State: Funnel chart highlighting order distribution across states
