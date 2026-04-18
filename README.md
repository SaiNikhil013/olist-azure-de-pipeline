# Olist Revenue Intelligence Pipeline
Azure Medallion Architecture: ADF → ADLS Gen2 → Databricks → Delta Lake → dbt → Power BI

## Goal
Build an end-to-end Azure Data Engineering pipeline using:
ADF → ADLS Gen2 → Databricks (PySpark) → Delta Lake → dbt → Power BI  
following Medallion Architecture (Bronze/Silver/Gold).

## Status
Day 1 ✅ — Azure setup complete, Bronze layer populated, first ADF Copy pipeline running
- Created Azure Resource Group
- Created ADLS Gen2 Storage Account (Hierarchical namespace enabled)
- Created containers: bronze, silver, gold
- Created folder structure for Medallion architecture
- Uploaded raw Olist dataset CSV files into bronze/raw/olist

## Dataset
Olist Brazilian E-Commerce Dataset (~100k orders).

## Tech Stack
- Azure Data Factory (orchestration)
- ADLS Gen2 (data lake — Bronze/Silver/Gold)
- Azure Databricks (PySpark transformations) 
- Delta Lake (storage format)
- dbt (Gold layer models)
- Power BI (dashboards)
- Great Expectations (data quality)
- MLflow (experiment tracking)
