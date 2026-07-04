# FootSight Analytics

## Overview

FootSight Analytics is an end-to-end Business Intelligence project designed to support football scouting and player recruitment through interactive dashboards and data-driven insights.

The project demonstrates the complete BI workflow, from data extraction and transformation to data modeling and dashboard development using Power BI. It enables users to analyze player performance, compare athletes, and identify scouting opportunities through interactive visualizations.

---

## Project Objectives

- Build an end-to-end Business Intelligence solution for football scouting.
- Transform raw player data into meaningful business insights.
- Design interactive Power BI dashboards for decision-making.
- Develop a reusable ETL pipeline for data preparation.
- Create a scalable data model following BI best practices.

---

## Features

- Interactive Power BI dashboards
- Executive Summary dashboard
- Player Profile dashboard
- Deep Dive Analysis dashboard
- ETL pipeline using Python
- Cleaned and transformed datasets
- Data model and schema documentation
- Performance KPIs and player comparisons

---

## Dashboard Pages

### Executive Summary

Provides a high-level overview of player statistics and key performance indicators.

Key insights include:

- Total players analyzed
- Position distribution
- Average player ratings
- Overall performance metrics
- Recruitment overview

---

### Player Profile

Allows users to analyze individual players through detailed statistics such as:

- Technical attributes
- Physical attributes
- Performance metrics
- Position-specific analysis
- Player comparisons

---

### Deep Dive Analysis

Provides advanced analytics including:

- Position comparisons
- Attribute distributions
- Performance trends
- Interactive filtering
- Recruitment insights

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Data Transformation (ETL)
4. Data Modeling
5. Measure Creation (DAX)
6. Dashboard Development
7. Data Visualization
8. Business Insight Generation

---

## Repository Structure

```
FootSight-Analytics/
│
├── BI Dashboard/
│   ├── FootSight Analytics.pbix
│   ├── Executive Summary.png
│   ├── Player Profile.png
│   └── Deep Dive Analysis.png
│
├── Dataset/
│   ├── football_scouting_dataset_10000_players.xlsx
│   └── FootSight_Clean_Dataset.csv
│
├── ETL/
│   ├── FootSight_ETL_Notebook.ipynb
│   └── FootSight_Data_Dictionary.xlsx
│
├── Model/
│   ├── FootSight Schema.jpg
│   └── FootSight_measures_definitions.pdf
│
├── Report/
│   └── FootSight-BI-Project.pdf
│
├── Use Case/
│   └── Use Case FootSight Analytics.pdf
│
└── README.md
```

---

## Technologies Used

- Power BI
- Python
- Pandas
- Jupyter Notebook
- Excel
- DAX (Data Analysis Expressions)
- Power Query
- Data Modeling

---

## Data Pipeline

The ETL process includes:

- Importing raw player data
- Cleaning missing and inconsistent values
- Standardizing attributes
- Feature engineering
- Exporting cleaned datasets for Power BI

---

## Data Model

The project includes a structured data model designed to support efficient reporting and analytics.

Documentation includes:

- Data schema
- Measure definitions
- Relationships
- Data dictionary

---

## Business Insights

The dashboard helps answer questions such as:

- Which players perform best by position?
- What attributes contribute most to player performance?
- Which players fit specific scouting criteria?
- How do players compare across different metrics?
- Which positions require recruitment attention?

---

## Dashboard Preview

The repository contains screenshots of:

- Executive Summary
- Player Profile
- Deep Dive Analysis

The full interactive dashboard is available in:

```
BI Dashboard/FootSight Analytics.pbix
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/FootSight-Analytics.git
```

Open the Power BI report:

```
BI Dashboard/FootSight Analytics.pbix
```

To execute the ETL process:

```bash
cd ETL
```

Launch the notebook:

```bash
jupyter notebook FootSight_ETL_Notebook.ipynb
```

---

## Learning Outcomes

This project demonstrates practical experience with:

- Business Intelligence
- Power BI Dashboard Development
- Data Visualization
- ETL Processes
- Data Cleaning
- Data Modeling
- DAX Measures
- Business Analytics
- KPI Design
- Sports Analytics

---

## Future Improvements

- Real-time player statistics integration
- SQL database backend
- Automated data refresh
- Predictive player valuation
- Machine learning for player recommendation
- Deployment using Power BI Service

---

## Author

**Aateff**

---

## License

This project is intended for educational and portfolio purposes.
