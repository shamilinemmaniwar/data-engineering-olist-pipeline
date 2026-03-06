# Olist Data Engineering Project

This project implements an end-to-end data engineering pipeline using PySpark based on the Olist E-commerce dataset.

## Architecture
The pipeline follows a medallion architecture:

- Raw Layer – Original CSV datasets
- Bronze Layer – Raw ingestion with metadata
- Silver Layer – Cleaned and transformed data
- Gold Layer – Business KPIs and analytics tables

Raw Data → Bronze Layer → Silver Layer → Gold Layer → Business KPIs

## Tools Used
- Python
- PySpark
- Jupyter Notebook
- GitHub

## Dataset
Olist Brazilian E-commerce dataset.

## Pipeline Overview
1. Ingest raw CSV files
2. Perform data profiling
3. Apply transformations in Silver layer
4. Generate KPIs in Gold layer
