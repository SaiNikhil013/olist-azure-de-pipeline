# Olist Revenue Intelligence Pipeline
Azure Medallion Architecture: ADF → ADLS Gen2 → Databricks → Delta Lake → dbt → Power BI

## Status
Day 1 ✅ — Azure setup complete, Bronze layer populated, first ADF Copy pipeline running

## Tech Stack
- Azure Data Factory (orchestration)
- ADLS Gen2 (data lake — Bronze/Silver/Gold)
- Azure Databricks (PySpark transformations) 
- Delta Lake (storage format)
- dbt (Gold layer models)
- Power BI (dashboards)
- Great Expectations (data quality)
- MLflow (experiment tracking)
