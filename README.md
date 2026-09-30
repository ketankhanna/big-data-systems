# Big Data Systems

Coursework from **Big Data Management Systems and Tools** at the University of Toronto, 2021: NoSQL, Hadoop, Spark and choosing the right datastore.

| # | Work | Topic | Status |
|---|---|---|---|
| 1 | [MongoDB](a1_mongodb_crud_and_aggregation.ipynb) | Queries, inserts, deletes, updates and aggregation pipelines with PyMongo | ✅ Ketan |
| 2 | [Hadoop and Datastores](a2_hadoop_and_datastores.ipynb) | When not to use Hadoop, graph vs relational vs columnar vs document stores, HDFS replication and MapReduce | ✅ Ketan |
| 3 | [Spark on Databricks](a3_spark_iot_devices.ipynb) + [written answers](docs/A3_Spark_Written_Answers.pdf) | RDDs vs DataFrames vs Datasets; Spark SQL on 198k IoT sensor readings | ✅ Ketan |
| Final | [Ames House Prices report](docs/Final_Project_Report_Ames_House_Prices.pdf) | Data preparation and analysis of 2,919 home sales with 79 features | 👥 Team (Group 7) |

## 🔧 Claude Note (2026)
Assignment 2, Question 4 says MongoDB "does not support transactions". That was true of early versions, but MongoDB has supported multi-document ACID transactions since version 4.0 (2018), so today it's less of a drawback for a CRM.

## Running Assignment 1
It needs a local MongoDB server and the course's sample `Employee`, `Workplace` and `Address` collections, so the notebook is shown as submitted.

## Tools
Python · MongoDB / PyMongo · Hadoop / MapReduce · Apache Spark · Databricks · Spark SQL
