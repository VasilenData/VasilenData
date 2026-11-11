# Vasilen Kanchev

**Data Engineer | Python, SQL, dbt, PostgreSQL and AWS RDS**

Porto, Portugal · EU citizen · Open to full-time remote Data Engineer and SQL/dbt Analytics Engineer roles with teams that can hire in Portugal.

I build pipelines and reporting systems for business decisions. At Gosian Media, I was promoted from **Data Engineer to Chief Revenue Officer in June 2026**, while continuing hands-on data engineering. I am now targeting a dedicated engineering role focused on pipeline ownership, data quality and business reporting.

I built and maintain Gosian's **agency-wide cash-flow reporting system**, live since **October 2026** with **daily refreshes**. I consolidated **30+ spreadsheets into PostgreSQL on AWS RDS** using Python, Docker and dbt, saving an estimated **10+ hours of manual data entry each week**. Previously, I automated Python/Tableau KPI reporting for **15+ stakeholders** and built ETL workflows from social media APIs.

[Portfolio](https://vasilendata.github.io) · [Data Engineer CV](https://vasilendata.github.io/vasilen-kanchev-cv.pdf) · [Analytics Engineer CV](https://vasilendata.github.io/vasilen-kanchev-cv-analytics.pdf) · [LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) · [Email](mailto:vasilen.business@gmail.com)

## Selected engineering projects

| Project | What to inspect | Operating scope |
|---|---|---|
| [**E-Commerce Finance Mart**](https://github.com/VasilenData/ecommerce-finance-mart) · [customer prediction report](https://vasilendata.github.io/labs/customer-value/) | Star schema and SQL/Excel reconciliation over **1.07M public invoice lines**. Point-in-time 90-day repeat-purchase prediction achieved ROC-AUC **0.748 / 0.762** in two future test windows. | Historical public data and tested batch scoring. The simple spend baseline beat the learned revenue candidate and was retained; no retention uplift or lifetime profit is claimed. |
| [**NYC Taxi Data Platform**](https://github.com/VasilenData/nyc-taxi-data-platform) · [forecast report](https://vasilendata.github.io/labs/forecast/) | Dagster/dbt ingestion, quarantine and atomic publication. Daily pickup forecasts reduced MAE **11.3%** versus a weekly baseline over **16,043 held-out zone-days**. | Local/Docker and CI; historical forecasting replay, not live dispatch. The earlier **31.6M-trip** pipeline benchmark is documented separately. |
| [**HN Pulse**](https://github.com/VasilenData/hn-pulse) · [live dashboard](https://vasilendata.github.io/hn-pulse/) | Python/dbt/DuckDB pipeline with model contracts and tests that gate publication, bounded API retries and a separate hourly freshness check. | GitHub Actions runs the live schedule. A separate Airflow DAG demonstrates local orchestration. |

## Start with the evidence

- **Professional ownership:** [the Gosian case study](https://vasilendata.github.io/gosian/) explains the spreadsheet-to-RDS implementation, daily reporting and the difference between estimated automation savings and wider operational outcomes. Employer code and data are private.
- **Safe publication:** [NYC Taxi publication tests](https://github.com/VasilenData/nyc-taxi-data-platform/blob/main/tests/test_publication.py) exercise failed validation, interrupted publication and preservation of the previous release. The [dated full-data measurement](https://github.com/VasilenData/nyc-taxi-data-platform/blob/main/measurements/full-2026-11-08.json) records the earlier benchmark conditions.
- **Actual run history:** the [dated HN Pulse operations review](https://github.com/VasilenData/hn-pulse/blob/main/docs/operations-review-2026-11-08.md) records observed outcomes, two historical failures and a separately labeled recovery exercise. The [dashboard](https://vasilendata.github.io/hn-pulse/) exposes data age and quality status; a [separate monitor workflow](https://github.com/VasilenData/hn-pulse/actions/workflows/monitor.yml) retains dated freshness observations.
- **Forecast and customer prediction:** inspect the [held-out demand forecasts](https://vasilendata.github.io/labs/forecast/) and [customer future-value study](https://vasilendata.github.io/labs/customer-value/). These are measured public-data experiments with explicit baselines and limits.
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

Browse the [evidence hub](https://vasilendata.github.io/labs/) for additional projects and their supporting reports.

For remote roles involving data quality, financial reporting or pipeline ownership, [contact me on LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) or [email me](mailto:vasilen.business@gmail.com).
