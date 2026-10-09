# Sales Performance Analytics | SQL, Power BI & Excel

## Project Overview

Sales Performance Analytics is a business intelligence project focused on analyzing sales transactions, customer behavior, product performance, and budget comparisons.

The project demonstrates an end-to-end analytics workflow using SQL for data extraction and transformation, Excel for budget data, and Power BI for interactive reporting.

**Project Status:** Open-source project under review and further development.

## Tech Stack

- **SQL Server / T-SQL:** Data extraction, cleaning, transformation, and joins
- **Power BI:** Data modeling, interactive dashboards, and KPI visualization
- **Excel:** Sales budget data
- **Power Query:** Data preparation
- **DAX:** Calculated measures and business KPIs

## Business Objectives

The analytics solution is designed to answer important business questions:

1. How does sales performance change over time?
2. Which products and categories contribute the most revenue?
3. Who are the highest-value customers?
4. How do actual sales compare with budget targets?
5. Which sales trends can support business decisions?

## Dataset Description

The project uses sales data organized into fact and dimension tables.

| Dataset | Description |
|---|---|
| DIM_Customer | Customer information |
| DIM_Product | Product and category details |
| DIM_Calendar | Date and calendar information |
| FACT_InternetSales | Sales transaction records |
| SalesBudget | Sales budget information |

These datasets are combined to support sales performance reporting.

## Project Workflow

### 1. Data Extraction and Cleaning

SQL scripts prepare the sales data for analysis.

Key operations include:

- Selecting relevant business attributes
- Joining related dimension tables
- Handling missing values
- Applying transformations
- Exporting prepared datasets as CSV files

### 2. Data Modeling

Power BI connects the prepared datasets using relationships between fact and dimension tables.

The model supports analysis across customers, products, dates, and sales transactions.

### 3. Data Visualization

The Power BI report supports analysis of:

- Total sales and sales trends
- Sales versus budget
- Customer-wise sales performance
- Product-wise sales performance
- Monthly and yearly revenue patterns
- Interactive filtering and drill-down analysis

### 4. Business Reporting

The dashboard is intended to support performance monitoring and data-driven sales decisions.

## Repository Structure

```text
Sales-Performance-Analytics/
│
├── README.md
│
├── DIM_Calendar_Clean.sql
├── DIM_Customer_Clean.sql
├── DIM_Product_Clean.sql
├── FACT_InternetSales_Clean.sql
│
├── DIM_Calendar_Export.csv
├── DIM_Customer_Export.csv
├── DIM_Product_Export.csv
├── FACT_InternetSales_Export.csv
│
├── Sent Over Data - SalesBudget.xlsx
│
├── Sales Report.pbix
├── Sales Report.pdf
│
├── Example Business Request.docx
└── Business Demand Overview & User Stories.docx
```

## Dashboard

The repository includes a Power BI report and a PDF export.

**[View Dashboard PDF](Sales%20Report.pdf)**

To explore the interactive report, download `Sales Report.pbix` and open it using Power BI Desktop.

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/shashankkachouli/Sales-Performance-Analytics.git
```

2. Open the SQL scripts to review the data preparation logic.

3. Explore the exported CSV datasets and Excel budget file.

4. Open `Sales Report.pbix` in Power BI Desktop.

5. Refresh or configure the data sources if required.

## Skills Covered

- SQL data manipulation and joins
- Relational data modeling
- Business KPI analysis
- Sales and budget reporting
- Dashboard development
- Data visualization
- Business intelligence concepts

## Future Improvements

- Add customer segmentation analysis
- Introduce additional DAX measures
- Implement year-over-year growth analysis
- Expand sales forecasting and trend analysis
- Document validated business insights

## Repository Maintainer

**Shashank Kachouli**

[GitHub Profile](https://github.com/shashankkachouli)
