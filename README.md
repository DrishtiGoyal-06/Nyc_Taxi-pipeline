Project Overview

The NYC Taxi Data Pipeline project:

Ingests raw NYC taxi trip data (from public sources like the NYC Taxi & Limousine Commission)

Applies repeatable transformations to create Silver (clean) and Gold (analytics) data layers

Uses configuration-driven pipelines and linked services for flexible deployment

Supports analytics and reporting on trip patterns, fares, locations, and more

This project can be deployed on Azure Synapse Pipelines or Azure Data Factory. It is designed to be modular, configurable, and production-ready.
Key Features

✔ Modular pipeline architecture — Each stage (Ingest, Silver, Gold) is isolated and reusable
✔ Config-driven setup — Easily swap datasets, linked services, and environments
✔ Data Quality Ready — Designed to integrate validations in transformation stages
✔ Cloud-friendly deployment — Works with Azure Data Factory, Synapse, Databricks, etc.

📊 Data Workflow (Conceptual)

Raw Ingestion
Load raw taxi trip data into a staging area (cloud storage such as Azure Blob / ADLS).

Silver Layer
Clean and standardize trip data — filter invalid records, dedupe, normalize fields.

Gold Layer
Transform clean datasets into analytical models suitable for dashboards and BI.

Analytics & Reporting
Use the Gold layer to derive business insights (daily ridership, revenue summaries, zone analysis, etc.).
