This project implements a data pipeline using Azure Databricks and the Medallion Architecture (Bronze, Silver, Gold layers).
It connects to Azure Blob Storage, mounts the container in Databricks, and processes datasets such as reviews, products, and sales.

The pipeline ensures structured data processing, moving data from the Raw (Bronze) layer to Refined (Silver) and Aggregated (Gold) layers for analytics and reporting.

🚀 Features
Azure Blob Storage Integration – Mounts Azure Blob Storage to Databricks for seamless file access.

Widget-based Parameterization – Allows dynamic file selection (reviews, products, sales) without code changes.

Medallion Architecture Implementation:

Bronze Layer – Raw data ingestion from Blob Storage.

Silver Layer – Cleaned and structured data.

Gold Layer – Aggregated data ready for analytics.

Scalable & Modular – Easily extendable for new data sources and transformations.
