# Task 6 - Sales Trend Analysis Using SQL Aggregations

## Objective

Analyze monthly revenue and order volume using SQL aggregate functions and date-based grouping.

## Tools Used

* SQL Server Management Studio (SSMS)
* SQL

## Dataset

Amazon Sales Dataset

## Columns Used

* Order_ID
* Date
* Amount

## SQL Concepts Applied

* GROUP BY
* SUM()
* COUNT(DISTINCT)
* ORDER BY
* TOP
* TRY_CAST()
* Aggregate Functions

## Queries Performed

### 1. Monthly Revenue and Order Volume Analysis

Grouped sales data by year and month to calculate:

* Total Revenue
* Total Order Volume

### 2. Top 3 Months by Revenue

Identified the three highest-performing months based on total sales revenue.

### 3. Time Period Analysis

Analyzed sales performance for a selected time period (April–May 2022).

## Data Cleaning Note

The Amount column was stored as NVARCHAR. To perform revenue calculations, TRY_CAST() was used to convert the values into DECIMAL format before applying the SUM() function.

## Results

Successfully analyzed monthly sales trends, calculated revenue, measured order volume, and identified top-performing months using SQL aggregation techniques.

## Key Findings

- April 2022 generated the highest revenue.
- Monthly revenue and order volume trends were identified using SQL aggregation functions.
- Data type conversion was required because the Amount column was stored as NVARCHAR.
- Revenue calculations were successfully performed using TRY_CAST().

## Outcome

Learned how to:

* Group data by month and year
* Use aggregate functions
* Calculate monthly revenue
* Count unique orders
* Sort and analyze time-based sales trends
* Handle data type conversion issues in SQL
  
