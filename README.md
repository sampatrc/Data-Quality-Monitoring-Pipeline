# 🔍 Automated Data Quality Monitoring System using Azure

In today’s data-driven world, ensuring high-quality data is essential for accurate analytics and decision-making. This project introduces a **cloud-native automated system** for monitoring and validating data quality in ETL pipelines using Microsoft Azure services.

![Architecture Diagram](./architecture.png) <!-- Replace with actual file name if different -->

---

## 📌 Abstract

Manual data validation in ETL processes is time-consuming and error-prone. This project proposes an **automated, event-driven data quality monitoring system** that uses Azure Data Factory, Azure Data Lake Storage, Azure Databricks, and Azure Logic Apps to:
- Detect anomalies and schema mismatches
- Remove nulls and duplicates
- Alert data engineers in real-time

---

## 🧩 Problem Statement

Organizations face:
- Inaccurate and inconsistent data
- Manual, unscalable validation processes
- Delayed analytics due to undetected issues
- Undetected schema drifts and anomalies

**Goal:** To build a robust, scalable solution that eliminates manual checks and ensures reliable data flow across the pipeline.

---

## 🎯 Scope

The project covers:
- Automated validation with PySpark in Azure Databricks
- Event-triggered pipelines using Logic Apps
- Real-time alerts and visual dashboards via Power BI
- Scalable storage and orchestration using ADLS and Data Factory

---

## 🏗️ Architecture

### Azure Components:
- **Azure Data Factory**: Data ingestion
- **Azure Data Lake Storage (ADLS)**: Central data store
- **Azure Databricks**: Data cleaning and quality checks
- **Azure Logic Apps**: Event-driven alerts
- **Power BI** *(optional)*: Visual dashboards


