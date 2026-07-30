ETL Architecture

The ETL pipeline loads raw data into the warehouse.

CSV Files
     │
     ▼
Staging Tables
     │
     ▼
Data Cleaning
     │
     ▼
Data Validation
     │
     ▼
Business Transformation
     │
     ▼
Dimension Tables
     │
     ▼
Fact Tables
     │
     ▼
Reporting Views
 
 

ETL Stages

Extract

Import CSV files

Load into staging tables

Transform

Remove duplicates

Validate data

Standardise formats

Build relationships

Load

Populate Dimension tables

Populate Fact tables
