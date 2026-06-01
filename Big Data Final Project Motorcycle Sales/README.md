Motorcycle Value Classification Pipeline
Overview

This project demonstrates an end-to-end big data pipeline using Apache NiFi, HDFS, Hive, Spark MLlib, and HBase. Motorcycle sales data was ingested, processed, analyzed, and used to train a machine learning model for motorcycle value classification.

Objective

The objective was to build a complete big data workflow that automates data ingestion, storage, processing, machine learning, and result storage using Hadoop ecosystem technologies.

Data

The project used a motorcycle sales dataset containing information such as selling price, year, ownership history, seller type, kilometers driven, and ex-showroom price.

Tools & Technologies
Apache NiFi
HDFS
Apache Hive
Apache Spark MLlib
HBase
Python
Hadoop
YARN
Methodology

The dataset was downloaded from GitHub using NiFi and stored in HDFS. Hive was used to create a structured schema and query the data. Spark MLlib was then used to train a Random Forest classification model that categorized motorcycles into high-value and standard-value classes. Finally, evaluation metrics were stored in HBase for verification and reporting.

Results

The Random Forest model achieved approximately:

Accuracy: 97.18%
Precision: 97.13%
Recall: 97.18%
F1 Score: 97.09%

The project successfully demonstrated end-to-end integration across all required technologies.

Skills Demonstrated
Big Data Architecture
Data Engineering
Machine Learning
Spark MLlib
Hadoop Ecosystem
Database Design
Pipeline Automation
