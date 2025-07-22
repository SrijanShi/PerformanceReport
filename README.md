# PerformanceReport

**Plant Co. Gross Profit Performance Dashboard**
**Overview**
This Power BI report provides an analytical overview of gross profit, sales, and quantity data for a plant-based company. The report compares current year performance with the previous year using YTD (Year-To-Date) and PYTD (Previous Year-To-Date) metrics, along with country and product-level insights.

The dashboard is designed for decision-makers to monitor profitability, track performance trends over time, and identify opportunities or areas of concern based on region and product segmentation.

**Features**
Year-To-Date (YTD) and Previous Year-To-Date (PYTD) performance tracking

Dynamic measure switching between Sales, Quantity, and Gross Profit using slicers

Monthly and quarterly trend analysis

Country-level and product-type profitability breakdown

Interactive visuals: waterfall chart, treemap, stacked column chart, scatter plot

Responsive mobile layout built using Power BI's mobile canvas

**Dataset**
The report uses a structured dataset containing:

Transactional data with order details

Product and customer information

Dates with full calendar hierarchy

Measures including:

Sales

Quantity

Gross Profit

Gross Profit Percentage

Custom date columns and hierarchies were created to enable period comparisons and accurate visualizations.

**Metrics and DAX Measures**
Key measures include:

YTD_Sales, YTD_Quantity, YTD_GrossProfit: Total values from Jan 1 of selected year to the current date

PYTD_Sales, PYTD_Quantity, PYTD_GrossProfit: Same-period totals from the previous year

YTD_vs_PYTD: Difference and percentage change between YTD and PYTD

Dynamic switch measures using the DAX SWITCH() function for toggling between metric types

Quarter and month breakdown columns for formatted X-axis grouping

**Visualizations**
KPI Cards: Display current YTD and PYTD values and their differences

Waterfall Chart: Shows monthly increases and decreases in performance

Stacked Column + Line Chart: YTD vs PYTD per month, broken down by product type

Treemap: Highlights bottom 10 countries by change in gross profit

Scatter Plot: Segments customer accounts by Gross Profit % and YTD value

Slicers: Allow user filtering by year, metric type, product type, and date

**Mobile Layout**
A mobile-optimized version of the dashboard was created using Power BI’s mobile layout editor. This ensures the report is accessible and usable on mobile devices through the Power BI mobile app.

**How to Use**
Open the .pbix file in Power BI Desktop.

Use the slicers at the top to select:

Year (e.g., 2023)

Metric (Sales, Quantity, Gross Profit)

Explore visualizations for monthly, quarterly, and country-wise insights.

Use the mobile layout for a responsive experience on smaller screens.




<img width="1183" height="666" alt="image" src="https://github.com/user-attachments/assets/045f6607-1f32-4a7f-a139-24bbd65df927" />


https://github.com/user-attachments/assets/b76b7795-ee98-4130-9e38-8c4d9eb80937

