# Olist Commerce Intelligence
### End-to-End Data Warehouse & Business Intelligence Solution

## Overview
Olist Commerce Intelligence is an end-to-end e-commerce analytics project built using Microsoft Fabric and Power BI. It transforms Brazilian e-commerce data into structured analytical datasets and interactive dashboards to support business decision-making.

## Project Objectives
- Build a medallion data architecture using Bronze, Silver, and Gold layers.
- Develop reusable fact and dimension tables for analytical reporting.
- Automate data processing and validation using Microsoft Fabric pipelines.
- Create a semantic model with DAX measures.
- Deliver interactive dashboards for sales, delivery, payment, and customer review analysis.

## Technology Stack
- **Data Platform:** Microsoft Fabric
- **Data Processing:** Fabric Lakehouse and SQL
- **Data Warehouse:** Fact and dimension tables
- **Orchestration:** Fabric Data Pipelines
- **Data Modeling:** Semantic Model and DAX
- **Visualization:** Power BI
- **Dataset:** Brazilian E-Commerce Public Dataset by Olist (Kaggle)

## Architecture
1. **Bronze:** Raw source data ingestion.
2. **Silver:** Data cleaning, transformation, and reconciliation.
3. **Gold:** Analytical fact and dimension tables.
4. **Semantic Model:** Relationships and reusable DAX measures.
5. **Dashboards:** Interactive business intelligence reports.

## Dashboard Pages

### 1. Executive Overview
High-level business KPIs, including total orders, total sales value, average order value, and delivery completion rate.

### 2. Sales & Products
Product revenue, items sold, freight value, monthly sales trends, and product category performance.

### 3. Delivery & Operations
On-time delivery rate, late delivery rate, average delivery days, and delivery performance analysis.

### 4. Payments & Customer Reviews
Payment value, transaction analysis, payment types, review scores, and customer feedback indicators.

## Data Quality and Validation
The pipeline includes profiling, reconciliation, and Gold-layer validation activities to help maintain reliable analytical data.

## Repository Structure
- `docs/` — Architecture, data model, and pipeline documentation
- `screenshots/` — Dashboard screenshots
- `sql/` — SQL scripts for warehouse tables and validation
- `dax/` — DAX measure documentation
- `pipeline/` — Pipeline documentation
- `data/` — Dataset notes and source information

## Key Learning Outcomes
- Medallion architecture and data engineering
- Dimensional data modeling
- Pipeline orchestration and data quality checks
- Semantic modeling and DAX
- Interactive dashboard development
- Translating operational data into business insights

## Dataset
The project uses the Brazilian E-Commerce Public Dataset by Olist, available on Kaggle. Refer to the original dataset page for source information and applicable terms.

## Notes
This repository documents the project implementation. Microsoft Fabric workspace resources and connected semantic models may require separate access and are not automatically published through GitHub.

