# Customer_analysis
-------------------

Descriptive Customer Analysis Dashboard in Tableau
---------------------------------------------------
Overview
---------
This Tableau project provides a detailed descriptive analysis of customer data using various visualizations. The dashboard includes insights on revenue distribution, trends, and correlations across different dimensions such as geography, time, age, discount, and product categories.

Visualizations
--------------
Revenue per State (Geographic Chart)
Revenue per Month (Line Chart)
Revenue per Age (Bar Chart)
Quantity-Discount Correlation (Scatterplot Chart)
Revenue Percentage per Region (Donut Chart)
Revenue per Category (Butterfly Chart)

Dataset
--------
The dataset used for this analysis includes customer purchase data with the following fields:
---------------------------------------------------------------------------------------------

CustomerID
State
Date
Age
Revenue
Quantity
Discount
Region
Category
Visualizations Details

1. Revenue per State (Geographic Chart)
-----------------------------------------
This chart displays the total revenue generated in each state. It helps identify high-performing regions.

Steps to create:

Connect your dataset to Tableau.
Drag State to the Columns shelf.
Drag Revenue to the Rows shelf.
Change the visualization type to a Map.
Adjust the color gradient to reflect revenue values.

2. Revenue per Month (Line Chart)
---------------------------------
This line chart shows the trend of revenue over time, providing insights into seasonal patterns and growth trends.

Steps to create:

Drag Date to the Columns shelf and set it to Month.
Drag Revenue to the Rows shelf.
Change the visualization type to a Line Chart.

3. Revenue per Age (Bar Chart)
------------------------------
This bar chart categorizes revenue based on customer age groups, highlighting which age groups contribute the most to the revenue.

Steps to create:

Create age bins if necessary (e.g., 0-10, 11-20, etc.).
Drag Age (or Age Bins) to the Columns shelf.
Drag Revenue to the Rows shelf.
Change the visualization type to a Bar Chart.

4. Quantity-Discount Correlation (Scatterplot Chart)
----------------------------------------------------
This scatterplot shows the relationship between the quantity of items purchased and the discount offered, revealing how discounts impact purchase quantities.

Steps to create:

Drag Quantity to the Columns shelf.
Drag Discount to the Rows shelf.
Change the visualization type to a Scatterplot.

5. Revenue Percentage per Region (Donut Chart)
----------------------------------------------
The donut chart visualizes the percentage contribution of each region to the total revenue.

Steps to create:

Create a Pie Chart with Region and Revenue.
Convert the Pie Chart to a Donut Chart by adding a circle shape in the center (dual-axis with an empty circle).
Adjust the chart to show percentages instead of absolute values.

6. Revenue per Category (Butterfly Chart)
-----------------------------------------
The butterfly chart compares revenue across different product categories, allowing for a side-by-side comparison of two different measures (e.g., male vs. female customers, or two different categories).

Steps to create:

Create two separate bar charts for the categories you want to compare.
Combine these charts into a single view with the bars extending in opposite directions (dual-axis or side-by-side configuration).

I Navigate through different sheets to explore the visualizations.
Use filters and interactive elements to drill down into specific data points.
