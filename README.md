# Vasilen Kanchev

**Data Engineer | Python, SQL, dbt, PostgreSQL and AWS RDS**

Porto, Portugal · EU citizen · Open to full-time remote Data Engineer and SQL/dbt Analytics Engineer roles with teams that can hire in Portugal.

I built and maintain Gosian's **agency-wide cash-flow reporting system**, live since **October 2026** with **daily refreshes**. I consolidated **30+ spreadsheets into PostgreSQL on AWS RDS** using Python, Docker and dbt, saving an estimated **10+ hours of manual data entry each week**. The [Gosian case study](https://vasilendata.github.io/gosian/) describes the implementation and distinguishes estimated automation savings from wider operational outcomes. Employer code and data are private.

I was promoted from **Data Engineer to Chief Revenue Officer in June 2026** at Gosian Media, while continuing hands-on data engineering. I am now targeting a dedicated engineering role focused on pipeline ownership, data quality and business reporting. Previously, I automated Python/Tableau KPI reporting for **15+ stakeholders** and built ETL workflows from social media APIs.

[Portfolio](https://vasilendata.github.io) · [Data Engineer CV](https://vasilendata.github.io/vasilen-kanchev-cv.pdf) · [Analytics Engineer CV](https://vasilendata.github.io/vasilen-kanchev-cv-analytics.pdf) · [LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) · [Email](mailto:vasilen.business@gmail.com)

## Selected engineering projects

### E-Commerce Finance Mart

**Problem:** Messy invoice data makes revenue, returns and customer reporting difficult to reconcile.

**Built:** A DuckDB SQL star schema and finance marts over **1.07M historical public invoice lines**, with explicit metric definitions and row/amount reconciliation. SQL, Excel and the interactive explorer are checked together in one release.

**Result:** The 11 November 2026 release passed **14 blocking checks** and **124 recalculated workbook-to-SQL comparisons**, with **zero formula errors**. This is a public-data project; no employer ROI is claimed.

[View the result](https://vasilendata.github.io/ecommerce-finance-mart/explorer/) · [Inspect the engineering](https://github.com/VasilenData/ecommerce-finance-mart)

### NYC Taxi Data Platform

**Problem:** Invalid trip records and failed rebuilds can leave analytics incomplete or inconsistent.

**Built:** Dagster/dbt ingestion, explicit quarantine reasons and staged publication in DuckDB. Failure tests exercise rejected candidates and interrupted publication while preserving the previous valid consumer release.

**Result:** A dated benchmark reconciled **31.6M trips** across valid and quarantined records. That measurement predates staged publication; the current failure tests are separate evidence. Runs locally, in Docker and in CI.

[View the result](https://vasilendata.github.io/projects/nyc-taxi/) · [Inspect the engineering](https://github.com/VasilenData/nyc-taxi-data-platform#evidence-to-inspect)

### HN Pulse

**Problem:** A live dashboard needs complete, validated data and a visible signal when publication falls behind.

**Built:** A Python/dbt/DuckDB pipeline with model contracts, publication gates, bounded API retries and an independent freshness monitor.

**Result:** A public dashboard exposes data age and quality status. GitHub Actions publication and hourly monitoring are configured; recorded operations include failures and scheduling gaps. The Airflow DAG demonstrates separate local orchestration.

[View the result](https://vasilendata.github.io/hn-pulse/) · [Inspect the engineering](https://github.com/VasilenData/hn-pulse)

## Toolkit

**Professional use:** Python, SQL, PostgreSQL, dbt, Docker, AWS RDS, ETL and API integration, data validation, Tableau and Excel.

**Demonstrated in projects:** Dagster, Airflow (local), Kafka, Spark Structured Streaming, DuckDB, dimensional modeling, data contracts, GitHub Actions, scikit-learn, temporal backtesting and regression evaluation gates. BigQuery measurements use a sandbox; the Databricks Free Edition work is a SQL port. Terraform configuration is validated in CI and has not been deployed.

## Career progression

| Company | Earlier role | Later role |
|---|---|---|
| Gosian Media LLC | Data Engineer · Jun 2025–May 2026 | Chief Revenue Officer · Jun 2026–Present; continuing hands-on data engineering |
| Influencer Marketing Hub | Data Analyst · Nov 2023–Apr 2024 | Senior Supervisor · May 2024–Jun 2025 |
| Tapin Platforms | Data Administrator · Oct 2021–Sep 2022 | Operations Analyst · Oct 2022–Nov 2023 |

My earlier work includes operations and data administration. That experience helps me connect technical work with the people and decisions it supports. I am studying BSc (Hons) Computer Science at the University of Suffolk, expected 2027, and hold a Higher Certificate in Mathematics and Statistics with Distinction.

## More work

- [Demand forecasting](https://vasilendata.github.io/labs/forecast/): historical replay reduced MAE **11.3%** versus a weekly baseline across **16,043 held-out zone-days**. This is not live dispatch.
- [Customer future-value study](https://vasilendata.github.io/labs/customer-value/): 90-day repeat-purchase ROC-AUC **0.748 / 0.762** across two future test windows. The learned revenue candidate lost to a simple spend baseline, which was retained. No retention uplift or lifetime profit is claimed.
- [Additional experiments and reports](https://vasilendata.github.io/labs/): evaluation, search, experimentation and prediction-service evidence, with each report's scope and limitations.

For remote roles involving data quality, financial reporting or pipeline ownership, [contact me on LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) or [email me](mailto:vasilen.business@gmail.com).
