#  Data Pipeline with dbt, Airflow, and Snowflake
### Emmanuel Torres Malena | 2021-1097

This project implements a modern data pipeline leveraging dbt for SQL-based data transformations, Airflow (via Astronomer CLI) for orchestration, and Snowflake as the cloud data warehouse. The pipeline is designed to transform raw data into analytics-ready datasets efficiently and scalably.

---

#### Key Componentes

1. Snowflake: Purpose: A cloud-based data warehouse used for storing and querying both raw and transformed datasets.
Features:

    - Highly performant for large-scale data processing.
    - Scalable storage and compute resources.
    - Native support for dbt, simplifying integration and data management.
   
3. DBT (Data Build Tool): Purpose: Enables SQL-based transformations with a focus on modularity, maintainability, and transparency.
Features:

    - Data transformations are written in SQL and version-controlled.
    - Supports automated documentation and testing.
    - Includes a library of pre-built macros like dbt_utils for enhanced functionality.
      
4. Apache Airflow: Purpose: Provides orchestration and scheduling for the pipeline, ensuring tasks are executed in the correct order and retried upon failure.
Features:

    - DAGs (Directed Acyclic Graphs) define workflows.
    - Scalable and extensible architecture for managing complex pipelines.
    - Integrates seamlessly with dbt through providers like cosmos.
      
5.  Astro CLI: 

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

#### Future Enhancements

- CI/CD Integration: Automate testing, deployment, and promotion of -changes across environments.
- Data Quality Extensions: Use tools like Great Expectations or additional dbt tests to enhance data validation.
- Enhanced Monitoring: Implement metrics dashboards for real-time pipeline performance and error tracking.
- Cross-Cloud Capabilities: Leverage Snowflake’s multi-cloud features to expand the pipeline across different providers.











