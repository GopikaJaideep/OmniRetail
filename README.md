# OmniRetailX – Enterprise-Scale Data Platform Engineering

This capstone project simulates a real-world **enterprise data engineering engagement**. The goal is to design, implement, and justify an **end-to-end modern data platform** integrating relational modelling, ETL pipelines, distributed analytics, real-time streaming, and cloud-native architecture.

The project demonstrates practical implementation of **SQL analytics, Python ETL engineering, Apache Spark distributed processing, streaming architectures, and serverless cloud data platforms**.

# Project Architecture Overview

The OmniRetailX platform follows a **modern Lakehouse architecture** consisting of the following layers:

1. **Data Ingestion Layer**
   Raw retail data is ingested from CSV, JSON, and event streams.

2. **ETL Processing Layer**
   Python-based pipelines clean, validate, and transform the raw data.

3. **Distributed Analytics Layer**
   Apache Spark performs scalable data transformations and analytics.

4. **Streaming Layer**
   Retail events are processed in near real-time for fraud detection and monitoring.

5. **Storage Layer**
   Data is stored in a Lakehouse architecture using **Delta / Parquet formats**.

6. **Analytics Layer**
   Business intelligence queries and analytics dashboards operate on curated datasets.

# Project Phases

**Phase 1 – Relational Data Modelling & SQL**
Designed a normalized **3NF relational schema** for retail operations including customers, orders, products, payments, and subscriptions. Implemented advanced SQL analytics using CTEs and window functions.

**Phase 2 – Python ETL Pipeline**
Built a modular ETL pipeline following **Bronze–Silver–Gold architecture**. Implemented schema validation, duplicate removal, feature engineering, and API integration.

**Phase 3 – Distributed Processing (Apache Spark)**
Processed large datasets using **Spark DataFrames and RDD transformations**. Data was stored in **Parquet format** to improve performance and scalability.

**Phase 4 – Real-Time Streaming Simulation**
Implemented a streaming pipeline using **Spark Structured Streaming** to process retail events and detect high-value transactions.

**Phase 5 – Cloud & Serverless Architecture**
Designed a **cloud-native Lakehouse architecture** integrating event ingestion, distributed processing, object storage, and analytics layers.

**Phase 6 – Production Engineering**
Discussed **DevOps practices** including idempotent pipelines, CI/CD integration, monitoring strategies, and infrastructure as code.

# Repository Structure

```
OmniRetailX
│
├── SQL Analytics
│
├── ETL Pipeline
│
├── Spark Processing
│
├── Real-Time
│
├── Cloud
│
├── Production Engineering & DevOps Consideration
│
└── diagrams
    │
    ├── ERD
    │
    ├── Cloud 
```

# Technology Stack

| Component              | Technology                    |
| - | -- |
| SQL Analytics          | Databricks SQL                |
| ETL Pipelines          | Python                        |
| Distributed Processing | Apache Spark                  |
| Streaming              | Spark Structured Streaming    |
| Storage                | Delta Lake / Parquet          |
| Cloud Platform         | Serverless Cloud Architecture |
| Data Modelling         | Relational (3NF)              |

# Key Learning Outcomes

This project demonstrates practical understanding of:

* Enterprise data modelling
* Production-grade ETL pipelines
* Distributed analytics with Spark
* Real-time streaming architectures
* Lakehouse storage design
* Cloud-native serverless data platforms
* Data engineering DevOps practices
