#  Data Pipeline with dbt, Airflow, and Snowflake
### Emmanuel Torres Malena | 2021-1097

This project implements a modern data pipeline leveraging dbt for SQL-based data transformations, Airflow (via Astronomer CLI) for orchestration, and Snowflake as the cloud data warehouse. The pipeline is designed to transform raw data into analytics-ready datasets efficiently and scalably.

---

#### Key Componentes

- Snowflake: Acts as the cloud data warehouse to store and manage raw, intermediate, and transformed data.
- dbt (Data Build Tool): Handles SQL-based data transformations and testing within Snowflake.
- Apache Airflow: Orchestrates the pipeline, scheduling tasks, and ensuring dependencies are met.

#### Setup Instructions

##### Step 1: Set Up a Python Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

