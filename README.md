#  DBT, Airflow & SnowFlake Data Pipeline
### Emmanuel Torres Malena | 2021-1097

This project implements a data pipeline leveraging dbt for data transformation, Airflow for orchestration, and Snowflake as the cloud data warehouse. The pipeline processes, transforms, and organizes raw data into analytics-ready datasets.

---

#### Key Componentes

- Snowflake: Acts as the cloud data warehouse to store and manage raw, intermediate, and transformed data.
- dbt (Data Build Tool): Handles SQL-based data transformations and testing within Snowflake.
- Apache Airflow: Orchestrates the pipeline, scheduling tasks, and ensuring dependencies are met.
