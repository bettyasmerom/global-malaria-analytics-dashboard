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
