## DAX Depo – Power BI Project

# Overview

This project focuses on advanced DAX calculations in Power BI to build a strong data model and generate insights like sales, profit, returns, and time-based analysis using only Matrix visuals.

# Dataset

Fact Tables: Sales_Fact, Returns_Fact
Dimension Tables: Customer_Dim, Product_Dim, Date_Dim, Region_Dim

# Calculated Columns

Profit = SalesAmount - Cost

ReturnFlag = Returned / Not Returned

Customer Full Name = First Name + Last Name


# Measures

Total Sales

Total Cost

Total Profit

Return Rate (%)

Average Sale per Transaction


# Quick Measures

Year-over-Year Sales Growth

Monthly Sales Difference


# DAX Concepts Used

SUM, AVERAGE, MAX, COUNTX, DISTINCTCOUNT, IF, AND, OR, SWITCH, CONCATENATE, UPPER, LEFT, YEAR, MONTH, EOMONTH

# Filter Context

Used ALL(), FILTER(), CALCULATE() to compare filtered and unfiltered data

# Time Intelligence

TOTALYTD(), SAMEPERIODLASTYEAR(), DATESINPERIOD(), and running total using CALCULATE + DATESBETWEEN

# Additional Logic

Sales categorization using SWITCH (Low, Medium, High) and iterator functions SUMX, AVERAGEX

# Output

Matrix visual only, grouped by Region, Month, Product Category, and Customer Segment. No other visuals used.

## Author
# yash
