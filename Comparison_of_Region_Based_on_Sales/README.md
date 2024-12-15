# Comparison of Region-Based Sales Dashboard
![comparison_of_region_based_sales](https://github.com/user-attachments/assets/5e98e505-a804-4001-8b24-ca61dd78ef6b)

This project involves creating an interactive Tableau dashboard to compare the sales performance between two selected regions. The dashboard provides key insights to the organization’s upper management, enabling them to analyze regional sales data and take actionable steps for improvement.

## Problem Statement
The director of the organization needs to compare sales between two regions. Regional operators have recorded the sales data, and upper management wants to visualize and compare this data to:
* Understand performance differences between regions.
* Identify trends, strengths, and areas of improvement.
* Suggest actionable measures to enhance overall sales performance.

## Project Objectives
The key objectives of this project are:

* To create a dynamic and interactive Tableau dashboard that allows the comparison of two regions.
* To visualize important sales metrics, such as total sales, average sales per order, and customer engagement, for better decision-making.
* To utilize Tableau features such as hierarchies, parameters, and calculated fields for flexible data analysis.

## Dataset Description
The project uses Tableau's Sample Superstore Dataset. Key variables used in the analysis include:
* Location Data: Region, Country, State.
* Order Information: Order Date, Number of Orders, Products Sold.
* Sales Metrics: Total Sales, Average Sales per Order, Number of Customers.
* Additional Metrics: Profit and Product Segmentation.

## Key Features of the Dashboard
### Metrics for Comparison
The dashboard dynamically displays the following metrics for the two selected regions:

1. First Order Date: When sales began in the region.
2. Total Sales: The cumulative sales revenue.
3. Average Sales per Order: Revenue generated per order.
4. Number of Customers: Total customers served.
5. Number of Orders: Total orders placed.
6. Number of Products Sold: Product diversity in sales.

### Interactivity
+ Region Selection:
    + Parameters to select two regions (Primary and Secondary) for comparison.
* Dynamic Visualization:
    * Real-time updates to metrics and visualizations based on selected regions.
* Calculated Fields
    Used to derive insights such as First Order Date and metrics for selected regions.
* Hierarchy Implementation
    A hierarchical structure for Location (Country → Region → State) ensures easy navigation and drill-down analysis.

## Tasks Performed
1. Data Preparation
* Used the Sample Superstore Dataset and grouped data by folder to segregate relevant information.
* Created a Location Hierarchy for region-based analysis.
2. Parameter and Calculated Field Creation
* Designed two parameters: Primary Region and Secondary Region, allowing users to select regions for comparison.
* Developed calculated fields to filter and display data for the chosen regions.
3. Dashboard Design
* Created a clean and visually appealing Tableau dashboard by aligning sheets and visualizations.
* Included the following details for both selected regions:
    * First Order Date
    * Total Sales
    * Average Sales per Order
    * Number of Customers
    * Number of Orders
    * Number of Products Sold
4. Visualization
* Partitioned the dashboard to show a side-by-side comparison of the two selected regions.
*  Designed charts and KPIs to clearly present trends and metrics.
## Project Outcome
The dashboard effectively visualizes and compares sales data for any two selected regions. Key outcomes include:

* Sales Insights: Understand which region performs better in terms of sales volume, customer engagement, and product diversity.
* Data-Driven Decisions: Enable management to take corrective measures to improve sales in underperforming regions.

## How to Use the Dashboard
1. Access the Dashboard:
+ Open the dashboard in Tableau Public or Tableau Desktop.
2. Select Regions for Comparison:
+ Use the Primary Region and Secondary Region dropdown menus to select two regions.
3. View Insights:
+ Analyze the KPIs and metrics for both regions.
+ Drill down into specific details using the Location Hierarchy.
## Tools and Techniques Used
Key Tableau Features
+ Parameters: Dynamic selection of regions for comparison.
+ Calculated Fields: Deriving insights such as first order date and custom metrics.
+ Hierarchy: Location drill-down for flexible data exploration.
+ Interactive Dashboard: Side-by-side comparison of selected regions.
## Prerequisites
To use or replicate this project, you should be familiar with:

+ Building hierarchies, parameters, and calculated fields in Tableau.
+ Designing and formatting interactive dashboards.
## Conclusion
This Tableau dashboard provides upper management with a powerful tool to visualize and compare regional sales data, facilitating data-driven decision-making to enhance sales performance. The project demonstrates effective use of Tableau's interactive features to create an actionable business intelligence solution.


## Dashboard Link Available Here,
https://public.tableau.com/app/profile/siddhi.shastri/viz/Book1_17232076026780/Dashboard1
