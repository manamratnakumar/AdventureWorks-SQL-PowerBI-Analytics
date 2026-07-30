Solution Architecture

This project follows a complete Business Intelligence architecture that transforms raw CSV files into an interactive Power BI dashboard.

                AdventureWorks CSV Files
                         │
                         ▼
                  SQL Server Staging
                         │
                         ▼
                Data Cleaning & Validation
                         │
                         ▼
                 ETL Transformation Layer
                         │
                         ▼
                  SQL Data Warehouse
               (Dimensions & Facts)
                         │
                         ▼
                 Reporting SQL Views
                         │
                         ▼
                  Power BI Desktop
                         │
                         ▼
             Interactive Business Dashboard
             

          

Components
             
AdventureWorks CSV Files

SQL Server

ETL Pipeline

Data Warehouse

Reporting Views

Power BI Dashboard
