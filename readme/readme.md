# Project Overview

This Olympic Data Analytics project showcases my applied knowledge from the Azure Data Fundamentals certificate. It provided me with introductory hands-on experience with Azure services, specifically in data engineering and analytics. This project demonstrates the capabilities of various Azure services in an end-to-end data engineering workflow using the 2021 Tokyo Olympics dataset.

# Project Architecture

![Project Architecture](.readme/final%20architecture.png)

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

![Resource Group](.readme/Screenshot%202024-06-17%20192126.png)

### Resources

- **Azure Data Factory**
- **Azure Storage**
    - Enable hierarchical namespace
    - Containers:
        
        ![Storage Containers](./readme/Screenshot%202024-06-17%20192253.png)
        
        - `raw-data`
        - `transformed-data`
- **Azure Databricks**
- **Azure Synapse Analytics**
