# Vasilen Kanchev

**Data Engineer | Python, SQL, dbt, PostgreSQL and AWS RDS**

Porto, Portugal · EU citizen · Open to full-time remote Data Engineer roles.

I build tested data pipelines that turn fragmented operational data into reliable datasets. At Gosian Media, I migrated **30+ spreadsheets into PostgreSQL on AWS RDS** and built Python, Docker and dbt workflows that replaced **10+ hours of manual data entry each week**. Previously, I automated Python/Tableau KPI reporting for **15+ stakeholders** and built ETL workflows from social media APIs.

[Portfolio](https://vasilendata.github.io) · [CV (PDF)](https://vasilendata.github.io/vasilen-kanchev-cv.pdf) · [LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) · [Email](mailto:vasilen.business@gmail.com)

## Selected engineering projects

| Project | What to inspect | Operating scope |
|---|---|---|
| [**NYC Taxi Data Platform**](https://github.com/VasilenData/nyc-taxi-data-platform) | Dagster/dbt pipeline over **31.6M public taxi trips**, with quarantine reasons, reconciliation checks and tests for reruns and corrupted input. | Local/Docker implementation and CI. Full-data measurements and sample-test scope are documented in the repository. |
| [**Wikipedia Streaming Lakehouse**](https://github.com/VasilenData/wiki-stream-lakehouse) | Kafka and Spark Structured Streaming with watermark-bounded deduplication, late-event handling, dead letters and checkpoint-reuse tests on real Kafka. | Local execution and CI. AWS Terraform is validated, not deployed. |
| [**HN Pulse**](https://github.com/VasilenData/hn-pulse) · [live dashboard](https://vasilendata.github.io/hn-pulse/) | Python/dbt/DuckDB pipeline with **27 dbt data tests** and enforced model contracts; failed tests block dashboard publication. | GitHub Actions runs the live schedule. A separate Airflow DAG demonstrates local orchestration. |

## How I work

- **Connect the data to a decision.** Define the metrics, table grain and downstream use before choosing the implementation.
- **Make failures visible.** Validate schemas and counts, retain rejected records where appropriate, and test reruns and failure paths.
- **Explain the evidence.** Keep professional delivery, local experiments, CI checks and deployed demos clearly identified.

## Toolkit

**Professional use:** Python, SQL, PostgreSQL, dbt, Docker, AWS RDS, ETL and API integration, data validation, Tableau and Excel.

**Demonstrated in projects:** Dagster, Airflow (local), Kafka, Spark Structured Streaming, DuckDB, dimensional modeling, data contracts, GitHub Actions, BigQuery sandbox measurements and a Databricks Free Edition SQL port. Terraform configuration is validated in CI; it has not been deployed.

## More work

<details>
<summary>All 14 projects, including analytics and ML</summary>

| Project | Focus |
|---|---|
| [NYC Taxi Data Platform](https://github.com/VasilenData/nyc-taxi-data-platform) | Batch ingestion, dbt modeling, quarantine, reconciliation and rerun tests. |
| [Wikipedia Streaming Lakehouse](https://github.com/VasilenData/wiki-stream-lakehouse) | Local Kafka/Spark streaming and explicit delivery/recovery limits. |
| [HN Pulse](https://github.com/VasilenData/hn-pulse) · [live](https://vasilendata.github.io/hn-pulse/) | Scheduled API ingestion, model contracts, tests and a public dashboard. |
| [Data Contracts Platform](https://github.com/VasilenData/data-contracts-platform) | YAML/DuckDB validation and breaking-change detection; documented drift from a January-fitted contract across later monthly files. |
| [E-Commerce Finance Mart](https://github.com/VasilenData/ecommerce-finance-mart) · [explorer](https://vasilendata.github.io/ecommerce-finance-mart/explorer/) · [Tableau](https://public.tableau.com/app/profile/vasilen.kanchev/viz/E-CommerceFinanceMartSalesDashboard/E-CommerceFinanceMartsalesdashboard) | Star schema, financial reconciliation, an Excel workbook and a Databricks SQL port on public retail data. |
| [BigQuery Cost Lab](https://github.com/VasilenData/bigquery-cost-lab) | Public-table dry-run estimates, sandbox scan measurements, SQL linting and a bytes estimator. |
| [Tech Job Market ETL](https://github.com/VasilenData/tech-job-market-etl) | API ingestion, validation and idempotent PostgreSQL loads scheduled through GitHub Actions. |
| [Four-Engine Benchmark](https://github.com/VasilenData/taxi-engines-benchmark) | Cross-checked queries over 79M taxi trips using DuckDB, Polars, pandas and Spark. |
| [A/B Test Analysis](https://github.com/VasilenData/ab-test-analysis) | Experiment analysis, confidence intervals, multiple-testing correction and simulation checks. |
| [E-Commerce Sales & Logistics Dashboard](https://github.com/VasilenData/ecommerce-logistics-dashboard) · [live](https://vasilendata.github.io/ecommerce-logistics-dashboard/) | PostgreSQL views and a dashboard connecting revenue, delivery delays and customer reviews. |
| [Taxi Trip Duration Service](https://github.com/VasilenData/taxi-eta-service) | LightGBM, FastAPI, MLflow, champion/challenger promotion and drift monitoring. |
| [Evaluated AI Research Assistant](https://github.com/VasilenData/research-assistant-eval) | A local language model, retrieval evaluation and a measured claim checker. |
| [Retrieval Evaluation for RAG](https://github.com/VasilenData/rag-retrieval-eval) | BM25, Qdrant vectors, rank fusion and reranking evaluated on labeled questions. |
| [Customer Churn Model](https://github.com/VasilenData/customer-churn-model) | Random Forest classification, feature engineering and held-out evaluation. |

</details>

## Background

My current official role is **Data Engineer and Chief Revenue Officer at Gosian Media** (June 2025–present). My earlier work spans analytics, database administration and operations. That experience helps me understand which metrics matter and where automation improves day-to-day work.

I am studying BSc (Hons) Computer Science at the University of Suffolk, expected 2027, and hold a Higher Certificate in Mathematics and Statistics with Distinction.

For remote Data Engineer opportunities involving Python, SQL, dbt, data quality or pipeline ownership, [contact me on LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) or [email me](mailto:vasilen.business@gmail.com).
