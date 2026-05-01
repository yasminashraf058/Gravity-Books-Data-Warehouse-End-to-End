# Gravity Books: End-to-End Data Warehouse & BI Project

## Overview
This project demonstrates the complete transformation of raw transactional data into strategic business insights.

It covers the full data lifecycle, starting from raw transactional data in an OLTP database, followed by data warehousing, analytical processing, and business intelligence reporting.

---

## Project Objectives
- Transform raw bookstore transactional data into a structured analytical environment.
- Build a scalable Data Warehouse for reporting and analysis.
- Enable historical tracking of business data changes.
- Deliver interactive dashboards for business decision-making.

---

## Technical Architecture

### Source System
- Raw transactional data from the **Gravity Books** bookstore system.
- Database platform: **Microsoft SQL Server (OLTP)**.

### Data Warehouse Design
- Designed and implemented a **Snowflake Schema** to:
  - Reduce data redundancy.
  - Improve data organization.
  - Support scalable reporting and analytics.

### ETL Pipelines
- Built ETL workflows using **SQL Server Integration Services (SSIS)**:
  - Extract data from source systems.
  - Transform and cleanse data.
  - Load processed data into the Data Warehouse.

### Historical Data Management
- Applied **Slowly Changing Dimensions (SCD)** for maintaining historical records and tracking data changes over time.

### Analytical Layer
- Developed an **SSAS Cube** to support:
  - OLAP analysis.
  - Fast aggregations.
  - Multi-dimensional exploration of business metrics.

### Business Intelligence
- Created interactive dashboards in **Power BI** to visualize:
  - Sales performance.
  - KPIs.
  - Trends and patterns.

---

## Business Insights Generated
- Best-selling books and top-performing categories.
- Customer purchasing behavior analysis.
- Seasonal sales trends and peak sales periods.
- Regional performance comparisons.

---

## Tech Stack

| Category | Technology |
|---|---|
| Database | Microsoft SQL Server |
| Data Warehouse | SQL Server |
| ETL | SSIS |
| Analysis | SSAS |
| Data Modeling | Snowflake Schema |
| Visualization | Power BI |

---

## Project Workflow
OLTP Database → ETL (SSIS) → Data Warehouse (Snowflake Schema) → SSAS Cube → Power BI Dashboard

