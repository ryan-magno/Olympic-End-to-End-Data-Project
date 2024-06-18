# Project Overview

This Olympic Data Analytics project showcases my applied knowledge from the Azure Data Fundamentals certificate. It provided me with introductory hands-on experience with Azure services, specifically in data engineering and analytics. This project demonstrates the capabilities of various Azure services in an end-to-end data engineering workflow using the 2021 Tokyo Olympics dataset.

# Project Architecture

![Project Architecture](https://prod-files-secure.s3.us-west-2.amazonaws.com/581864de-d26b-4d58-8208-4a0f112c12b2/d472672d-9e25-4df6-8436-f37e9cc195f1/final_architecture.png)

The project utilizes an extract, transform, and load (ETL) model for processing the Tokyo Olympic 2021 dataset.

## Dataset - 2021 Tokyo Olympic Data

Source: [GitHub - Tokyo Olympic Azure Data Engineering Project](https://github.com/darshilparmar/tokyo-olympic-azure-data-engineering-project/tree/main/data)

### Entities

- `athletes.csv`
- `coaches.csv`
- `entries_gender.csv`
- `medals.csv`
- `teams.csv`

## Resource Group

![Resource Group](https://prod-files-secure.s3.us-west-2.amazonaws.com/581864de-d26b-4d58-8208-4a0f112c12b2/b201df58-6de5-4429-bf94-536d0f18f3a7/Untitled.png)

### Resources

- **Azure Data Factory**
- **Azure Storage**
    - Enable hierarchical namespace
    - Containers:
        
        ![Storage Containers](https://prod-files-secure.s3.us-west-2.amazonaws.com/581864de-d26b-4d58-8208-4a0f112c12b2/86c5ec3f-efb2-4a54-905c-36f29a3ed8f3/Untitled.png)
        
        - `raw-data`
        - `transformed-data`
- **Azure Databricks**
- **Azure Synapse Analytics**
