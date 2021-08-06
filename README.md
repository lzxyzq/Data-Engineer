# Data-Engineer

## Data Modelling
This module mainly introduces the concept of data modeling in terms of two major parts — Relational Database (PostgreSQL) and NoSQL Databases (Cassandra).

For the Relational Database part, it covers OLAP/OLTP, Normalization/Denormalization, and Fact/Dimension Tables.

For the NoSQL part, it covers CAP theorem in general, and then all the content is related and only related to Cassandra. 

### Introduction to Data Modeling

➔ Understand the purpose of data modeling

➔ Identify the strengths and weaknesses of different types of databases and data storage techniques

➔ Create a table in Postgres and Apache Cassandra

### Relational Data Models

➔ Understand when to use a relational database

➔ Understand the difference between OLAP and OLTP databases

➔ Create normalized data tables

➔ Implement denormalized schemas (e.g. STAR, Snowflake)

### NoSQL Data Models

➔ Understand when to use NoSQL databases and how they differ from relational databases

➔ Select the appropriate primary key and clustering columns for a given use case

➔ Create a NoSQL database in Apache Cassandra

## Cloud Data Warehouses
This module contains three pillars of content.
- Introduction to Data Warehouses
- Introduction to Cloud Computing and AWS
- Implementing Data Warehouses on AWS

## Data Lakes with Spark
This module dives deeper into the AWS ecosystem (especially EMR) and also introduces Spark (with PySpark). 
This module covers Spark very well in terms of talking about its use cases and syntax and provides practical solutions to handle the data skewness when working with large data volumes.

### The Power of Spark

➔ Understand the big data ecosystem

➔ Understand when to use Spark and when not to use it

### Data Wrangling with Spark

➔ Manipulate data with SparkSQL and Spark Dataframes

➔ Use Spark for ETL purposes

### Debugging and Optimization

➔ Troubleshoot common errors and optimize their code using the Spark WebUI

### Introduction to Data Lakes

➔ Understand the purpose and evolution of data lakes

➔ Implement data lakes on Amazon S3, EMR, Athena, and Amazon Glue

➔ Use Spark to run ELT processes and analytics on data of diverse sources, structures, and vintages

➔ Understand the components and issues of data lakes

## Data Pipelines with Airflow

➔ Create data pipelines with Apache Airflow

➔ Set up task dependencies

➔ Create data connections using hooks

### Data Quality

➔ Track data lineage

➔ Set up data pipeline schedules

➔ Partition data to optimize pipelines

➔ Write tests to ensure data quality

➔ Backfill data

### Production Data Pipelines

➔ Build reusable and maintainable pipelines

➔ Build your own Apache Airflow plugins

➔ Implement subDAGs

➔ Set up task boundaries

➔ Monitor data pipelines


