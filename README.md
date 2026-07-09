# Global Malaria Trends Dashboard

An interactive Power BI dashboard analyzing global malaria trends from 2010–2017 to evaluate progress toward the WHO 2030 malaria elimination goal.

## Project Overview

This project uses WHO malaria case and mortality data to identify global trends, regional disparities, high-burden areas, and opportunities for targeted public health intervention.

## Tools Used

- Power BI
- SQL
- Excel
- Power Query
- DAX
- GitHub

## Key Questions

- Are malaria cases and deaths declining fast enough to support the WHO 2030 elimination goal?
- Which WHO regions carry the highest malaria burden?
- Where are cases or deaths increasing year-over-year?
- How can data support better resource allocation?

## Key Deliverables

- Interactive Power BI dashboard
- Executive case study presentation
- Data cleaning workflow
- DAX measures
- Strategic recommendations

- ## Dataset

The dataset was sourced from Kaggle and contains malaria case and death records by country, year, and WHO region.

Dataset: Malaria Dataset by imdevskp  
https://www.kaggle.com/datasets/imdevskp/malaria-dataset

## Data Preparation

The data preparation process included:

- Removing duplicate records in Excel
- Validating country, year, case, and death fields
- Cleaning and standardizing data using SQL
- Transforming data types in Power Query
- Replacing null values where appropriate
- Formatting year fields correctly for time-based analysis

## Dashboard Features

- KPI cards for cases, deaths, YoY growth, and death rate
- Year slicer for dynamic filtering
- Trend analysis by year
- WHO regional comparison
- Geographic map with country-level tooltips
- Bubble chart analyzing cases YoY, deaths YoY, and death rate

- ## Key Insights

Analysis of WHO malaria data (2010–2017) revealed several important findings:

- Global malaria mortality continued to decline throughout the study period.
- Malaria cases and deaths remained heavily concentrated in a small number of high-burden WHO regions.
- Regional disparities suggest targeted interventions are needed to achieve the WHO 2030 malaria elimination goal.
- Interactive filtering enables executives to compare trends across years, regions, and countries.
- Geographic visualization helps identify disease hotspots for resource prioritization.

- ## Dashboard Preview

### Executive Dashboard

![Dashboard Overview](images/dashboard-overview.png)

### Trend Analysis

![Trend Analysis](images/trend-analysis.png)

### Geographic Intelligence

![Geographic Analysis](images/geographic-analysis.png)

### Correlation Analysis

![Correlation Analysis](images/correlation-analysis.png)

## Repository Structure

```
global-malaria-analytics-dashboard/
│
├── Dashboard/
│   ├── Malaria Dashboard.pbix
│   └── Interactive Dashboard.html
│
├── Presentation/
│   └── Global Malaria Analytics Case Study.pdf
│
├── SQL/
│   └── Data Cleaning.sql
│
├── Images/
│   ├── dashboard-overview.png
│   ├── trend-analysis.png
│   ├── geographic-analysis.png
│   └── correlation-analysis.png
│
└── README.md
```
