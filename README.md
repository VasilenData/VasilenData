# Vasilen Kanchev

**Data Engineer | Python, SQL, dbt, PostgreSQL and AWS RDS**

Porto, Portugal · EU citizen · Open to full-time remote Data Engineer and SQL/dbt Analytics Engineer roles with teams that can hire in Portugal.

I build pipelines and reporting systems for business decisions. At Gosian Media, I was promoted from **Data Engineer to Chief Revenue Officer in June 2026**, while continuing hands-on data engineering. I am now targeting a dedicated engineering role focused on pipeline ownership, data quality and business reporting.

I built and maintain Gosian's **agency-wide cash-flow reporting system**, live since **October 2026** with **daily refreshes**. I consolidated **30+ spreadsheets into PostgreSQL on AWS RDS** using Python, Docker and dbt, saving an estimated **10+ hours of manual data entry each week**. Previously, I automated Python/Tableau KPI reporting for **15+ stakeholders** and built ETL workflows from social media APIs.

[Portfolio](https://vasilendata.github.io) · [Data Engineer CV](https://vasilendata.github.io/vasilen-kanchev-cv.pdf) · [Analytics Engineer CV](https://vasilendata.github.io/vasilen-kanchev-cv-analytics.pdf) · [LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) · [Email](mailto:vasilen.business@gmail.com)

## Selected engineering projects

| Project | What to inspect | Operating scope |
|---|---|---|
| [**NYC Taxi Data Platform**](https://github.com/VasilenData/nyc-taxi-data-platform) · [forecast report](https://vasilendata.github.io/labs/forecast/) | Dagster/dbt ingestion, quarantine and atomic publication. Daily pickup forecasts reduced MAE **11.3%** versus a weekly baseline over **16,043 held-out zone-days**. | Local/Docker and CI; historical forecasting replay, not live dispatch. The earlier **31.6M-trip** pipeline benchmark is documented separately. |
| [**E-Commerce Finance Mart**](https://github.com/VasilenData/ecommerce-finance-mart) · [customer prediction report](https://vasilendata.github.io/labs/customer-value/) | Star schema and SQL/Excel reconciliation over **1.07M public invoice lines**. Point-in-time 90-day repeat-purchase prediction achieved ROC-AUC **0.748 / 0.762** in two future test windows. | Historical public data and tested batch scoring. The simple spend baseline beat the learned revenue candidate and was retained; no retention uplift or lifetime profit is claimed. |
| [**HN Pulse**](https://github.com/VasilenData/hn-pulse) · [live dashboard](https://vasilendata.github.io/hn-pulse/) | Python/dbt/DuckDB pipeline with model contracts and tests that gate publication, bounded API retries and a separate hourly freshness check. | GitHub Actions runs the live schedule. A separate Airflow DAG demonstrates local orchestration. |

For streaming roles, inspect the [Wikipedia Streaming Lakehouse](https://github.com/VasilenData/wiki-stream-lakehouse): a local Kafka/Spark implementation with raw-event replay and real Kafka CI recovery tests.

## Seven capabilities, with evidence

The [evidence hub](https://vasilendata.github.io/labs/) connects the implementation, measured result and limits for each direction. These extend the existing projects; the CVs remain focused on three role-relevant examples.

<details>
<summary>Experimentation, customer value, forecasting, finance, serving, search and evaluation</summary>

| Capability | Evidence and scope |
|---|---|
| Product experimentation | [Decision report](https://vasilendata.github.io/labs/experimentation/): 90,189 assigned players; retrospective primary/guardrail protocol, explicit missing exposure/timestamp evidence. |
| Customer retention and future value | [Temporal retail study](https://vasilendata.github.io/labs/customer-value/) and [nested churn evaluation](https://vasilendata.github.io/labs/churn/); no measured retention uplift or lifetime-profit claim. |
| Demand and capacity planning | [Forecast replay](https://vasilendata.github.io/labs/forecast/): 11.3% lower MAE against the weekly baseline; capacity units are hypothetical. |
| Financial decision support | [Management brief](https://vasilendata.github.io/labs/management/): reconciled historical revenue drivers, proposed actions and information still needed before acting. |
| Prediction service operations | [Booking evaluation](https://vasilendata.github.io/labs/service/): 4.068-minute MAE versus 5.574 baseline on 200,000 future-period sampled trips; booking-only features. [Railway trial API / docs](https://taxi-booking-api-demo.up.railway.app/docs), deployed and probed on 11 Nov 2026. One observation, not an uptime history; cold starts and trial expiry remain possible. |
| Domain search and RAG | [Document lifecycle](https://vasilendata.github.io/labs/search/): four local formats, stable identities, incremental search and transactional deletion; small source-informed smoke demonstration. |
| AI regression evaluation | [Release gate](https://vasilendata.github.io/labs/evaluation/): 160 paired retrieval tasks and a rejected regression; full-generation publication tests do not constitute a new LLM benchmark. |

</details>

## Start with the evidence

- **Professional ownership:** [the Gosian case study](https://vasilendata.github.io/gosian/) explains the spreadsheet-to-RDS implementation, daily reporting and the difference between estimated automation savings and wider operational outcomes. Employer code and data are private.
- **Safe publication:** [NYC Taxi publication tests](https://github.com/VasilenData/nyc-taxi-data-platform/blob/main/tests/test_publication.py) exercise failed validation, interrupted publication and preservation of the previous release. The [dated full-data measurement](https://github.com/VasilenData/nyc-taxi-data-platform/blob/main/measurements/full-2026-11-08.json) records the earlier benchmark conditions.
- **Actual run history:** the [dated HN Pulse operations review](https://github.com/VasilenData/hn-pulse/blob/main/docs/operations-review-2026-11-08.md) records observed outcomes, two historical failures and a separately labeled recovery exercise. The [dashboard](https://vasilendata.github.io/hn-pulse/) exposes data age and quality status; a [separate monitor workflow](https://github.com/VasilenData/hn-pulse/actions/workflows/monitor.yml) retains dated freshness observations.
- **Prediction and evaluation:** inspect the [held-out demand forecasts](https://vasilendata.github.io/labs/forecast/), [customer future-value study](https://vasilendata.github.io/labs/customer-value/) and [retrieval regression gate](https://vasilendata.github.io/labs/evaluation/). These are measured public-data experiments with explicit baselines and limits.
- **Business definitions and reconciliation:** inspect the [Finance Mart models and release checks](https://github.com/VasilenData/ecommerce-finance-mart), [interactive explorer](https://vasilendata.github.io/ecommerce-finance-mart/explorer/) and [Tableau dashboard](https://public.tableau.com/app/profile/vasilen.kanchev/viz/E-CommerceFinanceMartSalesDashboard/E-CommerceFinanceMartsalesdashboard).

## Toolkit

**Professional use:** Python, SQL, PostgreSQL, dbt, Docker, AWS RDS, ETL and API integration, data validation, Tableau and Excel.

**Demonstrated in projects:** Dagster, Airflow (local), Kafka, Spark Structured Streaming, DuckDB, dimensional modeling, data contracts, GitHub Actions, scikit-learn, temporal backtesting, customer prediction, regression evaluation gates, BigQuery sandbox measurements and a Databricks Free Edition SQL port. Terraform configuration is validated in CI; it has not been deployed.

## Career progression

| Company | Earlier role | Later role |
|---|---|---|
| Gosian Media LLC | Data Engineer · Jun 2025–May 2026 | Chief Revenue Officer · Jun 2026–Present; continuing hands-on data engineering |
| Influencer Marketing Hub | Data Analyst · Nov 2023–Apr 2024 | Senior Supervisor · May 2024–Jun 2025 |
| Tapin Platforms | Data Administrator · Oct 2021–Sep 2022 | Operations Analyst · Oct 2022–Nov 2023 |

My earlier work includes operations and data administration. That experience helps me connect technical work with the people and decisions it supports. I am studying BSc (Hons) Computer Science at the University of Suffolk, expected 2027, and hold a Higher Certificate in Mathematics and Statistics with Distinction.

## More work

<details>
<summary>Additional projects in data engineering, analytics and ML</summary>

| Project | Focus |
|---|---|
| [Wikipedia Streaming Lakehouse](https://github.com/VasilenData/wiki-stream-lakehouse) | Local Kafka/Spark streaming, replay from retained raw events and real Kafka CI tests for forced-crash recovery. |
| [Data Contracts Platform](https://github.com/VasilenData/data-contracts-platform) | YAML/DuckDB validation, breaking-change detection and regression tests preventing duplicate rule names from downgrading blocking failures. |
| [BigQuery Cost Lab](https://github.com/VasilenData/bigquery-cost-lab) | Public-table dry-run estimates, sandbox scan measurements, SQL linting and exact integer billing ceilings. |
| [Tech Job Market ETL](https://github.com/VasilenData/tech-job-market-etl) | Idempotent PostgreSQL loads, per-source diagnostics and a completeness gate that withholds reports after source failures. |
| [Four-Engine Benchmark](https://github.com/VasilenData/taxi-engines-benchmark) | Recorded queries over 79M taxi trips; cross-engine answer checks, validated worker measurements and atomic result checkpoints. |
| [A/B Test Analysis](https://github.com/VasilenData/ab-test-analysis) | Assignment/exposure contracts, analysis cutoffs and immutable decision reports; retrospective Cookie Cats protocol, with missing timestamps and exposure events disclosed. |
| [E-Commerce Sales & Logistics Dashboard](https://github.com/VasilenData/ecommerce-logistics-dashboard) · [live](https://vasilendata.github.io/ecommerce-logistics-dashboard/) | PostgreSQL views linking revenue, delivery and reviews; identifier-preserving imports and explicit missing-estimate handling. |
| [Taxi Trip Duration Service](https://github.com/VasilenData/taxi-eta-service) | Booking-only LightGBM/FastAPI model with separate train/selection/calibration/test months; June sampled MAE 4.068 minutes versus 5.574 baseline. [Public trial API](https://taxi-booking-api-demo.up.railway.app/docs) probed on 11 Nov 2026; versioned delivery and drift checks, without a production-uptime claim. |
| [Evaluated AI Research Assistant](https://github.com/VasilenData/research-assistant-eval) · [release gate report](https://vasilendata.github.io/labs/evaluation/) | Fingerprinted baseline/candidate evaluation with paired quality, p95 latency, API-cost and error gates. The measured 160-query retrieval comparison is separate from historical language-model answer evaluation. |
| [Retrieval Evaluation for RAG](https://github.com/VasilenData/rag-retrieval-eval) | Bounded four-format ingestion, stable document identities, transactional incremental SQLite search and deletion; historical retrieval results remain separate. |
| [Customer Churn Model](https://github.com/VasilenData/customer-churn-model) | Cross-fit selection/calibration with customer identities; bounded logistic rerun AUC 0.8446 and Brier 0.1363 on the previously inspected split, plus a tested illustrative threshold policy. |

</details>

For remote roles involving data quality, financial reporting or pipeline ownership, [contact me on LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) or [email me](mailto:vasilen.business@gmail.com).
