# South Africa's Electricity Generation Mix Analysis

## Project Overview

This project explores South Africa's electricity generation mix, renewable energy growth and electricity-sector emissions using the **Ember Yearly Electricity Data** dataset.

The objective is to analyse historical electricity generation trends, understand the country's dependence on different energy sources, evaluate the growth of renewable energy and examine changes in electricity-related emissions.

The project uses SQL for data exploration, cleaning, querying and analysis, with Tableau planned for data visualisation and dashboard development.

## Project Objectives

The analysis aims to answer the following questions:

1. How has South Africa's electricity generation changed over time?
2. What percentage of electricity generation comes from coal?
3. How quickly are solar and wind generation growing?
4. How have electricity-sector emissions changed over time?
5. How does South Africa compare with other countries?

## Dataset

**Source:** [Ember – Yearly Electricity Data](https://ember-energy.org/data/)

The dataset contains historical electricity data across countries and geographical regions, including information on:

- Electricity generation (TWh)
- Generation year-on-year changes
- Electricity generation shares (%)
- Installed generation capacity (GW)
- Electricity-sector emissions (MtCO2e)
- Emissions intensity (gCO2e/kWh)
- Electricity generation sources
- Geographical classifications

The dataset was downloaded, cleaned and imported into MySQL for analysis.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| MySQL Workbench | Data exploration, querying and analysis |
| SQL | Data manipulation, aggregation and analytical queries |
| Tableau | Data visualisation and dashboard development |
| GitHub | Project documentation and version control |

## SQL Analysis

The SQL analysis focuses on the following areas:

### 1. Data Exploration & Quality Checks
- Examining the dataset structure.
- Identifying the number of records and geographical areas.
- Exploring the available electricity generation sources.
- Investigating missing values and data quality.

### 2. Electricity Generation Analysis
- Analysing historical electricity generation trends.
- Calculating coal's contribution to total electricity generation.
- Investigating the growth of solar and wind generation.
- Comparing electricity generation across different years.

### 3. Emissions Analysis
- Analysing annual electricity-sector emissions.
- Investigating year-on-year emissions changes.
- Examining electricity emissions intensity.

## Tableau Visualisation

The next stage of the project involves developing an interactive Tableau dashboard to communicate the findings.

Planned visualisations include:

- Electricity generation trends over time.
- Electricity generation mix by source.
- Coal versus renewable electricity generation.
- Solar and wind generation growth.
- Electricity-sector emissions trends.

## Key Findings

*Key findings and analytical insights will be added following completion of the SQL analysis and Tableau visualisations.*

## Project Structure

```text
South-Africa-Electricity-Analysis/
│
├── Dataset/
│   └── release_generation_yearly_global..csv
│
├── SQL/
│   └── electricity_analysis.sql
│
├── emissions Visualisation.png
│
├── Findings/
│   └── project_findings.md
│
└── README.md
```

## About This Project

This is an independent data analytics portfolio project demonstrating practical SQL skills, data exploration, analytical thinking and data visualisation.

The project also explores how data analytics can be applied to the energy sector to better understand electricity generation patterns, renewable energy development and emissions trends.
