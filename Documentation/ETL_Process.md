ETL Workflow
Extract

Imported CSV files into SQL Server staging tables.

Transform

Performed

Data cleaning
Duplicate removal
Data validation
Data type conversion
Relationship verification

Load

Loaded cleaned data into

Dimension Tables

DimCustomer
DimProduct
DimDate
DimTerritory

Fact Tables

FactSales
FactReturns

ETL Flow

CSV Files

↓

Staging Tables

↓

Cleaning

↓

Transformation

↓

Dimensions

↓

Facts

↓

Reporting Views

↓

Power BI
