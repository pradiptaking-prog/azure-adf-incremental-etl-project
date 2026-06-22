# Azure Data Factory Incremental ETL Pipeline

## Overview

This project demonstrates an Incremental ETL pipeline built using Azure Data Factory (ADF), Azure Blob Storage, and Azure SQL Database.

## Technologies Used

- Azure Data Factory
- Azure Blob Storage
- Azure SQL Database
- SQL

## Business Problem

Loading complete datasets repeatedly increases processing time and resource consumption. This project implements a watermark-based incremental loading mechanism to load only new records.

## Architecture

CSV File (Blob Storage)
↓
ADF Lookup Activity
↓
ADF Copy Activity
↓
Azure SQL Database

## Key Features

- Incremental Loading
- Watermark Table
- Lookup Activity
- Copy Activity
- Azure SQL Integration

## Learning Outcomes

- ADF Pipeline Development
- Incremental ETL Design
- Azure SQL Integration
- Data Movement and Orchestration
