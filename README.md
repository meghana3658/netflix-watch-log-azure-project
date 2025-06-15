# 🎬 Netflix Watch Log — Azure Data Engineering Project

This is an **end-to-end Azure Data Engineering project** that processes and analyzes Netflix user activity data using various Azure services and Power BI for visualization. The purpose is to demonstrate a real-world data pipeline from raw data ingestion to insightful dashboards.
---

## 🚀 Project Architecture

```mermaid
graph TD
    A[CSV Files] --> B[Azure Data Factory]
    B --> C[Azure Data Lake Gen 2 (Bronze)]
    C --> D[Azure Databricks]
    D --> E[Data Lake Gen2 (Silver/Gold)]
    E --> F[Power BI Desktop]
# netflix-watch-log-azure-project
