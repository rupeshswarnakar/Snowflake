## 📄 Assignment Document
[View Full Assignment PDF](./Snowflake_Assignment.pdf)

# Snowflake Assignment

## Overview
This project demonstrates core Snowflake data loading workflows using both internal and external stages. The assignment includes two parts:

1. Creating and loading an `Employee` table in the `bootcamp` database and `snow` schema from `Employee.csv` in Snowflake
2. Creating a `listing` table in Snowflake from Parquet data unloaded from Redshift to Amazon S3

The assignment also shows how to export Snowflake table data back to S3.  

## Objectives
- Create the `bootcamp` database and `snow` schema
- Create an `Employee` table from a CSV source
- Load CSV data into Snowflake using an internal managed stage
- Export Snowflake table data to an S3 output directory
- Unload Redshift `listing` data to S3 in Parquet format
- Create and load a Snowflake `listing` table from Parquet data
- Ensure Parquet data is loaded into individual columns, not JSON-style records  

## Technologies Used
- Snowflake
- SQL
- Amazon S3
- Amazon Redshift
- Internal Stage
- External Stage

## File Format
- CSV
- Parquet
