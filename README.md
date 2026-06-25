Project Overview

This project is my Capstone 3 Power BI analysis for EmporiUm, a virtual student bookstore that sells books and student-related products through both in-store and online sales. The goal of this project was to analyze sales performance for the Northeast region and create a Power BI report that helps the regional sales team better understand trends, product performance, state-level sales, and top-selling books.

The final report was built in Power BI using the provided sales data and a separate book list file that included general bookstore book titles and author names.

Business Scenario

EmporiUm wants to review sales performance over the last four years. As the data analyst, my job was to clean and model the data, build useful visuals, and present insights that could help the regional director, territory managers, and store managers make better business decisions.

This report focuses on the Northeast region.

Tools Used
Power BI Desktop
Power Query
Power BI Model View
Excel
Text/CSV data source
GitHub
Data Preparation Process
1. Reviewed the source files

I started by reviewing the provided Excel sales file and the book list text file. The Excel file contained the main sales data, while the book list included general bookstore titles and author names.

2. Cleaned the book list

The original book list was formatted like a numbered text list, so I cleaned it into a Power BI-friendly table. The cleaned book list includes fields such as:

BookID
Title
Author
Audience
IsTextbook

This made it easier to use the book list in Power BI and connect it to the product data.

3. Cleaned and shaped the sales data

In Power Query, I checked the tables for common data issues such as blank rows, extra spaces, incorrect data types, messy headers, and date fields that needed formatting.

The main goal was to make the data easier to model and use in visuals.

4. Built the data model

After cleaning the data, I created relationships between the main sales tables and supporting lookup tables.

The main sales tables were:

Store Sales
Online Sales

The supporting lookup tables included:

Products
Inventory Categories
Store Locations
State Regions
Regional Directors
Store Managers
Shipper List
Book List

Most relationships were set up as one-to-many relationships with single-direction filtering to keep the model simple and clean.

Power BI Report Pages

The report includes at least two pages with clear headers.

Page 1: Northeast Sales Overview

This page focuses on overall sales performance in the Northeast region.

Visuals included:

Line chart showing sales trends over time
Bar chart showing sales performance by category
Slicer/filter for interacting with the report
Page 2: Northeast State and Book Performance

This page focuses more on state-level performance and top-selling books.

Visuals included:

Pie chart showing relative sales by state
Table showing top-selling general audience books
Author names included for the top-selling books
Required Visuals Included

The Power BI report includes the required visuals:

Sales trend line chart
Shows how sales changed across the full time period.
Sales by category chart
Compares sales performance across different product categories.
Sales by state donut or pie chart
Shows how each Northeast state contributed to overall sales.
Top-selling books table
Lists the top-selling general audience books with author names, excluding textbooks.
Key Insights

Some of the main insights from the report include:

Sales trends can help the team see stronger and weaker sales periods.
Category performance helps show which types of products are driving the most revenue.
State-level sales make it easier to compare performance across the Northeast region.
The top-selling books list helps managers understand which general bookstore titles are most popular with customers.
Why This Report Is Useful

This report is useful because it gives the Northeast sales team a clearer view of what is happening in the region. Instead of looking through raw spreadsheets, managers can use the Power BI report to quickly understand sales patterns, compare states, review categories, and identify popular books.

The report can support better decisions around inventory, sales strategy, and regional planning.

Video Recording

10-minute project walkthrough video here:

Video Recording Link

Published Power BI Report

Power BI Service report link here:(https://app.powerbi.com/links/X1tUePQZU1?ctid=bbce5c37-f181-4d0c-9310-7f877336e1cf&pbi_source=linkShare)

Powerpoint Link: https://yearuptemp-my.sharepoint.com/:p:/g/personal/pgreen-holloway_my_yearupunited_org/IQDubFaqxCQYTbCq-gmPBPQrAVX2AFR3jBC-ry0QlWLdMwg?e=WehRBx

Final Reflection

This project helped me practice cleaning data, building a Power BI model, creating visuals, and presenting insights in a clear way. I also got more comfortable using Power Query, setting up relationships, and thinking about how a report can support real business decisions.
