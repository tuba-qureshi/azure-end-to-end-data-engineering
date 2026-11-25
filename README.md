☁️ Azure End-to-End Data Engineering Project

<p align="center">
  <b>End-to-End Data Pipeline using Microsoft Azure</b>
</p><p align="center">
  <img src="https://img.shields.io/badge/Azure-Cloud%20Data%20Engineering-0078D4?logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/ETL-Data%20Pipeline-orange" />
  <img src="https://img.shields.io/badge/Apache%20Spark-PySpark-E25A1C?logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Project-Learning%20Purpose-green" />
</p>---

🚀 Project Overview

This project demonstrates an end-to-end data engineering workflow using Microsoft Azure services.

The project integrates multiple cloud services to ingest data from GitHub, store data in Azure Data Lake Storage Gen2, process and transform data using Azure Databricks, and prepare data for analytics using Azure Synapse Analytics.

The workflow covers different stages of data engineering, from source data ingestion to data processing and analytical preparation.

---

🏗️ Architecture

The project follows a layered data architecture consisting of Bronze, Silver, and Gold layers.

Layer| Description
🥉 Bronze| Stores ingested source data
🥈 Silver| Handles data processing and transformations
🥇 Gold| Prepares data for analytical consumption

Architecture Diagram

"Azure End-to-End Data Engineering Architecture" (architecture/architecture-diagram.png)

---

🔄 Project Workflow

📂 GitHub
    │
    ▼
⚙️ Azure Data Factory
    │
    ▼
🗄️ Azure Data Lake Storage Gen2
    │
    ├── 🥉 Bronze Layer
    │
    ▼
🔧 Azure Databricks
    │
    ├── 🥈 Silver Layer
    │
    ▼
🥇 Gold Layer
    │
    ▼
📊 Azure Synapse Analytics

Workflow Description

📥 1. Source Data

AdventureWorks CSV datasets are hosted on GitHub and serve as the source for data ingestion.

⚙️ 2. Data Ingestion

Azure Data Factory retrieves source files through HTTP-based connections and dynamically ingests the data.

🗄️ 3. Data Storage

Azure Data Lake Storage Gen2 is used to store data within the data lake architecture.

🔧 4. Data Transformation

Azure Databricks and PySpark are used for data processing and transformation.

📊 5. Analytics

Azure Synapse Analytics is used for SQL-based analytical processing and views.

---

🛠️ Technologies Used

Technology| Purpose
☁️ Microsoft Azure| Cloud platform
⚙️ Azure Data Factory| Data ingestion and pipeline orchestration
🗄️ Azure Data Lake Storage Gen2| Data lake storage
🔧 Azure Databricks| Data processing and transformation
⚡ Apache Spark| Distributed data processing
🐍 PySpark| Data transformation using Python
📊 Azure Synapse Analytics| SQL analytics and views
📝 SQL| Querying and analytical processing
🐙 GitHub| Source data and version control

---

📂 Dataset

The project uses AdventureWorks datasets in CSV format.

Dataset Files

- 📅 "AdventureWorks_Calendar.csv"
- 👥 "AdventureWorks_Customers.csv"
- 🗂️ "AdventureWorks_Product_Categories.csv"
- 📦 "AdventureWorks_Product_Subcategories.csv"
- 🛍️ "AdventureWorks_Products.csv"
- ↩️ "AdventureWorks_Returns.csv"
- 📈 "AdventureWorks_Sales_2015.csv"
- 📈 "AdventureWorks_Sales_2016.csv"
- 📈 "AdventureWorks_Sales_2017.csv"
- 🌍 "AdventureWorks_Territories.csv"

Source data is hosted on GitHub and accessed through raw file URLs for ingestion into Azure Data Factory.

📁 "Explore Dataset" (dataset/)

---

📚 Project Components

⚙️ Azure Data Factory

- Dynamic data ingestion
- HTTP-based source connections
- Pipeline orchestration
- Dataset configuration
- Linked services
- Pipeline execution monitoring

📁 "Explore Azure Data Factory" (azure-data-factory/)

🔧 Azure Databricks

- Apache Spark
- PySpark
- Data processing
- Silver layer notebook

📁 "Explore Databricks" (databricks/)

📊 Azure Synapse Analytics

- SQL scripts
- Schema creation
- Analytical views

📁 "Explore Synapse Analytics" (azure-synapse/)

---

📖 Documentation

Project documentation and reference materials are organized within the repository.

- 🏗️ "Architecture" (architecture/architecture.md)
- 🔄 "Data Flow" (architecture/data-flow.md)
- 📂 "Dataset Documentation" (dataset/README.md)
- ⚙️ "Azure Data Factory Documentation" (azure-data-factory/README.md)
- 🔧 "Databricks Documentation" (databricks/README.md)
- 📊 "Synapse Documentation" (azure-synapse/README.md)
- 📘 "Project Overview" (documentation/project-overview.md)

---

📁 Repository Structure

azure-end-to-end-data-engineering/
│
├── architecture/
│   ├── architecture-diagram.png
│   ├── architecture.md
│   └── data-flow.md
│
├── azure-data-factory/
│   ├── arm-template/
│   ├── datasets/
│   ├── linked-services/
│   ├── pipeline/
│   ├── screenshots/
│   └── README.md
│
├── azure-synapse/
│   └── sql-scripts/
│
├── databricks/
│   ├── notebooks/
│   └── README.md
│
├── dataset/
│   ├── raw-data/
│   └── README.md
│
├── documentation/
│   └── project-overview.md
│
├── visuals/
│
├── .gitignore
└── README.md

---

🎯 Key Data Engineering Concepts

- 🔄 Data ingestion
- ⚙️ Pipeline orchestration
- 📥 Dynamic data ingestion
- 🗄️ Data lake storage
- 🏗️ Layered data architecture
- 🔧 Data processing and transformation
- ⚡ Apache Spark & PySpark
- 📝 SQL analytics
- ☁️ Cloud-based data engineering workflows

---

🎓 Project Purpose

This project was undertaken to gain practical exposure to Azure Data Engineering concepts and understand how multiple cloud services work together in a data pipeline.

It serves as a learning reference for exploring data ingestion, storage, transformation, pipeline orchestration, and analytical processing.

---

🙏 Credits

This project is based on a YouTube tutorial by "Ansh Lamba" (https://www.youtube.com/@AnshLamba).

Completed for learning and educational purposes.

---

<p align="center">
  ⭐ Thank you for visiting this repository!
</p>
