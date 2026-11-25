Azure End-to-End Data Engineering Project

Project Overview

This project demonstrates an end-to-end data engineering workflow using Microsoft Azure services. It involves ingesting AdventureWorks datasets from GitHub, storing data in Azure Data Lake Storage Gen2, processing and transforming data using Azure Databricks, and preparing data for analytics using Azure Synapse Analytics.

The project integrates multiple Azure services to demonstrate a data pipeline workflow from source data ingestion to analytical data processing.

Architecture

The project follows a layered data architecture consisting of Bronze, Silver, and Gold layers.

- Bronze Layer: Stores the ingested source data.
- Silver Layer: Used for data processing and transformation.
- Gold Layer: Used to prepare data for analytical consumption.

Architecture Diagram

"Azure End-to-End Data Engineering Architecture" (02-architecture/architecture-diagram.png)

Project Workflow

1. Source Data – AdventureWorks CSV datasets hosted on GitHub.
2. Data Ingestion – Azure Data Factory retrieves source files using HTTP-based connections and dynamically ingests the data.
3. Data Storage – Azure Data Lake Storage Gen2 stores the ingested data within the data lake architecture.
4. Data Transformation – Azure Databricks and PySpark are used for data processing and transformation.
5. Analytics – Azure Synapse Analytics is used for SQL-based analytical processing and views.

Technology Stack

Technology| Purpose
Microsoft Azure| Cloud platform
Azure Data Factory| Data ingestion and pipeline orchestration
Azure Data Lake Storage Gen2| Data lake storage
Azure Databricks| Data processing and transformation
Apache Spark| Distributed data processing
PySpark| Data transformation using Python
Azure Synapse Analytics| SQL analytics and views
SQL| Querying and analytical processing
GitHub| Source datasets and version control

Data Source

The project uses AdventureWorks datasets in CSV format.

The source datasets include:

- Calendar
- Customers
- Product Categories
- Product Subcategories
- Products
- Returns
- Sales (2015, 2016, 2017)
- Territories

The source data is hosted on GitHub and accessed through raw file URLs for ingestion into Azure Data Factory.

Repository Structure

azure-end-to-end-data-engineering/
│
├── 01-dataset/
│   ├── raw-data/
│   └── README.md
│
├── 02-architecture/
│   ├── architecture-diagram.png
│   ├── architecture.md
│   ├── data-flow.md
│   └── README.md
│
├── 03-azure-data-factory/
│   ├── arm-template/
│   ├── datasets/
│   ├── linked-services/
│   ├── pipeline/
│   ├── screenshots/
│   └── README.md
│
├── 04-databricks/
│   ├── notebooks/
│   └── README.md
│
├── 05-azure-synapse/
│   ├── sql-scripts/
│   └── README.md
│
├── 07-visuals/
│
├── 08-documentation/
│   └── project-overview.md
│
├── .gitignore
└── README.md

Key Data Engineering Concepts

- Data ingestion from external sources
- Pipeline orchestration
- Dynamic data ingestion
- Azure Data Lake Storage
- Layered data architecture
- Data processing and transformation
- PySpark
- SQL analytics
- Cloud-based data engineering workflows

Project Documentation

Detailed project files are organized within their respective folders:

- "Dataset" (01-dataset/README.md)
- "Architecture" (02-architecture/README.md)
- "Azure Data Factory" (03-azure-data-factory/README.md)
- "Azure Databricks" (04-databricks/README.md)
- "Azure Synapse Analytics" (05-azure-synapse/README.md)
- "Project Overview" (08-documentation/project-overview.md)

Disclaimer

This project was developed as a learning and portfolio project based on an end-to-end Azure Data Engineering workflow.

This repository preserves project source files, datasets, notebook code, pipeline configurations, SQL scripts, architecture diagrams, and documentation. Azure resources, credentials, live services, and deployed infrastructure are not included.

Recreating and running the project requires configuring the necessary Azure resources and services.

--------------------------------------------------------------------------------------------------------------------------------------------------------------
## Credits
This project is based on a YouTube tutorial by [Ansh Lamba](https://www.youtube.com/@AnshLambaJSR).
Completed for learning and educational purposes.


