# 📦 Financial Transaction Dataset Pipeline + DAG

> PySpark ingestion and ETL data pipeline into a Databricks environment executed on the Databrick's orchestrator (Apache airflow substitute)

## 📌 About

This project is limited to 1 data pipeline and processes 5 tables at once in a layer-based approach DAG. The end product are gold level tables that show metrics related to fraud.

## ✨ Features

- Window function analysis
- Aggregations by client and time

## 🛠️ Tech Stack

- SQL (PostgreSQL / Spark SQL)
- Databricks
- Python (optional)
- PySpark

## 🚀 Usage
Import all notebooks + YAML into Databricks and run the job.
Afterwards, run SQL queries in your database environment.
