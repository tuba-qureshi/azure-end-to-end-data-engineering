Azure Data Factory – Data Ingestion

Overview

Azure Data Factory (ADF) is used to build and orchestrate a dynamic data ingestion pipeline that transfers data from a source into Azure Data Lake Storage Gen2.

Pipeline Design

The pipeline uses a parameterized and dynamic approach to manage data ingestion.

Activities Used

- Lookup: Retrieves the information required for pipeline execution.
- ForEach: Iterates over multiple configured items.
- Copy Data: Transfers data from the source to the destination.

Storage

Azure Data Lake Storage Gen2 is used as the storage destination, organized into the following containers:

- Bronze: Raw data
- Silver: Processed data
- Gold: Data prepared for analytics

Workflow

1. Retrieve the required information using Lookup.
2. Iterate over the configured items using ForEach.
3. Execute Copy Data to ingest the source data.
4. Store the ingested data in Azure Data Lake Storage Gen2.

Technologies

- Azure Data Factory
- Azure Data Lake Storage Gen2
- Pipeline orchestration
- Dynamic data ingestion
