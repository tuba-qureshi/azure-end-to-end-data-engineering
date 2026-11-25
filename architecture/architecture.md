Azure End-to-End Data Engineering Architecture

Project Overview

This project demonstrates an end-to-end data engineering workflow using Microsoft Azure services to ingest, store, process, and analyze data.

Architecture Components

1. Azure Data Factory (ADF)

Used to orchestrate the data pipeline and automate data ingestion from the source into Azure storage.

2. Azure Data Lake Storage (ADLS Gen2)

Used as the storage layer to organize data into Bronze, Silver, and Gold layers.

- Bronze: Stores raw ingested data.
- Silver: Stores cleaned and processed data.
- Gold: Stores data prepared for analytical purposes.

3. Azure Databricks

Used as the data processing platform for working with data using Apache Spark and PySpark.

4. Azure Synapse Analytics

Used to access and query data using SQL and external data objects for analytical purposes.

Data Flow

Source Data → Azure Data Factory → Azure Data Lake Storage → Azure Databricks → Azure Synapse Analytics

Technologies Used

- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks
- Azure Synapse Analytics
- Apache Spark
- PySpark
- SQL
