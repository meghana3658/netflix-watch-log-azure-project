# 🎬 Netflix Watch Log — Azure Data Engineering Project

This is an **end-to-end Azure Data Engineering project** that processes and analyzes Netflix user activity data using various Azure services and Power BI for visualization. The purpose is to demonstrate a real-world data pipeline from raw data ingestion to insightful dashboards.
---

## 🚀 Project Architecture

```mermaid
flowchart TD
    A[Netflix CSV Files]
    A --> B[Azure Data Factory]
    B --> C[Azure Data Lake Gen2 - Bronze Layer]
    C --> D[Azure Databricks - Silver Transformations]
    D --> E[Azure Data Lake Gen2 - Silver Layer]
    E --> F[Microsoft Fabric - Power BI Dashboard]
```
