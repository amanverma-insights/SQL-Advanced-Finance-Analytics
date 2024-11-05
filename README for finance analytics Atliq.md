# SQL-Advanced-Finance-Analytics
s

This repository contains SQL scripts and stored procedures developed for advanced finance analytics, focusing on data retrieval, gross sales reporting, and market classification.

## Contents

- **Customer Data Retrieval**
  - Functions to retrieve customer-specific data for Croma (India), including transaction data for the fiscal year 2021.
  - Definition and usage of the `get_fiscal_year` function for calculating fiscal years.

- **Monthly Product Transactions**
  - Scripts to join sales, product, and gross price data to generate monthly product-level sales transactions.

- **Gross Sales Report**
  - SQL query to generate a monthly gross sales report for Croma in India.

- **Stored Procedures**
  - `get_monthly_gross_sales_for_customer`: Procedure to generate a monthly gross sales report for specified customers.
  - `get_market_badge`: Procedure to classify markets as "Gold" or "Silver" based on total sales quantity.

## Getting Started

To run these scripts:
1. Ensure you have access to the required tables (`dim_customer`, `fact_sales_monthly`, `dim_product`, and `fact_gross_price`).
2. Execute the function and procedure definitions to set up reusable SQL functions and stored procedures.

### Requirements
- **SQL Database**: Compatible with databases supporting user-defined functions and stored procedures.

### Usage

- **User-Defined SQL Functions**: Use `get_fiscal_year` to simplify fiscal year calculations in queries.
- **Stored Procedures**:
  - Use `get_monthly_gross_sales_for_customer` to generate monthly sales reports for any customer.
  - Use `get_market_badge` to classify a market as "Gold" or "Silver" based on sales volume.

## Contributing

Contributions are welcome. Please submit a pull request for any improvements.

---


