# Online Retail Sales Analysis | Python, Pandas & PostgreSQL

## Project Overview

This project analyses an online retail transaction dataset using Python (Pandas) and PostgreSQL to understand sales performance, customer purchasing patterns, product demand, and cancelled transactions.

The objective is to clean and analyse retail data, identify meaningful business trends, and translate the results into actionable insights.

## Business Objectives

- Identify top-performing countries by revenue.
- Analyse monthly sales trends and seasonality.
- Identify products contributing to sales and revenue.
- Examine cancelled transactions and their impact on product rankings.
- Investigate data quality issues that may affect business reporting.

## Dataset

The project uses an online retail transaction dataset containing invoice details, product descriptions, quantities, unit prices, customer IDs, and country information.
**Dataset source:** (https://github.com/cynthia-ugochinyerem/SQL-RETAIL-STORE-MANAGEMENT)

The dataset contains retail transactions from a UK-based online retailer. The original dataset is available from the source linked above.

## Key Findings

- **Geographic performance:** The United Kingdom contributed approximately 85% of total revenue.
- **Monthly sales trend:** November 2011 was the peak sales month, generating approximately £1.5 million in revenue.
- **Returns and cancellations:** Cancelled or returned transactions accounted for approximately 8.4% under the project's chosen calculation.
- **Data quality:** Cancelled transactions involving top-selling products and non-product codes, such as `DOT` and `POST`, could distort product rankings if not handled appropriately.

These findings demonstrate why transaction status, product identifiers, and data cleaning decisions matter when interpreting retail performance.

## Business Recommendations

- Monitor sales concentration in the UK while evaluating opportunities in other markets.
- Prepare inventory and fulfilment plans ahead of peak sales periods.
- Analyse cancelled and returned transactions to identify potential operational issues.
- Exclude or separately classify non-product codes when ranking products.
- Apply consistent transaction filters and validate revenue calculations before presenting business results.

## Project Structure

- `README.md` — Project overview, tools, and findings.
- `*.ipynb` — Python notebook containing data cleaning and analysis, if included.
- `*.sql` — PostgreSQL queries used for analysis, if included.

## Conclusion

This project demonstrates how Python, Pandas, and PostgreSQL can be used together to clean retail transaction data, analyse sales performance, identify trends, and investigate data quality issues.
The analysis highlights the importance of handling cancellations, returns, and non-product transactions correctly to produce reliable business insights.

## Tools & Technologies

- **Python:** Data analysis and data cleaning
- **Pandas:** Data manipulation, filtering, aggregation, and exploratory data analysis
- **PostgreSQL:** SQL-based analysis and querying
- **Jupyter Notebook / Google Colab:** Python development environment
- **GitHub:** Project documentation and version control

## SQL & Python Skills

- Data cleaning and validation
- Handling missing values
- Filtering and sorting data
- Aggregations and grouping
- SQL joins and subqueries
- Date-based sales analysis
- Revenue calculations
- Exploratory data analysis (EDA)
- Identifying cancelled transactions and data quality issues

## Author

**Ruchika Bisoi**

Aspiring Data Analyst | SQL | Python | PostgreSQL | Power BI

[GitHub](https://github.com/RuchikaBisoi) | [LinkedIn](https://www.linkedin.com/in/ruchika-bisoi/)
