# Credit Card Customer & Transaction Analysis - Power BI

## Overview
This project delivers two interactive Power BI dashboards that analyze customer demographics and transaction behavior for a credit card portfolio. It enables performance tracking across gender, income group, age group, card category, and spending category.

## Objective
- To understand customer distribution by gender, age group, and income group.
- To analyze how spending varies across expense categories.
- To track Transaction trends over time.
- To compare transaction behavior between male and female customers.
- To monitor key performance indicators such as total spend, transaction count, credit utilization, and delinquency.

## Tools Used
- **Power BI** - Dashboard design and reporting.
- **Power Query** - Data cleaning and transformation.
- **DAX** - Creating measures and KPIs
- **Data Modelling** - Building relationships between tables.

## Key Insights
- Spending is highest in bills category and follwed by entertainment category.
- Male customers contribute more to total spend compared to female customers.
- Customers aged 45-54 represent the largest customer segment.
- High income customers have the highest average credit limit while middle income customers have lowest.

## Dashboards

### Dashboard 1 – Credit Card Customer Overview
This dashboard focuses to understand customer segments and risk patterns.

**Key Features:**
- KPI cards for:
  - Total customers
  - Average credit limit
  - Average satisfaction score
  - Delinquency rate
- Visuals:
  - Customer distribution by gender
  - Customer distribution by age group
  - Customer distribution by income group
  - Average credit limit by income group
  - Deliquency rate by age group
  - Average income comparison by gender
- Filters:
  - Gender
  - Age group
  - Income group
  - Card category
  - Date

### Dashboard 2 – Transaction Report
This dashboard helps to analyze how customers spend and how transaction activity changes over time.

**Key Features:**
- KPI cards for:
  - Total spend
  - Transaction count
  - Average Transaction Value  
  - Total Interest earned
  - Utilization ratio
  - Transaction growth %
- Visuals:
 - Monthly transaction trend by gender
 - Weekly transaction count
 - Transaction amount by expense category 
 - Transaction share bt payment method
 - Average transaction value by card category
- Filters:
  - Date
  - Gender
  - Card category
  - Expense type
  - Payment method

## Interactivity & Features
- All visuals respond to slicer selections.
- Cross-filtering between male and female customers.
- Trend comparison between male and female customers.

## Screenshots
Screenshots of the final dashboards are available in the **`screenshots`** folder:

- 01 - Customer overview (default view)
- 02 - Customer overview (with filters applied)
- 03 - Transaction report (default view)
- 04 - Transaction report (with filters applied)

## Challenges Faced
- Handling and organizing multiple measures.
- Managing slicer interactions across multiple visuals.
- Avoiding duplicate calculations in DAX.
- Keeping layout clean hile inserting multiple charts.

## Files Included
- Complete Power BI dashboard file
- Dashboard screenshots   
- Raw datasets (CreditCard and customer data)

## Conclusion
This project demonstrates the ability to transform raw credit card data into structred business insights using Power BI. It highlights skilld in data modelling, DAX, dashboard design and interactive reprting.
