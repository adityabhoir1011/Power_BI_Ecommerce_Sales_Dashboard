# Table of Content

- [Overview](#1-overview)
- [Data Model & Relationships](#2-data-model--relationships)
- [DAX Measures](#3-dax-measures)
- [Visuals & Insights](#4-visuals--insights)
- [Filters & Interactivity](#5-filters--interactivity)
- [Conclusion & Insights](#6-conclusion--insights)


## 1. Overview

The E-commerce Sales Dashboard provides insights into yearly sales, profit, orders, and quantities sold. It also includes detailed breakdowns by category, product, region, and shipping type. The dashboard is fully interactive, with filters and slicers allowing for segmented data analysis.

## 2. Data Model & Relationships

The dataset consists of the following tables:

- **e-commerce_data:** Contains sales transaction details, including order quantities, revenue, and customer information.
- **us_state_long_lat_codes:** Contains state-wise latitude and longitude for map visualization.
- **calender:** A custom date table used for time-based calculations and filtering.

## 3. DAX Measures

Several DAX measures were created for calculating key performance indicators (KPIs):

**Year-to-Date (YTD) Measures:**
- **YTD Sales →** Calculates total sales up to the current date within the year.
- **YTD Profit →** Computes the cumulative profit for the year.
- **YTD Orders →** Counts the total number of orders in the year.
- **YTD Quantity →** Aggregates the total quantity sold year-to-date.

**Year-Over-Year (YoY) Percentage Change:**
- **YoY Sales % →** Measures the percentage change in sales compared to the previous year.
- **YoY Profit % →** Calculates the YoY growth in profit.
- **YoY Orders % →** Computes the YoY variation in total orders.
- **YoY Quantity % →** Evaluates the YoY change in product quantities sold.

## 4. Visuals & Insights

The dashboard contains multiple visuals representing different business insights:

- **KPIs (Cards with Trend Lines):** YTD Sales, YTD Profit, YTD Orders, YTD Quantity, each showing trends over time.
- **Sales by Category (Table):** Compares sales figures for Furniture, Office Supplies, and Technology. Includes YoY growth percentages for each category.
- **Top 5 Selling Products (Bar Chart):** Displays highest-selling products by revenue.
- **Worst 5 Selling Products (Bar Chart):** Shows products with the lowest sales.
- **Sales by Shipping Type (Donut Chart):** Breaks down sales by Standard, Second Class, First Class, and Same Day shipping.
- **Sales by Region (Donut Chart):** Highlights revenue distribution across West, East, Central, and South regions.
- **Sales by State (Map Visualization):** Uses latitude/longitude data to map sales across U.S. states.

Color-coded based on sales volume.

![Dashboard]("http:")

## 5. Filters & Interactivity

**Slicer:** customer_segment (Consumer, Corporate, Home Office) allows filtering based on customer type.

**Filters:** All visuals are dynamically linked, meaning selecting a category or region updates all related charts in real-time.

## 6. Conclusion & Insights

- The E-commerce Sales Dashboard is a comprehensive tool for analyzing business performance across multiple dimensions.
- It helps decision-makers track key KPIs, identify best-performing products and regions, and make data-driven business strategies.