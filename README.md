# Sales & Marketing Contact Deduplication Pipeline

## 🚀 Overview
This project implements a scalable data engineering pipeline to deduplicate sales and marketing contacts using Spark (PySpark and Scala) on Azure Cloud. It ingests data from sources like Salesforce and SAP, processes it via Azure Data Factory and Azure HDInsight, and stores the clean data in Azure Blob Storage and HBase.

## 🛠️ Technologies
- PySpark & Spark Scala
- Azure Data Factory (ADF)
- Azure HDInsight
- HBase
- Teradata
- Git, Jenkins

## 🧩 Features
- Contact deduplication using business logic
- JSON flattening and validation
- Data lake storage integration
- CI/CD with Jenkins and Git

## 📁 Input/Output
- `contacts_raw.csv`: Raw contact data
- `contacts_deduplicated.csv`: Cleaned and deduplicated contacts

## 📊 Architecture
1. Ingest data → ADF
2. Process via PySpark in HDInsight
3. Apply deduplication rules → Spark transformations
4. Store in Blob Storage / HBase

## 📌 Setup
Run the provided PySpark notebook in Databricks or HDInsight, and use the sample input files to test locally.

