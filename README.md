# Power BI Sales Analysis Dashboard

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#resultsfindings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

---

## Project Overview
This project showcases an interactive sales analysis dashboard built using Power BI. It focuses on leveraging a custom date table, matrix charts, calendar heatmaps, and advanced DAX calculations to provide comprehensive insights into sales performance. The goal was to enhance data import efficiency, optimize the analysis of 150,000+ sales records, and provide stakeholders with real-time decision-making tools.

## Data Sources
- **Sales Records**: Data comprises over 150,000 sales transactions.
- **Custom Date Table**: A custom date table was created to enable time-based trend analysis, including columns such as day names, week numbers, and month names for more detailed insights.

## Tools
- **Power BI**: For building the dashboard and creating visualizations.
- **Python**: To optimize data import from CSV to SQL, reducing time from 1 hour to 12 seconds.
- **SQL**: For cleaning and preparing large datasets for analysis.
- **DAX (Data Analysis Expressions)**: To calculate daily average sales, identify performance trends, and highlight above/below-average metrics.

## Data Cleaning/Preparation
- Cleaned and standardized the sales data in SQL to remove inconsistencies and errors.
- Optimized the data import process by reducing the CSV-to-SQL import time by over 99.7% using Python, making the data processing more efficient.

## Exploratory Data Analysis
Key initial insights focused on:
- Identifying weekly and daily sales patterns using the date table.
- Visualizing peak sales periods across different time frames to uncover seasonal trends.

## Data Analysis
The analysis section includes:
- **Custom Date Table**: A fully developed date table to facilitate detailed time-based analysis, including day names, week numbers, month names, and numbers.
- **Matrix Chart**: Used to display sales in a calendar format, enabling easy tracking of sales patterns over weeks and months.
- **Calendar Heatmap**: A visual representation of sales volumes, color-coded to quickly identify low and high sales days.
- **DAX Calculations**: Implemented DAX to compute daily average sales, and highlighted days with above and below average performance to aid quick decision-making.

## Results/Findings
- **Data Import Optimization**: Reduced data import time by over 99.7%, from 1 hour to 12 seconds, significantly enhancing the efficiency of the data analysis process.
- **Granular Insights**: Custom date columns (day names, week numbers, etc.) allowed for a deeper understanding of sales trends and seasonal patterns.
- **Improved Decision-Making**: The dashboard provided stakeholders with real-time insights into sales performance, enabling better-informed decisions.
- **Visual Impact**: Matrix charts and heatmaps made complex sales data more accessible, simplifying the process of identifying key trends.

## Recommendations
- **Enhance Visuals**: Incorporate additional custom visuals to make insights even more intuitive for users.
- **Extend Date Table**: Include holiday markers or other important business events in the date table to improve trend analysis.

## Limitations
- **Historical Data Only**: The analysis is based on historical data; adding real-time data sources could provide even more actionable insights.
- **External Data**: Including external factors (e.g., economic indicators) could further enhance the analysis.

## References
- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- [DAX Guide](https://dax.guide/)
- [SQL Documentation](https://www.mysql.com/)
