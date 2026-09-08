# Customer-Behavior-Analysis

An end-to-end **Customer Behavior Analysis** project built using **Python, Pandas, PostgreSQL, SQL, and Power BI** to analyze customer purchasing behavior and generate actionable business insights.

## Project Overview

The project follows a complete data analytics workflow:

```text
Raw Dataset
    ↓
Python & Pandas
(Data Cleaning + Feature Engineering)
    ↓
PostgreSQL
    ↓
SQL Analysis
    ↓
Power BI Dashboard
```

## Tools & Technologies

* **Python** — Data cleaning and transformation
* **Pandas** — Data manipulation and feature engineering
* **PostgreSQL** — Data storage
* **SQL** — Business analysis
* **Power BI** — Data visualization and dashboard
* **DAX & Power Query** — Power BI analysis and transformation

## Data Cleaning & Feature Engineering

The raw dataset was cleaned and prepared using Python and Pandas.

### Data Cleaning

* Inspected dataset structure, data types, statistics, and missing values
* Handled missing `Review Rating` values using category-wise median
* Standardized column names
* Renamed columns for easier analysis
* Removed unnecessary columns

### Feature Engineering

Created new analytical columns:

* **Age Group** — Young Adult, Adult, Middle-Aged, Senior
* **Purchase Frequency Days** — Converted purchase frequency categories into numeric day intervals

The cleaned dataset was then loaded into PostgreSQL for further analysis.

## SQL Analysis

SQL was used to answer business questions related to:

* Revenue by gender
* Discount usage and spending
* Product ratings
* Shipping preferences
* Subscriber vs non-subscriber spending
* Product discount rates
* Customer segmentation
* Top products by category
* Repeat buyers and subscription behavior
* Revenue by age group

### SQL Concepts Used

`GROUP BY` · `CASE` · `CTE` · `Subqueries` · `Window Functions` · `ROW_NUMBER()` · `SUM()` · `AVG()` · `COUNT()` · `ROUND()`

## Power BI Dashboard

The cleaned and analyzed data was used to create an interactive **Customer Behavior Dashboard** in Power BI.

The dashboard focuses on:

* Customer demographics
* Revenue analysis
* Product performance
* Discounts
* Subscription behavior
* Shipping preferences
* Customer segmentation
* Age-group analysis

## Skills Demonstrated

**Python | Pandas | PostgreSQL | SQL | Power BI | DAX | Power Query | Data Cleaning | Feature Engineering | Data Analysis | Data Visualization**

About

This project was created as part of my Data Analyst portfolio to demonstrate an end-to-end approach to data cleaning, data transformation, SQL analysis, and business intelligence using Python, PostgreSQL, SQL, and Power BI.

