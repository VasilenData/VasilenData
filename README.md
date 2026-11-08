# Vasilen Kanchev

**Data Engineer | Python, SQL, dbt, PostgreSQL and AWS RDS**

Porto, Portugal · EU citizen · Open to full-time remote Data Engineer and SQL/dbt Analytics Engineer roles.

I built and maintain Gosian Media's **agency-wide cash-flow reporting system**, live since **October 2026** with **daily refreshes**. I migrated **30+ spreadsheets into PostgreSQL on AWS RDS** and built Python, Docker and dbt workflows, saving an estimated **10+ hours of manual data entry each week**. Previously, I automated Python/Tableau KPI reporting for **15+ stakeholders** and built ETL workflows from social media APIs.

[Portfolio](https://vasilendata.github.io) · [CV (PDF)](https://vasilendata.github.io/vasilen-kanchev-cv.pdf) · [LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) · [Email](mailto:vasilen.business@gmail.com)

## Selected engineering projects

| Project | What to inspect | Operating scope |
|---|---|---|
| [**NYC Taxi Data Platform**](https://github.com/VasilenData/nyc-taxi-data-platform) | Dagster/dbt pipeline with a recorded **31.6M-trip** run, quarantine and reconciliation. Validated mart releases publish atomically; failure tests protect the previous release. | Local/Docker implementation and CI. Full-data measurements and sample-test scope are documented in the repository. |
| [**E-Commerce Finance Mart**](https://github.com/VasilenData/ecommerce-finance-mart) | Star schema over **1.07M public invoice lines**, 14 blocking checks and a release build that compares **124 recalculated Excel values** with SQL. | DuckDB full-source release verified in CI. Historical Databricks port comparison is documented separately. |
| [**HN Pulse**](https://github.com/VasilenData/hn-pulse) · [live dashboard](https://vasilendata.github.io/hn-pulse/) | Python/dbt/DuckDB pipeline with **27 dbt data tests**, enforced model contracts, bounded API retries and a separate hourly check of published-data freshness. | GitHub Actions runs the live schedule. A separate Airflow DAG demonstrates local orchestration. |

## Start with the evidence

- **Professional delivery:** [the spreadsheet-to-RDS case study](https://vasilendata.github.io/gosian/) explains the operational problem, my implementation and the difference between automation results and wider business outcomes.
- **Repeatability and recovery:** [NYC Taxi publication tests](https://github.com/VasilenData/nyc-taxi-data-platform/blob/main/tests/test_publication.py) exercise failed validation, interrupted publication and preservation of the previous release. The [dated full-data measurement](https://github.com/VasilenData/nyc-taxi-data-platform/blob/main/measurements/full-2026-11-08.json) records the benchmark conditions; sample CI runs are a separate check.
- **Scheduled delivery:** the [dated HN Pulse operations review](https://github.com/VasilenData/hn-pulse/blob/main/docs/operations-review-2026-11-08.md) records actual run outcomes, two historical failures and a separately labeled recovery exercise. The [live dashboard](https://vasilendata.github.io/hn-pulse/) exposes data age and quality status; a [separate monitor workflow](https://github.com/VasilenData/hn-pulse/actions/workflows/monitor.yml) retains dated freshness observations.

For **Analytics Engineer** roles, start with the [finance mart and reconciliation checks](https://github.com/VasilenData/ecommerce-finance-mart) and my [Analytics Engineer CV](https://vasilendata.github.io/vasilen-kanchev-cv-analytics.pdf).

## Toolkit

**Professional use:** Python, SQL, PostgreSQL, dbt, Docker, AWS RDS, ETL and API integration, data validation, Tableau and Excel.

**Demonstrated in projects:** Dagster, Airflow (local), Kafka, Spark Structured Streaming, DuckDB, dimensional modeling, data contracts, GitHub Actions, BigQuery sandbox measurements and a Databricks Free Edition SQL port. Terraform configuration is validated in CI; it has not been deployed.

## More work

<details>
<summary>All 14 projects, including analytics and ML</summary>

| Project | Focus |
|---|---|
| [NYC Taxi Data Platform](https://github.com/VasilenData/nyc-taxi-data-platform) | Batch ingestion, quarantine, reconciliation and atomic publication of validated marts. |
| [Wikipedia Streaming Lakehouse](https://github.com/VasilenData/wiki-stream-lakehouse) | Local Kafka/Spark streaming, replay from retained raw events and real Kafka CI tests for forced-crash recovery. |
| [HN Pulse](https://github.com/VasilenData/hn-pulse) · [live](https://vasilendata.github.io/hn-pulse/) | Scheduled API ingestion, publication gates, bounded retries and published-data freshness checks. |
| [Data Contracts Platform](https://github.com/VasilenData/data-contracts-platform) | YAML/DuckDB validation, breaking-change detection and regression tests that prevent duplicate rule names from downgrading blocking failures. |
| [E-Commerce Finance Mart](https://github.com/VasilenData/ecommerce-finance-mart) · [explorer](https://vasilendata.github.io/ecommerce-finance-mart/explorer/) · [Tableau](https://public.tableau.com/app/profile/vasilen.kanchev/viz/E-CommerceFinanceMartSalesDashboard/E-CommerceFinanceMartsalesdashboard) | Star schema and reconciliation on public retail data; release bundles validate recalculated Excel values against SQL and record source/artifact checksums. |
| [BigQuery Cost Lab](https://github.com/VasilenData/bigquery-cost-lab) | Public-table dry-run estimates, sandbox scan measurements, SQL linting and exact integer billing ceilings. |
| [Tech Job Market ETL](https://github.com/VasilenData/tech-job-market-etl) | Idempotent PostgreSQL loads, per-source diagnostics and a completeness gate that withholds reports after source failures. |
| [Four-Engine Benchmark](https://github.com/VasilenData/taxi-engines-benchmark) | Recorded queries over 79M taxi trips; cross-engine answer checks, validated worker measurements and atomic result checkpoints. |
| [A/B Test Analysis](https://github.com/VasilenData/ab-test-analysis) | Experiment analysis, multiple-testing correction, inference-domain validation and seeded statistical invariant checks. |
| [E-Commerce Sales & Logistics Dashboard](https://github.com/VasilenData/ecommerce-logistics-dashboard) · [live](https://vasilendata.github.io/ecommerce-logistics-dashboard/) | PostgreSQL views linking revenue, delivery and reviews; identifier-preserving imports and explicit missing-estimate handling. |
| [Taxi Trip Duration Service](https://github.com/VasilenData/taxi-eta-service) | LightGBM/FastAPI service with chronological evaluation, drift checks and atomic publication of model/metadata bundles. |
| [Evaluated AI Research Assistant](https://github.com/VasilenData/research-assistant-eval) | Local language-model evaluation, claim checking and response caches keyed to model bytes and runtime settings. |
| [Retrieval Evaluation for RAG](https://github.com/VasilenData/rag-retrieval-eval) | Recorded retrieval comparisons plus reusable question-level evidence and paired article-cluster bootstrap comparisons for new runs. |
| [Customer Churn Model](https://github.com/VasilenData/customer-churn-model) | Held-out model evaluation, calibration and training-only threshold optimization checked against an exhaustive oracle. |

</details>

## Background

My current official role is **Data Engineer and Chief Revenue Officer at Gosian Media** (June 2025–present). My earlier work spans analytics, database administration and operations. That experience helps me understand which metrics matter and where automation improves day-to-day work.

I am studying BSc (Hons) Computer Science at the University of Suffolk, expected 2027, and hold a Higher Certificate in Mathematics and Statistics with Distinction.

For remote Data Engineer or SQL/dbt Analytics Engineer opportunities involving data quality, financial reporting or pipeline ownership, [contact me on LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) or [email me](mailto:vasilen.business@gmail.com).
