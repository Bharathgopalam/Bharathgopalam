# Bharath Kumar Gopalam

**Data Engineer** · Dahlonega, GA · [LinkedIn](https://www.linkedin.com/in/bharathkumargopalam)

Data engineer with 3 years of experience across data engineering and analytics roles, delivering data projects end to end. I owned the build of a healthcare analytics platform from raw source data to a governed reporting layer used by 10+ business stakeholders, and built a workforce analytics pipeline that consolidated 12 disconnected source systems.

Authorized to work in the U.S., no sponsorship required.

## Projects

| Project | What it is | Built with |
|---|---|---|
| [lakehouse-elt](https://github.com/Bharathgopalam/lakehouse-elt) | Medallion (Bronze/Silver/Gold) data pipeline on deliberately messy order events: idempotent ingestion, incremental loads by watermark, quarantine of invalid rows, a quality gate before Gold, and a DAG runner. 22 pytest tests. | Python, DuckDB, SQL, Parquet, pytest |
| [job-tracker-api](https://github.com/Bharathgopalam/job-tracker-api) | REST API for tracking job applications: JWT login, per-user data isolation, an enforced status workflow, and response and interview rate reporting. 20 pytest tests. | Python, FastAPI, SQLAlchemy, SQLite, JWT, pytest |

## Experience

**Data Engineer, TEK Business Solutions LLC** (Aug 2025 – Jun 2026, Remote)
Healthcare analytics platform, owned end to end:
- Automated environment provisioning and releases across dev, test, and prod with Terraform and Azure DevOps CI/CD.
- Built 12 reusable, parameterized Azure Data Factory pipelines loading 1M+ rows a day from 20+ source tables into Snowflake through ADLS Gen2.
- Delivered 30+ governed Silver/Gold models in SQL with SCD Type 1/2 history across 14 dimension tables.
- Added automated checks for nulls, duplicates, row-count mismatches between layers, and schema drift.
- Cut incremental load times by ~30% and saved roughly 10–15% of monthly compute.

**System Engineer, ADP Solutions Software** (May 2022 – Jul 2023, Hyderabad)
Workforce analytics data pipeline built from scratch in SQL and Python, consolidating 12 source systems; components reused across 5+ reporting projects.

**Data Analyst Intern, APEX Healthcare Limited** (Jun 2021 – Mar 2022, Hyderabad)
Maintained Azure Data Factory, Spark, and SQL pipelines carrying patient and claims data.

## Skills

- **Languages:** SQL, Python, PySpark, Shell scripting
- **Platforms:** Snowflake (Snowpark, Tasks), Azure Data Factory, ADLS Gen2, Databricks, AWS (S3, Glue, Lambda), DuckDB, FastAPI
- **Practices:** ETL/ELT, Medallion architecture, dimensional modeling (SCD Type 1/2), data quality, Terraform, CI/CD, Git, pytest

## Education

- M.S., Computer and Information Sciences, Trine University (2025)
- B.S., Computer Science, International Institute of Business Management & Research Technology (2022)
