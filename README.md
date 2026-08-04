Enterprise Sales Intelligence Platform

Transforming Raw Transactional Data into Executive Business Intelligence

End-to-End Business Intelligence Solution using SQL Server, Power BI & Advanced DAX



 Enterprise Dashboard

 Product Performance Analytics

 Return Intelligence

 Time Intelligence

 Executive KPI Monitoring

 Star Schema Data Modeling

 SQL Server + Power BI + Advanced DAX

 <h2 align="center">Executive Sales Dashboard</h2>

<p align="center">
  <img src="./ScreenShots/Executive%20Sales%20Dashboard%202.png" width="1200">
</p>

EXECUTIVE SUMMARY

Modern organizations generate thousands of sales transactions every day across multiple products, territories, and customer segments. While this data contains valuable business

insights, raw transactional records alone cannot support strategic decision-making.


Business leaders require a centralized reporting solution capable of monitoring operational performance, identifying growth opportunities, evaluating product success, and understanding

customer return behavior in real time.

To address these challenges, this project delivers an Enterprise Sales Intelligence Platform built using SQL Server, Power BI, and Advanced DAX. The solution transforms AdventureWorks

transactional data into a scalable Business Intelligence system that enables executives to monitor Key Performance Indicators (KPIs), analyze sales trends, evaluate product performance,

and make data-driven decisions.

The project follows enterprise Business Intelligence best practices including SQL-based data preparation, Star Schema dimensional modeling, advanced DAX calculations, Time Intelligence,

interactive dashboard development, and business storytelling.

The final solution provides three integrated analytical dashboards:

Executive Dashboard

Product Performance Dashboard

Return Intelligence Dashboard

Together, these dashboards provide a comprehensive view of organizational performance and support faster, more informed business decisions.

<h2 align="center">Executive Sales Dashboard</h2>

<p align="center">
  <img src="./ScreenShots/Executive%20Sales%20Dashboard%202.png" width="1200">
</p>

<h2>Executive Business Insights Dashboard</h2>

<p align="center">
  <img src="./ScreenShots/Executive%20Business%20Insights%20Dashboard.png" width="1000">
</p>

<h2>Product Details Dashboard</h2>

<p align="center">
  <img src="./ScreenShots/Product%20Details%20Dashboard.png" width="1000">
</p>

BUSINESS PROBLEM

AdventureWorks operates across multiple product categories and geographic regions, generating a significant volume of transactional data. Although large amounts of operational data are

available, business users often face challenges in transforming this information into actionable insights.

Traditional reporting methods using spreadsheets and static reports make it difficult to monitor business performance efficiently.

Several critical business questions remain unanswered:

Which products contribute the highest sales?

Which product categories are underperforming?

Which regions require management attention?

How are sales changing over time?

What is the Year-to-Date business performance?

Which products generate the highest return rates?

Which business segments drive organizational growth?

Without a centralized Business Intelligence platform, executives spend considerable time consolidating reports instead of making strategic decisions.

This project addresses these challenges by delivering an interactive analytical reporting platform capable of providing executive-level business insights in real time.

BUSINESS OBJECTIVES

The primary objective of this project is to design and develop a scalable Business Intelligence solution capable of transforming transactional sales data into meaningful business

insights.

Specific objectives include:

Executive Reporting

Develop a centralized Executive Dashboard that provides a real-time overview of organizational performance.

Sales Performance Analysis

Monitor sales trends across multiple years, quarters, and months using advanced Time Intelligence calculations.

Product Intelligence

Identify best-selling products, underperforming products, and category-level sales contributions.

Return Intelligence

Analyze return behavior across products and regions to identify potential quality issues and operational improvements.

Business Growth Analysis

Measure Year-over-Year (YoY), Month-over-Month (MoM), and Quarter-over-Quarter (QoQ) business growth.

Decision Support

Provide interactive analytical reports that enable management to make faster and more informed business decisions.

SOLUTION ARCHITECTURE

                              AdventureWorks Dataset

                                        │

                                        ▼

══════════════════════════════════════════════════════════

                    SQL SERVER DATABASE

══════════════════════════════════════════════════════════

• Data Import

• Data Cleaning

• Duplicate Validation

• NULL Handling

• Data Type Conversion

• Data Quality Validation

• Business Queries

• Window Functions

• Common Table Expressions (CTEs)

• Data Aggregation

══════════════════════════════════════════════════════════

                                        │

                                        ▼

══════════════════════════════════════════════════════════

                 ENTERPRISE STAR SCHEMA

══════════════════════════════════════════════════════════

Fact Tables

• Sales

• Returns

Dimension Tables

• DimDate

• Product

• Product Category

• Territory

══════════════════════════════════════════════════════════

                                        │

                                        ▼

══════════════════════════════════════════════════════════

                    POWER BI DEVELOPMENT

══════════════════════════════════════════════════════════

• Power Query

• Relationship Modeling

• Advanced DAX

• Time Intelligence

• KPI Development

• Interactive Visualizations

• Dashboard Navigation

• Business Storytelling

══════════════════════════════════════════════════════════

                                        │

                                        ▼

              EXECUTIVE DECISION SUPPORT DASHBOARD








Architecture Explanation

The solution follows a modern Business Intelligence architecture consisting of SQL Server for data preparation, dimensional modeling using a Star Schema, advanced analytical

calculations through DAX, and interactive visualization using Power BI.

This layered architecture separates data storage, transformation, analytical calculations, and presentation, ensuring scalability, maintainability, and optimized report performance.

The solution follows a modern Business Intelligence architecture consisting of SQL Server for data preparation, dimensional modeling using a Star Schema, advanced analytical

calculations through DAX, and interactive visualization using Power BI.

This layered architecture separates data storage, transformation, analytical calculations, and presentation, ensuring scalability, maintainability, and optimized report performance.

PROJECT DEVELOPMENT LIFECYCLE

Developing a Business Intelligence solution requires much more than creating charts and dashboards. This project follows a structured, end-to-end BI development lifecycle, starting from raw data acquisition and ending with executive-level reporting.

Each phase was designed to ensure data quality, analytical accuracy, scalability, and business relevance.

Phase 1 — Business Understanding

The first step involved understanding the business requirements and identifying the key questions that management wanted to answer.

The project was designed to provide visibility into:

Overall sales performance

Product contribution

Return analysis

Regional performance

Business growth trends

Phase 2 — Data Exploration

The AdventureWorks dataset was explored to understand:

Available tables

Relationships

Data volume

Missing values

Duplicate records

Business entities

This helped identify the fact tables and dimension tables required for building the analytical model.

Phase 3 — SQL Development

SQL Server was used to prepare the data before importing it into Power BI.

Activities performed:

Imported raw datasets

Created database objects

Validated data quality

Removed inconsistencies

Optimized business queries

Verified relationships

Phase 4 — Data Modeling

A Star Schema was designed to improve report performance and simplify DAX calculations.

The data model included:

Fact Sales

Fact Returns

DimDate

Product

Product Category

Territory

Phase 5 — Power BI Development

Power BI Desktop was used to create the semantic model.

Development activities included:

Data loading

Power Query transformations

Relationship creation

Measure development

Interactive report design

Phase 6 — DAX Engineering

Business measures were developed using DAX.

These measures included:

Sales KPIs

Return KPIs

Time Intelligence

Growth Analysis

Variance Analysis

Rolling Calculations

Phase 7 — Dashboard Development

Three analytical dashboards were created:

Executive Dashboard

Product Performance Dashboard

Return Intelligence Dashboard

Phase 8 — Business Validation

The final solution was validated by:

Comparing SQL results with Power BI

Verifying KPI calculations

Testing slicers and cross-filtering

Validating Time Intelligence measures

Reviewing dashboard usability

SQL ENGINEERING

SQL Server served as the foundation of the analytical pipeline. Before any visualization or reporting was created, the raw AdventureWorks data was prepared, validated, and optimized

within SQL Server.

This ensured that the Power BI model consumed clean, reliable, and business-ready data.

SQL Development Workflow

AdventureWorks Dataset
        │
        ▼
Database Creation
        │
        ▼
Data Import
        │
        ▼
Data Cleaning
        │
        ▼
Data Validation
        │
        ▼
Business Query Development
        │
        ▼
Analytical Dataset
        │
        ▼
Power BI

Database Design

The AdventureWorks dataset was imported into SQL Server and organized into structured tables representing different business entities.

The database included:

Sales Transactions

Product Information

Product Categories

Territories

Calendar

Returns

Data Import

Raw CSV files were imported into SQL Server and verified to ensure:

Correct column mapping

Appropriate data types

Successful record loading

Consistent table structures

Data Cleaning

Several data quality checks were performed before analysis.

Activities

Removed duplicate records

Verified NULL values

Standardized date formats

Validated numeric columns

Checked primary and foreign key consistency

Corrected inconsistent values

Data Validation

Data validation ensured that the analytical model was built on trustworthy data.

Validation included:

Record count verification

Duplicate detection

Missing value checks

Referential integrity validation

Product count verification

Date range validation

SQL Business Queries

Business queries were written to answer analytical questions such as:

Top-selling products

Regional performance

Product category contribution

Monthly sales trend

Return statistics

Sales aggregation

Product rankings

Advanced SQL Concepts Used

The project demonstrates practical usage of advanced SQL concepts including:

Window Functions

Used for:

Ranking products

Running totals

Performance comparisons

Common Table Expressions (CTEs)

Used for:

Query readability

Multi-step calculations

Complex business logic

Aggregate Functions

Used for:

Total Sales

Total Orders

Average Quantity

Return Counts

Joins

Implemented:

INNER JOIN

LEFT JOIN

to combine transactional and dimensional data.

SQL Performance Considerations

To improve query efficiency:

Optimized joins

Minimized unnecessary calculations

Applied filtering at the database level

Structured reusable analytical queries

SQL Deliverables

Database Design

Data Cleaning

Data Validation

Business Queries

Aggregation

Window Functions

CTEs

Optimized Dataset

# 💻 SQL Business Analysis

This project leverages Microsoft SQL Server to perform advanced business analytics on the AdventureWorks dataset. SQL was used extensively for data preparation, business reporting, trend analysis, and performance optimization before importing the data into Power BI.

---

## 🌍 Country Performance Analysis

This query analyzes sales performance across different countries, helping identify top-performing markets and supporting regional business decisions.

<p align="center">
  <img src="./ScreenShots/Country%20Perfomance%20SQL.png" alt="Country Performance SQL" width="1400">
</p>

---

## 🏆 Product Ranking Analysis

This query ranks products based on sales performance using SQL Window Functions, enabling identification of best-selling and underperforming products.

<p align="center">
  <img src="./ScreenShots/Rank%20Products%20SQL.png" alt="Rank Products SQL" width="1400">
</p>

---

## 📅 Rolling 12 Months Analysis

This query calculates a Rolling 12-Month Total to analyze long-term sales trends while minimizing short-term fluctuations.

<p align="center">
  <img src="./ScreenShots/Rolling%2012%20Months%20SQL.png" alt="Rolling 12 Months SQL" width="1400">
</p>

---

## 📈 Running Total Analysis

This query computes cumulative sales over time using SQL Window Functions, allowing continuous monitoring of business growth.

<p align="center">
  <img src="./ScreenShots/Running%20Total%20SQL.png" alt="Running Total SQL" width="1400">
</p>

---

## 📊 Year-over-Year (YoY) Growth Analysis

This query compares yearly sales performance to measure business growth and identify long-term trends.

<p align="center">
  <img src="./ScreenShots/Year%20Over%20Year%20Growth%20SQL.png" alt="Year Over Year Growth SQL" width="1400">
</p>

 DATA MODELING (Star Schema)

 Data modeling is the foundation of every successful Business Intelligence solution. Instead of directly connecting all tables, a Star Schema was designed to improve performance, simplify DAX calculations,
 
 and ensure scalable reporting.

The model separates transactional data from descriptive attributes, making analytical queries more efficient and easier to maintain.

Why Star Schema?

The Star Schema was selected because it:

Improves report performance

Simplifies relationships

Supports advanced DAX calculations

Reduces model complexity

Enables efficient filtering

Follows Microsoft Power BI best practices

Fact Tables

Fact Sales

Contains transactional sales information including:

Order Number

Order Date

Product Key

Territory Key

Order Quantity

Fact Returns

Contains return-related transactions for analyzing product return behavior.

Dimension Tables
DimDate

Used for:

Year

Quarter

Month

Time Intelligence (YTD, MTD, QTD)

Product

Stores product-level descriptive information.

Product Category

Groups products into business categories.

Territory

Provides geographical analysis by region or country.

Relationship Design

Relationships were configured using one-to-many cardinality, with dimension tables filtering the fact tables. This structure enables accurate aggregations, efficient slicers, and reliable DAX calculations.


  <h2 align="center">⭐ Data Model (Star Schema)</h2>

<p align="center">
  <img src="./ScreenShots/Data%20Modelling.png" alt="Data Model" width="1600">
</p>

<p align="center">
<i>Figure: Enterprise Star Schema Data Model designed in Power BI, illustrating relationships between fact and dimension tables.</i>
</p>

<p align="center">
    <img src="./ScreenShots/Relationships.png" alt="Power BI Relationships" width="1600">
</p>




