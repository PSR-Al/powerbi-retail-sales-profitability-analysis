# Power BI – Retail Sales and Profitability Analysis

This project presents an interactive **Power BI dashboard** designed to analyze the commercial performance of a retail company. The analysis focuses on **sales, customers, and product returns** in order to identify opportunities to improve profitability and support data-driven decision making.

The dataset contains **fictional retail data** covering the period **2023–2025**.

---

# Objective

The main objective of this project is to analyze the commercial performance of a retail company through different business indicators.

The dashboard allows users to explore:

- Sales trends over time
- Customer purchasing behavior
- Product category performance
- Product returns and their impact on profitability

By combining these indicators, the dashboard helps identify patterns and opportunities to improve business efficiency and profitability.

---

# Dataset

The dataset used in this project contains fictional data from a retail company and includes information related to:

- Sales transactions
- Customers
- Product catalog
- Product returns
- Revenue and profitability indicators

**Period analyzed:** 2023–2025

The data is structured to allow analysis from different perspectives such as products, customers, sales channels and time.

---

# Data Model

The dashboard is built using a **star schema data model**, a common structure in business intelligence and analytical systems. This type of model organizes information into **fact tables**, which store the main business metrics, and **dimension tables**, which provide descriptive context for analysis.

This structure allows efficient aggregation of metrics and flexible analysis across multiple dimensions.

## Fact Tables

**FactSales**

Contains information about the sales transactions performed by the company, including key metrics such as:

- Quantity sold
- Revenue generated

**FactReturns**

Stores information related to product returns, including:

- Quantity returned
- Refunded amount

These tables contain the core measurable events of the business.

## Dimension Tables

**DimProduct**

Contains product information that allows analysis at different levels of the product hierarchy:

- Category
- Subcategory
- Brand
- SKU

**DimCustomer**

Contains customer attributes used for segmentation and behavioral analysis:

- Customer segment
- Gender
- Age

**DimDate**

Calendar table used for temporal analysis, enabling:

- Yearly comparisons
- Monthly trends
- Time-based metrics

**DimChannel**

Represents the sales channel through which transactions occur, such as:

- Physical store
- Online sales

---

# Key Business Metrics

Several additional metrics were calculated directly in Power BI using **DAX (Data Analysis Expressions)** to enable deeper analysis of business performance.

## Revenue YTD (Year to Date)

Revenue accumulated from the beginning of the year up to the current date.

This metric allows monitoring of revenue performance throughout the year.

## Year-over-Year Revenue Growth (%)

Measures the percentage increase or decrease in revenue compared to the same period in the previous year.

This indicator helps evaluate business growth trends.

## Profit

Represents the net gain obtained after subtracting the costs associated with sales.

## Profit Margin (%)

Measures profitability as a percentage of total revenue.

This metric allows the evaluation of how efficiently revenue is converted into profit.

## Rolling 12-Month Revenue

Revenue accumulated over a **moving 12-month window**, which helps analyze long-term trends while reducing seasonal fluctuations.

## Average Order Value (AOV)

Measures the average revenue generated per order.

This indicator helps evaluate customer purchasing behavior.

## Pareto Revenue Contribution (%)

Applies the **Pareto principle (80/20 rule)** to identify the customers, products or channels responsible for the largest share of revenue.

This helps detect the most valuable segments of the business.

---

# Dashboard Features

The Power BI dashboard includes multiple interactive visualizations that allow users to explore the data dynamically:

- Time-based sales analysis
- Product category comparisons
- Customer segmentation analysis
- Product return analysis
- Profitability indicators
- Channel performance comparison

These visualizations make it possible to analyze the business from different perspectives and identify factors that influence commercial performance.

---

# Technologies Used

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Data modeling**
- **Star schema design**
- **Business intelligence and data visualization techniques**

---

# Project File

The interactive dashboard is available in the following file:

`Retail_Analysis.pbix`

To explore the dashboard, download the file and open it using **Power BI Desktop**.

---

# Purpose of the Project

This project was developed as a **data analysis and business intelligence exercise** to demonstrate how Power BI can be used to analyze commercial performance in the retail sector.

The dashboard illustrates how combining sales data, customer information and return metrics can provide valuable insights that support strategic decision-making and help improve overall business profitability.
