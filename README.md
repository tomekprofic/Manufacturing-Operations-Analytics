# Manufacturing Operations & Financial Performance Dashboard

## Project Overview
This Power BI project provides a comprehensive analysis of manufacturing plant operations. It integrates operational data with financial accounts to track performance across different hierarchies, from global regions to specific plant locations.

The goal of this dashboard is to enable data-driven decision-making by monitoring key metrics, comparing actuals against budgets, and identifying operational bottlenecks.

## Tech Stack & Tools
* **Power BI Desktop** – Data modeling and interactive visualization.
* **Power Query (M)** – Data cleaning and transformation (ETL) of CSV sources.
* **DAX (Data Analysis Expressions)** – Implementation of calculated measures and KPIs.
* **Data Sources:** Plant hierarchy data, account mappings, and operational fact tables.

## Data Architecture
The project follows a **Star Schema** approach to ensure high performance and scalability:
* **Fact Table (`Plant_FACT`):** Contains transactional data including actual values and budget figures.
* **Dimension Tables:**
    * `Plant_Hierarchy`: Geographical and organizational structure (Region -> Country -> Plant).
    * `Accounts`: Financial categorization and account details.

## Key Features & Insights
* **Hierarchical Drilling:** Users can analyze data at a high-level (Global/Region) and drill down into specific plants.
* **Financial vs. Operational Tracking:** Seamless integration of account-based reporting with plant-specific metrics.
* **Interactive Filtering:** Dynamic slicers for time periods, regions, and specific account types.
* **KPI Monitoring:** Clear visualization of performance indicators to track operational efficiency.

## What I Learned
1. **Data Modeling:** Designing a robust star schema to handle multi-level hierarchies.
2. **ETL Processes:** Using Power Query to transform raw CSV data (`Plant_FACT`, `Hierarchy`, `Accounts`) into a clean, report-ready format.
3. **Advanced DAX:** Creating measures to compare performance across different organizational levels.
4. **UI/UX for Analytics:** Designing an intuitive layout that balances high-level overviews with detailed data points.

