# GCP-Notes

### Databases, Data warehouses, and Data lakes

🧠 Combined Architectures (Modern Data Stack)
- In many modern organizations, these components are used together:

- **Databases** store real-time operational data.

- ETL tools (e.g., Apache Airflow, dbt, Fivetran) extract data to:

- **Data Warehouses** for dashboards and KPIs, which can store both current and historical data.

- Raw data is stored in **Data Lakes**, which can be queried directly using engines like Presto, Athena, or Databricks.

Component | Primary Role | Best For
Database | Real-time, operational data | App backends, order systems, auth data
ETL/ELT Tools | Move and transform data | Automating pipelines
Data Warehouse | Analytics-ready data storage | BI dashboards, KPIs, aggregated data
Data Lake | Store all raw data | Machine learning, archive, semi/unstructured
Query Engines | Analyze lake data with SQL | Ad hoc, flexible analysis without data move
