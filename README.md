# Rohit Raju Dhole

**Data Engineer** · Batch & Streaming Pipelines · GCP · SQL · Python · PySpark

San Jose, CA · Open to relocation · M.S. Applied Data Intelligence, San José State University

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rohitdhole-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohitdhole)
[![Email](https://img.shields.io/badge/Email-rohitdhole18%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:rohitdhole18@gmail.com)

---

## About me

- Data Engineer with two years of professional engineering and data-validation experience, including 20 months building and supporting production data platforms for banking and commercial clients at Wipro.
- I build ETL/ELT and streaming pipelines with SQL, Python, PySpark, Airflow, Apache Beam and Kafka, and I care about data quality: validation, reconciliation, deduplication and schema checks.
- Hands-on with GCP (BigQuery, Cloud Spanner, Dataflow, Dataproc, Pub/Sub), plus Snowflake and dbt from graduate work.
- Open to Data Engineering roles.

---

## Experience

**Wipro Limited** — Project Engineer (Data Engineer) · India · Dec 2022 – Jul 2024

*Lloyds Banking Group — Payments Data Platform*
- Built and tuned Python and Apache Beam ingestion pipelines delivering sub-minute payment-data availability in Cloud Spanner and BigQuery, with ~25% lower end-to-end latency.
- Cut Cloud Spanner query execution time by ~30% for high-volume payment workloads by refining schemas and query patterns with data-modeling teams.
- Helped maintain 99.9%+ pipeline uptime against production SLAs; supported IAM and PCI DSS controls for payment data.

*Nomad Foods — Commercial Data Platform*
- Reduced FTPS and SharePoint batch-ingestion turnaround from hours to minutes by partitioning source data and parallelizing PySpark on Dataproc.
- Cut manual reconciliation effort by ~50% with Python and SQL validation, deduplication, schema checks and automated alerts.
- Enabled near-real-time reporting across sales, product mapping and payments with Airflow-orchestrated ETL/ELT and Pub/Sub ingestion into partitioned BigQuery tables and PostgreSQL.

---

## Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**Real-Time Market Sentiment**](https://github.com/imrohitdhole/real-time-market-sentiment) | Streaming pipeline that consumes news from Kafka, runs FinBERT sentiment and BERT entity extraction in PySpark Structured Streaming, and publishes results back to Kafka. Adds daily aggregation, Pearson correlation with stock prices and z-score anomaly detection. | Kafka, PySpark, Hugging Face Transformers, yfinance, Plotly, Streamlit, Docker |
| [**Cinema Analytics Platform**](https://github.com/imrohitdhole/cinema-analytics-platform) | Graduate team project: Snowflake analytics pipeline for 18K+ IMDb and TMDb movie records. Three Airflow DAGs with REST API extraction and MERGE-based incremental loads; dbt models, tests and snapshots for genre, release-year and popularity analysis. | Python, Airflow, Snowflake, dbt, SQL, Docker |
| [**CleanSQL**](https://github.com/imrohitdhole/nl-to-sql-cleanSQL) | Graduate research project on data-quality-aware text-to-SQL. Evaluates five prompting strategies and four RAG settings on Spider, then fine-tunes Qwen2.5-Coder-7B with QLoRA. Streamlit app profiles an uploaded CSV and returns basic and robust SQL. | Python, Qdrant, BGE-M3, QLoRA/PEFT, vLLM, Streamlit |
| [**Event-Driven Ride Booking**](https://github.com/imrohitdhole/event-driven-ride-booking) | Ride-hailing app with rider, driver and admin flows. Ride requests are published to Kafka, Redis handles caching and Socket.IO pushes live updates. Includes a scikit-learn fare-prediction service. | Node.js, Express, MongoDB, Kafka, Redis, Socket.IO, React, Flask, scikit-learn |
| [**UBE (Uber Eats-style app)**](https://github.com/imrohitdhole/ubereats) | Full-stack food-delivery app with a React/Redux client, Express API, MongoDB persistence and Kafka for order messaging. | React, Redux Toolkit, Node.js, Express, MongoDB, Kafka, Docker Compose |
| [**Airbnb Market Analysis (Santa Clara County)**](https://github.com/imrohitdhole/airbnb-market-analysis-santa-clara) | Group project: data cleaning, EDA and geospatial analysis of Airbnb listings to find pricing drivers and high-demand neighborhoods. | Python, pandas, geospatial and visualization libraries |

---

## Tech stack

| Area | Tools |
|---|---|
| Programming | SQL, Python, pandas, NumPy, Bash |
| Spark & processing | Apache Spark, PySpark, Spark SQL, batch and streaming pipelines, incremental processing, partitioning, query optimization |
| ETL & data quality | Apache Airflow, dbt, Apache Beam, Apache Kafka, REST APIs, validation, reconciliation, deduplication, schema checks |
| Cloud & databases | GCP (BigQuery, Cloud Spanner, Dataflow, Dataproc, Pub/Sub), AWS (Amazon Redshift), PostgreSQL, Snowflake |
| Engineering & reliability | Git, Docker, Kubernetes, Terraform, Liquibase, CI/CD, Cloud Monitoring, Cloud Logging |

---

## Education

- **M.S. Applied Data Intelligence**, San José State University · Aug 2024 – May 2026
- **B.Tech Computer Science and Engineering**, Dr. Babasaheb Ambedkar Technological University · Aug 2018 – May 2022

---

📫 Best way to reach me: [LinkedIn](https://www.linkedin.com/in/rohitdhole) or [rohitdhole18@gmail.com](mailto:rohitdhole18@gmail.com)
