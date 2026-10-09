# Suria Mart Sales & App Analytics Dashboard

A Power BI dashboard built for the K-Youth Programme (Aug 2025). It analyses retail sales, mobile app usage and wallet top-ups across four Suria Mart store locations.

## Dashboard pages
- **Overview:** sales by month and payment method (app vs cashier), app rating and installs by operating system, top-up amounts by month, and a word cloud of customer feedback.
- **Sales:** sales trend by month, sales by store location (map), sales by product category, and sales by customer age group.
- **App:** wallet top-up trends and time spent on the Smart Recipe and Smart Price Comparison features.

## Data
The source was an Excel workbook with 8 sheets: sales, top-ups, customers, app data, two product tables, stores and receipts. It contained about 4,250 sales transactions from April to June 2024.

## Data cleaning and transformation (Power Query)
- Fixed app ratings that were stored as dates.
- Combined two product tables into one.
- Derived customer age groups from the demographic field.

## Tools
Power BI, Power Query, Excel

