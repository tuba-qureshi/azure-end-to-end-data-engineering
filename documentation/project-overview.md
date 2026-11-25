Azure End-to-End Data Engineering Project

Project Overview

This project demonstrates an end-to-end data engineering workflow using Microsoft Azure services. It involves ingesting data from GitHub, storing it in Azure Data Lake Storage, processing it using Azure Databricks, and preparing transformed data for analytics using Azure Synapse Analytics.

Project Workflow

1. Data Source: AdventureWorks CSV datasets hosted on GitHub.
2. Data Ingestion: Azure Data Factory retrieves source files through HTTP-based connections.
3. Data Storage: Azure Data Lake Storage Gen2 is used to store ingested data in different layers.
4. Data Transformation: Azure Databricks and PySpark are used for data processing and transformation.
5. Data Analytics: Azure Synapse Analytics is used to work with the transformed data and analytical views.

Project Components

Component| Purpose
GitHub| Hosts source datasets and project code
Azure Data Factory| Orchestrates data ingestion workflows
Azure Data Lake Storage Gen2| Stores data in the data lake
Azure Databricks| Processes and transforms data using Spark
Azure Synapse Analytics| Supports analytical queries and views

Technology Stack

- Microsoft Azure
- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks
- Apache Spark
- PySpark
- Azure Synapse Analytics
- SQL
- GitHub

Key Data Engineering Concepts

- Data ingestion
- Pipeline orchestration
- Data lake storage
- Data transformation
- Layered data architecture
- Analytical data processing
- SQL-based analytics

Repository Purpose
This repository preserves the project source files, datasets, pipeline configurations, notebooks, SQL scripts, architecture diagrams, and documentation for reference, learning, and portfolio demonstration.

Disclaimer

This project is based on a learning project/tutorial. The repository contains the files and documentation preserved from the implementation. Azure resources and live services are not included.
