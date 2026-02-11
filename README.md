# bikes-databricks-pipeline
Data Engineering pipeline on Azure Databricks using Medallion Architecture (Bronze, Silver, Gold), with PySpark, Delta Lake and job orchestration via Databricks Workflows.

# Notes
These notebooks are part of a Databricks Medallion Architecture example. All credentials, paths, and data sources are mocked or abstracted for security reasons.

# Bikes - Databricks Medallion Pipeline (Bronze → Silver → Gold)
# Overview
Pipeline built in Databricks following the Medallion Architecture:

Bronze: raw ingestion
Silver: cleansing + transformations
Gold: business-ready tables/aggregations
Tech Stack
Databricks (Jobs, Notebooks)
Spark / PySpark
Delta Lake (Bronze/Silver/Gold)
Data quality validation (example step)
How to run (high level)
Configure your own storage and secrets
Run notebooks in order: Bronze → Silver → Gold
Trigger the job pipeline
Security note
This repository uses mock/sample data and does not expose:

workspace URLs
tokens/secrets
storage account names
subscription/tenant identifiers
