# Retail Sales Data Engineering Pipeline

### 📌 Project Overview

This project implements an end-to-end cloud data engineering pipeline for processing retail sales data using Amazon S3, Databricks, Delta Lake, and Power BI.

The pipeline follows the Medallion Architecture and is designed to support incremental data processing, data quality, deduplication, and analytical reporting.

The solution ingests customer, product, store, and sales data from Amazon S3, processes the data through Bronze, Silver, and Gold layers in Databricks, and exposes the curated Gold layer to Power BI for business intelligence and reporting.

### Architecture
![Databricks Architecture](architecture_diagram/architecture_diagram.jpg)

