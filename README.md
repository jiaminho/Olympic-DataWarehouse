# Data Warehouse Design and Multidimensional Analysis on Olympic Dataset

## Overview
This project focuses on designing a data warehouse for analyzing Olympic datasets using multidimensional analysis. It incorporates business intelligence concepts, data transformation techniques, and visualization tools to derive meaningful insights from Olympic data.

## Dataset
The dataset includes historical records from both the Summer and Winter Olympics (1896-2022), along with additional datasets on health, demographics, and economics:
- **Olympic Hosts**: Locations and details of Olympic Games.
- **Olympic Medals**: Medal counts by country and discipline.
- **Health Data**: Mental illness and life expectancy metrics.
- **Economic Data**: GDP per capita, population, and economic indicators.

## Data Warehouse Design
- **Schema**: Implements a **Star Schema** with a central fact table connected to dimension tables (Countries, Years, Games, Disciplines).
- **ETL Process**: Extract, Transform, and Load (ETL) operations performed using Python and PostgreSQL to clean and structure data.
- **Multidimensional Cube**: Built using **Atoti** for advanced analytics.

## Business Queries
Analyzing Olympic performance for **Australian and French Governments**:
- Correlation between GDP and Olympic success.
- Medal distributions across different sports.
- Impact of life expectancy and mental health on athlete performance.
- Effect of hosting the Olympics on national success.
- Historical ranking of top Olympic-performing countries.

## Implementation
- **ETL Pipeline**: Jupyter Notebook-based data extraction, transformation, and loading into PostgreSQL.
- **Visualization**: Utilized **Tableau** and **Atoti** for interactive data analysis.
- **Association Rule Mining**: Identified patterns in Olympic success using **Apriori algorithm**.
- **What-If Analysis**: Simulated the impact of increased health expenditure on medal counts.

