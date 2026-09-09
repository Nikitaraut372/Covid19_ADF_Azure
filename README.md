# Covid19_ADF_Azure | Data Engineering Azure Project

## Introduction
This project implements an end-to-end data engineering pipeline on Azure to ingest, process, and report on COVID-19 data. It combines case, death, hospital admissions, and testing data published by the ECDC (European Centre for Disease Prevention and Control) with population reference data, producing clean, analysis-ready datasets and an interactive Power BI dashboard.

## Architecture


## Technology Used

1. Cloud & Data Engineering
   -  Azure Data Factory
   -  Azure Data Lake Storage Gen2 (ADLS Gen2)
   -  Azure Blob Storage
   -  Azure Databricks
   -  Apache Spark
   -  Azure SQL Database
   -  Power BI

2. Development & Engineering
   - Python / PySpark
   - SQL
   - Git
   - Azure DevOps
   - ADF Data Flows
   - REST/HTTP data ingestion

ADF is used for ingestion, orchestration, scheduling, monitoring, and pipeline dependencies. Azure Databricks provides Spark-based processing for scalable transformation workloads.

**Modern data Pipeline Tool:** https://www.mage.ai/

**Contribute to this project here:** https://github.com/mage-ai/mage-ai

## Dataset Used
ECDC COVID-19 datasets (cases & deaths, hospital & ICU admissions, testing rates, country response measures) — publicly published by the European Centre for Disease Prevention and Control, ingested via HTTP connector
Population by age data — reference dataset (population_by_age.tsv.gz), sourced from Eurostat, loaded from Azure Blob Storage

### More Info About Dataset
1. Original Data Source - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
![Data model image](data_model.jpeg)

## Scripts for project
1. [Extract Python File](mage-files/extract.py)
2. [Load Python File](mage-files/load.py)
3. [Transform Python File](mage-files/transform.py)


## Complete Video Tutorial
Video Link - https://www.youtube.com/watch?v=WpQECq5Hx9g

