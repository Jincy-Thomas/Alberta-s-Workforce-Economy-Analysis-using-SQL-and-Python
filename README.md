# Alberta Workforce and Economic Trends Analysis

## Project Overview

This project explores the relationship between employment levels, earnings, and industry economic output in Alberta over time. The analysis examines how labour market trends, workforce demographics, and economic growth interact across different industries.

The project focuses on understanding workforce dynamics, including gender and age-based employment patterns, full-time and part-time employment distribution, wage trends, industry growth, and the impact of major economic events such as the COVID-19 pandemic.

## Research Questions

The project investigates:

- How does gender-based employment vary across different industries?
- Which industries experienced the highest growth in female employment between 2001 and 2024?
- How do age groups differ across industries?
- What are the trends in full-time and part-time employment?
- Which industries have the highest and lowest average weekly earnings?
- How do employment levels compare with industry GDP performance?
- Which industries were most affected during the COVID-19 period?
- How have Alberta industries changed in terms of employment, wages, and economic output over time?

## Data Sources

The analysis uses publicly available datasets from **Statistics Canada**:

- Labour force characteristics by industry, annual  
  https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1410002301

- Average weekly earnings by industry, monthly  
  https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1410020301

- Employment by industry, monthly  
  https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1410020101

- Gross domestic product (GDP) at basic prices by industry and province  
  https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3610040201

## Technologies Used

- **Python**  
- **SQL / MySQL**  
- **Pandas** – data cleaning and transformation  
- **NumPy** – numerical analysis  
- **Matplotlib & Seaborn** – data visualization  
- **SQLAlchemy** – database connection and querying  
- **Jupyter Notebook** – analysis and reporting  

## Methodology

1. Collected and cleaned multiple labour market and economic datasets from Statistics Canada.
2. Processed missing values, inconsistencies, and redundant information.
3. Standardized industry categories across datasets and merged them.
4. Loaded cleaned datasets into a SQL database for efficient querying.
5. Performed SQL-based aggregation, filtering, ranking, and trend analysis.
6. Combined SQL queries with Python-based analysis and visualization.
7. Generated insights on employment patterns, wage trends, industry performance, and economic changes.

## Key Insights

- Alberta’s workforce distribution varies significantly across industries, with noticeable gender differences in employment patterns.
- Female employment increased substantially in several industries traditionally dominated by male workers.
- Healthcare, construction, and public administration showed strong growth in female workforce participation.
- Industry performance during COVID-19 varied significantly, with some sectors experiencing larger employment disruptions.
- Higher GDP-performing industries did not always experience lower employment impacts during economic disruptions.
- Wage levels, employment opportunities, and economic output differ considerably across industries.


