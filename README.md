# Drive-Sense-Smart-Car-Insurance-Lakehouse-System![ProjectViz](https://github.com/user-attachments/assets/474994ff-540f-4432-a895-ae033036432e)

---

# Drive Sense — Smart Car Insurance Lakehouse System

An end-to-end **smart car insurance** data platform built on the **Databricks Lakehouse architecture**, integrating real-time telematics and policy data for advanced underwriting and claims analytics.

## Tech Stack

* **Databricks Lakehouse Platform (Delta Lake, MLflow, Unity Catalog)**
* **SQL Server** (source system)
* **PySpark**, **Python**
* **Databricks Jobs**, **Lakeflow & Auto Loader**
* **Genie**, **Databricks Apps**

## Project Highlights

* **Real-Time Ingestion**
  Ingested telematics and policy data from SQL Server using **Lakeflow** and **Auto Loader** for scalable and real-time ETL.

* **Medallion Architecture**
  Implemented a **Bronze → Silver → Gold** architecture using **Delta Lake**, ensuring schema enforcement, evolution handling, and quality checks.

* **Machine Learning at Scale**
  Trained and deployed ML models for driver risk scoring using **MLflow**, with model governance and lineage managed via **Unity Catalog**.

* **Data Apps & Dashboards**
  Delivered interactive visualizations and insurance apps using **Genie** and **Databricks Apps** for underwriting and claims analytics.

* **Automation & Reliability**
  Orchestrated end-to-end pipelines using **Databricks Jobs**, ensuring automated, low-latency, and fault-tolerant data transformations.

## Use Cases

* Predictive driver risk scoring
* Policy premium personalization
* Claims fraud detection
* Real-time policyholder behavior insights

## Folder Structure (suggested)

```
drive-sense-lakehouse/
├── notebooks/             # PySpark and data engineering notebooks
├── ml/                    # ML training & inference workflows
├── jobs/                  # Databricks job configurations
├── dashboards/            # Genie/Databricks App resources
├── sql/                   # SQL transformations and DDLs
└── README.md
```

## Getting Started

To run this project:

1. Connect to your Databricks workspace.
2. Configure Auto Loader to read from your SQL Server CDC source.
3. Run the notebooks in the following order:

   * Ingestion → Bronze Layer
   * Silver transformations
   * Gold aggregations & features
4. Train & deploy the ML model using MLflow
5. Launch the dashboards and apps

---

