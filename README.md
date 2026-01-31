his project demonstrates an end-to-end data analytics workflow using Power BI, starting from raw data cleaning to data modeling and interactive dashboard creation.

 Data Cleaning & Preparation

Imported raw Excel data into Power BI.

Fixed data type issues (e.g., converting text-based dates into proper Date format).

Cleaned categorical columns by removing extra spaces and standardizing text values (using Trim and Lowercase).

Removed duplicates and handled inconsistent values to ensure data quality.

Data Modeling

Designed a Star Schema with:

One Fact table containing transactional metrics such as revenue, cost, profit, and quantity.

Two Dimension tables:

Date Dimension created from Order Date (Year, Month Number, Month Name).

Customer Dimension containing descriptive customer attributes.

Established one-to-many relationships with single-direction filtering for optimal performance.

Measures & Calculations

Created DAX measures for key KPIs, including:

Total Revenue

Total Cost

Total Profit
