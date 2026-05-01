# Gravity Books: End-to-End Data Engineering & Analytics Project

## Project Overview
This project demonstrates the complete transformation of raw transactional data into strategic business insights. It covers the entire data lifecycle, from managing a source OLTP database to architecting a Cloud Data Warehouse and delivering interactive visualizations.

## Technical Architecture
The solution is built on a robust data pipeline consisting of the following stages:
* **Source System:** Raw transactional data from the Gravity Books bookstore system.
* **Data Modeling:** Implementation of a Snowflake Schema to optimize analytical query performance.
* **Cloud Warehousing:** Migration and storage of analytical data using **Snowflake**.
* **ETL Pipelines:** Automated data extraction, transformation, and loading using SQL Server Integration Services (SSIS).
* **Historical Data Management:** Application of Slowly Changing Dimensions (SCD) Type 2 to maintain a history of data changes.
* **Analytical Layer:** Development of an SSAS Cube for advanced multi-dimensional analysis (OLAP).
* **Business Intelligence:** Interactive dashboards created in Power BI to monitor KPIs and trends.

## Tech Stack
* **Cloud Platform:** Snowflake
* **RDBMS:** Microsoft SQL Server
* **ETL Tool:** SSIS
* **Analysis Tool:** SSAS
* **BI & Visualization:** Power BI

