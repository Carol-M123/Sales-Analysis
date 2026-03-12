# Sales Analysis

### Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)

### Project Overview
This long-term sales data aims to provide actionable insights that explain what is driving revenue growth, which products and customers contribute the most, and performance changes over time.

<img width="804" height="455" alt="Screenshot 2026-03-12 100047" src="https://github.com/user-attachments/assets/b9e38180-96a9-4d54-a66a-0e2087b29dce" />



### Data Sources
Sales Data : The primary dataset used in this analysis is the "sales_Data.Csv" file, containing detailed information about each sale made by particular customer in a certain region.

### Tools
- Excel - Data cleaning
- Power BI-creating Reports

### Data Cleaning
In the initial data preparation phase , we performed the following Tasks:
1. Data loading and inspection.
2. Handling missing values
3. Data cleaning and Formatting.

### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:
- Which products consistently generate the highest revenue?
- Are revenue changes driven by volume (quantity) or pricing effects?
- Which customers contribute most to growth, and how stable is their performance?
- How has sales performance evolved year-over-year across multiple economic cycles?

### Data Analysis
```Dax
YoY % Growth =
DIVIDE(
    [Total Sales] - [Sales Last Year],
    [Sales Last Year]
)
```
### Results
- A small group of products drives most revenue.
- Revenue growth is mainly volume-driven, not price-driven.
- Makamithi Enterprise and Ciira Agrovet are the biggest revenue contributors.
- Kithimani Agro Vet shows the fastest growth potential.
- Overall growth is stable but moderate across 2017–2025.
### Recommendations
- Focus marketing on top-selling products
- Introduce small price adjustments
- Strengthen relationships with top customers
- Support fast-growing customers
- Review low-performing products
- Expand distribution channels
- Use data dashboards for continuous monitoring

### Limitations
Key limitation of this analysis is that the data set only spans the first quarter of 2025, from january to March. As a result , any trends or patterns identified are limited to this period.

