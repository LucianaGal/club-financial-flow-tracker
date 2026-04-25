# Club Financial Flow Tracker

## Overview

A financial tracking and analysis system built in Excel using Power Query to consolidate multiple income streams, monitor payment status and analyse cash flow across hockey clubs.
---

## Dashboard Preview

![Dashboard](screenshots/dashboard_overview.png)

## Objective

The objective of this project is to:

* Track income across multiple clubs and payment structures
* Monitor expected versus paid revenue
* Identify unpaid income and potential cash flow risks
* Analyse income distribution and dependency by club
* Provide an interactive dashboard to support decision-making

---

## Data Model

Data is collected from multiple sources and transformed using Power Query into a centralised structure.

## Data Sources

The project integrates multiple data sources, structured as follows:

- **data/base**  
  - clubs_earning_details.xlsx (processed and unified dataset)

- **data/sources**  
  - days_detailed_stages.xlsx  
  - games_detailed_orange_titans.xlsx  
  - hours_detailed_blue_warriors.xlsx  
  - hours_detailed_emerald_demons.xlsx  

- **screenshots**  
  - dashboard_overview.png  
  - kpi_summary.png  
  - filters_slicers.png  

- **README.md**  
  - project documentation  

All sources are combined using Power Query into a unified dataset.


All sources are combined using Power Query into a unified dataset.

## Project Structure

- data/base: processed and unified dataset
- data/sources: raw input files used for data integration
- screenshots: visual representation of the dashboard, key metrics and interactive filters
- README: project documentation

### Transformation

* Data cleaning and standardisation
* Appending multiple datasets
* Creation of time-based fields such as Year and Month
* Categorisation by income type and club

### Output

* A unified fact table used for analysis and visualisation

---

## Dashboard Features

The dashboard provides an interactive overview of financial performance.

### Key KPIs

* Total Earned
* Paid
* Total Pending
* Collection Rate
* Projected Income
* Total Expected

### Visual Analysis

* Income distribution by club
* Monthly income comparing expected versus paid
* Payment breakdown per club
* Projected income by club

### Filters

* Year
* Club
* Month

![Filters](screenshots/filters_slicers.png)

---

## Key Insights

* Emerald Demons generates over 50 percent of total revenue, indicating a strong dependency on a single source
* A share of expected income remains unpaid, impacting short term cash flow
* Income shows clear seasonality, with peaks during specific periods of the year
* Revenue streams vary across clubs, combining hourly, daily, retainer and project based models, which affects predictability

![KPIs](screenshots/kpi_summary.png)

---

## Tools Used

* Excel
* Power Query
* Pivot Tables
* Data modelling techniques
* Dashboard design and data visualisation

---

## Outcome

This project demonstrates the ability to:

* Design a structured data model
* Build an ETL process using Power Query
* Create interactive dashboards
* Translate raw data into meaningful business insights

---

## Notes

This is a real world inspired project based on multi source income tracking, showcasing how Excel can be used as a complete analytical tool beyond basic spreadsheet usage.
