# AzureTransactionalBankingProject

# Azure Transactional Banking Data Pipeline

## Overview
This project implements an end-to-end data pipeline using Azure Data Factory, Azure Data Lake Storage Gen2, and Azure SQL Database.

## Architecture
- Source: CSV files in ADLS Gen2
- Orchestration: Azure Data Factory
- Processing: Copy activity with dynamic pipeline
- Logging: SQL table (pipeline_log)
- Error handling: Stored procedures with success/failure tracking

## Features
- Dynamic file processing using ForEach
- Metadata-driven pipeline
- Success & failure logging
- Error message tracking
- Schema mapping and transformation

## Tech Stack
- Azure Data Factory
- Azure SQL Database
- ADLS Gen2
- T-SQL

## Pipeline Flow
1. Get Metadata
2. Lookup configuration
3. ForEach loop
4. Copy data
5. Log success/failure

## Author
Harsha Vardhan
