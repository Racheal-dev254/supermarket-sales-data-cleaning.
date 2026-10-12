# Supermarket Sales Data Cleaning and Analysis

## Project type
Independent practice project using synthetic data.

## Objective
Demonstrate a reproducible workflow for inspecting, cleaning,
validating, analyzing, and visualizing supermarket sales data.

## Tools
- Python
- pandas
- NumPy
- Matplotlib
- Google Colab

## Data quality issues investigated
- Exact duplicate records
- Missing quantities and unit prices
- Inconsistent text formatting
- Missing product category
- Invalid date
- Negative quantity
- Incorrect recorded sales total

## Cleaning approach
Exact duplicate rows were removed. Recoverable values were derived
using documented assumptions appropriate to this synthetic dataset.
Product and category text was standardized. Invalid dates and
non-positive or missing quantities/prices were excluded from the
analytical dataset and recorded in an exclusion report.
Sales totals were recalculated as quantity multiplied by unit price.

## Analysis
The project calculates revenue, units sold, transaction counts,
average transaction value, product performance, category performance,
and monthly revenue.

## Deliverables
- supermarket_sales_cleaned.csv
- excluded_records_audit.csv
- product_performance.csv
- category_performance.csv
- monthly_revenue.png
- revenue_by_product.png
- revenue_by_category.png

## Limitations
All transactions are synthetic and created for practice. They do not
represent actual business records or verified commercial findings.
Derived values rely on the stated assumptions and should be confirmed
against source records in a real client engagement.

## Reproducibility
The notebook contains the code used to generate, clean, validate,
analyze, and visualize the dataset.