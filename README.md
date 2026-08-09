# Executive summary-Sales Report-Power BI
# Project Overview
This project features an interactive Power BI Sales Analytics Dashboard designed to transform raw transaction data into actionable business insights. The dashboard tracks key performance indicators (KPIs), visualizes sales trends over time, and analyzes product and regional performance to support data-driven decision-making.
# Key Features & Insights
--Dynamic KPIs: Real-time tracking of total revenue, profit margins, transaction volumes, and year-over-year (YoY) growth.

--Sales Performance & Trends: Interactive time-series charts identifying seasonal trends, peak sales periods, and revenue distribution.

--Geographical & Product Analysis: Breakdown of sales by region and product category to pinpoint top-performing markets and underperforming inventory.

--Customer Segmentation: Insights into purchasing behavior, average order value (AOV), and customer retention patterns.
# Tools & Technologies Used
--Power BI Desktop: Used for data modeling, managing table relationships, and creating the interactive visualization layer.

--DAX (Data Analysis Expressions): Utilized to write custom measures for advanced calculations, percentage margins, and time-intelligence metrics.

--Power Query (M): Used for data extraction, cleaning, shifting data types, and structural transformations.

--Excel: Primary data source for storing and retrieving the transactional dataset.
# Project Structure
Sales-Analytics-PowerBi.pbix: The core Power BI project file containing the data model, relationships, and visual reports.

data/: Contains the raw or cleaned datasets used to feed the report.

images/: Contains dashboard screenshots for quick previewing.
# SUMMARY OF PROJECT
--Creating Models between sales Data Table and other dimension Tables for Viusalization
--Sales amount by orderDate/DueDate
--Order Quantity by reseller Country
--Sales amount by Product Category and Reseller business Type
--Product category by sum of salesAmount
--Fiscal Calender slicer
--Day with most sales
--Regional KPI for most region worth investing
