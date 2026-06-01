
# NYC Payroll Data Integration Pipeline

This repository contains the Azure Data Factory project for the NYC Payroll Data Integration Pipeline.

## Contents

* Linked Services
* Datasets
* Data Flows
* Pipeline
* Factory Configuration
* SQL Scripts
* Project Screenshots

## Project Overview

This project uses Azure Data Factory, Azure Data Lake Storage Gen2, and Azure SQL Database to ingest, transform, and load NYC Payroll data.

The pipeline performs the following tasks:

1. Loads Agency, Employee, and Title master data.
2. Loads Payroll 2020 and Payroll 2021 data.
3. Creates a payroll summary dataset.
4. Stores processed data in Azure SQL Database and Azure Data Lake Storage.

## Verification

The repository includes:

* Successful pipeline execution screenshots
* SQL verification screenshots
* ADLS verification screenshots
* Azure Data Factory JSON artifacts

## Author

Alankriti Mehra
