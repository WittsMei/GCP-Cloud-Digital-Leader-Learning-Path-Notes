# GCP-Notes

### Databases, Data warehouses, and Data lakes

🧠 Combined Architectures (Modern Data Stack)
- In many modern organizations, these components are used together:

- **Databases** store real-time operational data.

- ETL tools (e.g., Apache Airflow, dbt, Fivetran) extract data to:

- **Data Warehouses** for dashboards and KPIs, which can store both current and historical data.

- Raw data is stored in **Data Lakes**, which can be queried directly using engines like Presto, Athena, or Databricks.
