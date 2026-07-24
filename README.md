# Highland-Distributors-Sales-Data-Analysis

## Project Overview
Data Analysis and Cleaning of Raw Sales data from Highland Distributors. 

## Objectives
- Clean and standardize the raw sales data.
- Calculate revenue, cost, profit, and margin metrics.
- Analyze sales performance by region, sales representative, category, and month.
- Create an interactive dashboard using PivotTables, PivotCharts, and slicers.
- Document all data cleaning decisions and assumptions.


## Tools Used
- Microsoft Excel
	- PivotTables
	- PivotCharts
	- VLOOKUP
	- GETPIVOTDATA
	- Slicers
	- Excel formulas for data cleaning and calculations

## Data Cleaning Process

The following issues were identified and addressed:

- Standardized inconsistent date formats into the real Excel dates format.
- Standardized Region and Sales Representative names using proper capitalization and trimming extra spaces.
- Removed duplicate records.
- Flagged negative quantity values and converted them to positive values using the ABS() function.
- Filled missing values where appropriate and documented all assumptions.
- Used Product ID to retrieve Unit Cost and Category information from the Product Cost Lookup table and added to the cleaned data.

### Assumptions

- Negative quantities were assumed to be data entry errors rather than returned products and were converted to their absolute values.
- Missing Region values were labeled as "Unknown" where necessary.
- All calculations were performed using the cleaned dataset rather than the raw data.

### Dashboard Components

The dashboard includes:

- Total Revenue (KES) KPI
- Total Profit (KES) KPI
- Average Margin Percentage (%) KPI
- Total Orders KPI
- Monthly Revenue Trend chart
- Revenue by Region chart
- Top 5 Products by Revenue table
- Interactive Region and Month slicers


# Summary of Findings

- Revenue and profit performance can be analyzed across regions, product categories, and by sales representatives.
- The dashboard provides an interactive view of monthly sales trends across regions.
- Data cleaning significantly improved quality, reporting reliability, and removed duplicates. 
