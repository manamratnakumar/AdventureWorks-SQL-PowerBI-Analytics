# AdventureWorks-SQL-PowerBI-Analytics

AdventureWorks Sales Analytics | End-to-End Data Warehouse & Power BI Dashboard 

An enterprise-level end-to-end Business Intelligence project built using SQL Server and Power BI to transform raw sales data into meaningful business insights through ETL, Data Warehousing, Data Modeling, DAX, and Interactive Dashboarding.

Project Overview:

Organizations generate massive amounts of sales data every day. However, raw transactional data alone does not provide meaningful insights for business decision-making.

This project demonstrates how to design and build a complete Business Intelligence solution by transforming raw AdventureWorks sales data into a structured SQL Server Data Warehouse and developing an interactive Power BI dashboard that enables business users to monitor sales performance, identify trends, evaluate product performance, analyse customer behaviour, and track product returns.

The project follows industry-standard Business Intelligence practices including:

Data Warehousing:

ETL Process

Data Cleaning

Data Validation

Star Schema Design

SQL Analytics

DAX Calculations

Interactive Power BI Dashboard

Business Goal:

Develop a scalable Business Intelligence solution that enables business stakeholders to:

Monitor overall sales performance

Track sales trends over time

Identify top-performing products and categories

Analyse customer purchasing behaviour

Evaluate geographical sales distribution

Monitor product return performance

Support strategic business decision-making using interactive dashboards

Business Questions:

The dashboard answers the following business questions:

Sales Performance

How is sales performance changing over time?

Which product categories contribute the most to sales?

Which products generate the highest sales volume?

What are the monthly and yearly sales trends?

Customer Analysis

How many customers purchased products?

Which customer groups contribute the most?

Which countries generate the highest sales?

How does customer distribution vary geographically?

Product Analysis

Which products perform best?

Which product categories dominate sales?

Which subcategories require attention?

Return Analysis

Which products have the highest return rate?

Which categories generate the most returns?

How can product returns be reduced?

Dataset Used:

AdventureWorks Sales Dataset (CSV)

Files included:

Calendar Lookup

Customer Lookup

Product Lookup

Product Categories Lookup

Product Subcategories Lookup

Territory Lookup

Returns Data

Sales Data 2020

Sales Data 2021

Sales Data 2022

Project Architecture

                  AdventureWorks CSV Files
                           │
                           ▼
                 SQL Server Staging Tables
                           │
                           ▼
                  Data Cleaning & Validation
                           │
                           ▼
                    ETL Transformation
                           │
                           ▼
                  Dimension Tables (DIM)
                           │
                           ▼
                     Fact Tables (FACT)
                           │
                           ▼
                     Reporting SQL Views
                           │
                           ▼
                      Power BI Desktop
                           │
                           ▼
              Interactive Executive Dashboard





              
ETL Pipeline

The project follows a SQL-based ETL process.

Extract

Imported CSV files into SQL Server

Loaded raw data into staging tables

Transform

Removed duplicate records

Cleaned missing values

Standardised data types

Created lookup relationships

Validated business rules

Optimised table structure

Load

Loaded transformed data into:

Dimension Tables

Fact Tables

using a Star Schema.

Data Warehouse Design

Fact Tables

Fact Sales

Fact Returns

Dimension Tables

Dim Customer

Dim Product

Dim Category

Dim Subcategory

Dim Territory

Dim Calendar

Schema

                 Dim Customer

                       │

Dim Calendar ---- Fact Sales ---- Dim Product
                       │
                  Fact Returns
                       │
                 Dim Territory



Technologies Used
                
Technology                              Purpose
SQL Server 2022                         Data Warehouse
T-SQL	                                  ETL & Analytics
Power BI Desktop	                      Dashboard Development
DAX	                                    Business Calculations
Power Query                            	Data Transformation
GitHub	                                Version Control

SQL Implementation:

The SQL layer includes:

Database Design

Staging Tables

ETL Scripts

Data Cleaning

Data Validation

Star Schema

Reporting Views

Analytical SQL Queries

Power BI Dashboard

The interactive dashboard includes:

KPI Cards

Total Orders

Total Customers

Total Products

Total Quantity Sold

Total Returns

Return Rate %

Total Categories

Total Countries

Interactive Visuals

Sales Trend Analysis

Category Performance

Product Performance Matrix

Geographic Sales Map

Customer Distribution

Return Analysis

Transaction Details

Dashboard Features

Interactive Filters

Drill Down

Drill Through

Report Page Tooltips

Dynamic DAX Measures

Conditional Formatting

Navigation Buttons

Bookmarks

Sync Slicers

Dynamic Titles

DAX Measures

Examples include:

Total Orders

Total Customers

Total Products

Total Quantity Sold

Total Returns

Return Rate %

Sales Trend Measures

Ranking Measures

Dashboard Preview

Dashboard Images

│── Executive Dashboard.png

│── Product Details.png

│── Drill Through.png

Repository Structure

AdventureWorks-Sales-Analytics/

│

├── Dataset/

│     ├── Sales_2020.csv

│     ├── Sales_2021.csv

│     ├── Sales_2022.csv

│     ├── Customer.csv

│     ├── Product.csv

│

├── SQL/

│     ├── 01_Database_Creation.sql

│     ├── 02_Staging_Tables.sql

│     ├── 03_ETL.sql

│     ├── 04_Dimensions.sql

│     ├── 05_Facts.sql

│     ├── 06_Data_Validation.sql

│     ├── 07_Reporting_Views.sql

│

├── Power BI/

│     ├── AdventureWorks Dashboard.pbix

│

├── Dashboard Images/

│

├── README.md

Key Business Insights:

The dashboard enables decision-makers to:

Identify sales trends across multiple years

Monitor high-performing products and categories

Evaluate customer purchasing patterns

Analyse geographical sales distribution

Track product return performance

Improve strategic planning through interactive analytics

Future Enhancements

Row-Level Security (RLS)

Power BI Service Deployment

Scheduled Data Refresh

Incremental Refresh

Mobile Dashboard Layout

Forecasting

AI Visuals

Real-time Data Integration

Skills Demonstrated

SQL:

Database Design

ETL Development

Data Cleaning

Data Validation

Joins

CTEs

Window Functions

Views

Stored Procedures

Performance Optimisation

Power BI:

Data Modelling

Star Schema

Power Query

DAX

Interactive Dashboards

Drill Through

Tooltips

Bookmarks

Dynamic Titles

Conditional Formatting

Business Intelligence:

KPI Development

Data Visualisation

Business Analysis

Dashboard Design

Decision Support

Executive Reporting

Project Highlights:

 End-to-End Business Intelligence Solution.

 Enterprise SQL Data Warehouse.

 ETL Pipeline Development.

 Star Schema Data Model.

 Advanced SQL Analytics.

 Interactive Power BI Dashboard.

 Advanced DAX Calculations.

 Business-Oriented KPI Reporting.

 Executive-Level Dashboard Design.

 Real-World BI Project.
