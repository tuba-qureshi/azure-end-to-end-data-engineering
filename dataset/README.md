Dataset

Overview

This folder contains the AdventureWorks datasets used as source data for the Azure End-to-End Data Engineering project. The data is used as input for the ingestion pipeline built using Azure Data Factory.

Data Source

The source datasets are hosted on GitHub and accessed through raw GitHub URLs. Azure Data Factory retrieves the source files using HTTP-based connections and dynamically ingests them into Azure Data Lake Storage.

Dataset Files

The project uses the following datasets:

- AdventureWorks_Calendar.csv
- AdventureWorks_Customers.csv
- AdventureWorks_Product_Categories.csv
- AdventureWorks_Product_Subcategories.csv
- AdventureWorks_Products.csv
- AdventureWorks_Returns.csv
- AdventureWorks_Sales_2015.csv
- AdventureWorks_Sales_2016.csv
- AdventureWorks_Sales_2017.csv
- AdventureWorks_Territories.csv

Folder Structure

01-dataset/
├── raw-data/
│   └── AdventureWorks CSV files
└── README.md

Purpose

- Provide source data for the Azure Data Factory ingestion pipeline.
- Support dynamic ingestion from GitHub.
- Supply data for Azure Data Lake Storage.
- Support downstream data processing and analytical transformations.

Technologies

- GitHub
- CSV
- Azure Data Factory
- Azure Data Lake Storage

Note
The datasets are included for educational and project demonstration purposes.
