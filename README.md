# Sales-Performance-Dashboard
## Overview
This project demonstrates an end-to-end data analyst workflow using Power BI to analyze ecommerce sales data. The dashboard transforms raw transactional data into actionable insights by leveraging data cleaning, data modeling, DAX measures, and time-series analysis.The focus of this project is on metric definition, trend analysis, and business insight generation, rather than just visualization.

## Problem Statement
Stakeholders need a clear, interactive way to:

Monitor overall sales performance

Track revenue trends over time

Identify top-performing products and regions

Evaluate key KPIs such as Average Order Value (AOV) and Month-over-Month (MoM) growth

# Dataset

## Source: Ecommerce sales CSV

Fields:

OrderID – Unique identifier for each order

Date – Order date

Product – Product name

Category – Product category

Revenue – Revenue per order

Customer Location – Customer region

# Data Cleaning & Transformation

## Performed in Power Query:

Standardized data types for dates and numeric fields

Cleaned and normalized region values

Removed duplicate records

Created derived time attributes (Year, Month)

Preserved raw data integrity while enabling analysis-ready structure

## Data Model

Implemented a star schema

Fact table: Sales

Dimension table: Date

One-to-many relationship between Date and Sales tables

Enabled accurate filter context and time intelligence calculations

## Metrics & KPIs (DAX)

Custom DAX measures were created to support analysis:

Total Revenue

Total Orders

Average Order Value (AOV)

Month-over-Month Revenue Growth (%)

Time intelligence functions such as DATEADD were used to calculate period-over-period performance accurately.

## Dashboard Analysis

The Power BI dashboard includes:

KPI cards for quick performance evaluation

Revenue trend analysis using a monthly time series

Product-level revenue ranking (Top N analysis)

Regional revenue comparison

Interactive slicers to dynamically filter results by date, category, and region

## Key Analytical Insights

Revenue exhibits consistent month-over-month growth with identifiable seasonal spikes

A small subset of products contributes a disproportionate share of total revenue

The USA and India generate the highest revenue among all regions

Certain categories show lower AOV but higher order frequency, suggesting price-sensitive purchasing behavior

## Business Impact & Recommendations

Prioritize high-revenue products for inventory and forecasting

Allocate marketing spend toward top-performing regions

Explore pricing or bundling strategies to improve AOV in lower-value categories

Use MoM trends to monitor performance changes and detect anomalies early

## Tools & Technologies

Power BI

DAX

Power Query

Data modeling

Time-series analysis

KPI development

Business analytics

## Files Included

Sales_Dashboard.pbix – Interactive Power BI dashboard

ecommerce_sales.csv – Raw dataset

Sales_Dashboard_Portfolio_Walkthrough.pdf – Executive summary of analysis

## Analytical thinking & insight generation

Communicating findings to stakeholders

Optional Resume Line (Data Analyst)

Analyzed ecommerce sales data using Power BI and DAX to build KPIs, perform time-series analysis, and deliver actionable insights on product and regional performance.
