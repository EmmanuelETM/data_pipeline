#  Data Pipeline with dbt, Airflow, and Snowflake
### Emmanuel Torres Malena | 2021-1097

This project implements a modern data pipeline leveraging dbt for SQL-based data transformations, Airflow (via Astronomer CLI) for orchestration, and Snowflake as the cloud data warehouse. The pipeline is designed to transform raw data into analytics-ready datasets efficiently and scalably.

---

#### Key Componentes

1. Snowflake: Acts as the cloud data warehouse to store and manage raw, intermediate, and transformed data.
2. dbt (Data Build Tool): Purpose: Enables SQL-based transformations with a focus on modularity, maintainability, and transparency.
Features:

    - Data transformations are written in SQL and version-controlled.
    - Supports automated documentation and testing.
    - Includes a library of pre-built macros like dbt_utils for enhanced functionality.
- Apache Airflow: Orchestrates the pipeline, scheduling tasks, and ensuring dependencies are met.
- Astro CLI: 

#### Setup Instructions

##### Step 1: Set Up a Python Virtual Environment

1. Create a virutal environment:
   
```bash
python3 -m venv venv
source venv/bin/activate
```
2. Install dbt dependencies:
   
```bash
pip install dbt-core dbt-snowflake
```

##### Step 2: Download Github Repo

```bash
git clone https://github.com/EmmanuelETM/data_pipeline.git
```












