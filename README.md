# Vasilen Kanchev

**Data Engineer | Financial data pipelines & reporting | Python, SQL, dbt**

Porto, Portugal · EU citizen · Open to full-time remote Data Engineer and SQL/dbt Analytics Engineer roles with teams that can hire in Portugal.

I built and maintain Gosian's **agency-wide cash-flow reporting system**, live since **October 2026** with **daily refreshes**. I consolidated **30+ spreadsheets into PostgreSQL on AWS RDS** using Python, Docker and dbt, saving an estimated **10+ hours of manual data entry each week**. The [Gosian case study](https://vasilendata.github.io/gosian/) describes the implementation and distinguishes estimated automation savings from wider operational outcomes. Employer code and data are private.

I was promoted from **Data Engineer to Chief Revenue Officer in June 2026** at Gosian Media, while continuing hands-on data engineering. I am now targeting a dedicated engineering role focused on pipeline ownership, data quality and business reporting. Previously, I automated Python/Tableau KPI reporting for **15+ stakeholders** and built ETL workflows from social media APIs.

[Portfolio](https://vasilendata.github.io) · [Data Engineer CV](https://vasilendata.github.io/vasilen-kanchev-cv.pdf) · [Analytics Engineer CV](https://vasilendata.github.io/vasilen-kanchev-cv-analytics.pdf) · [LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) · [Email](mailto:vasilen.business@gmail.com)

## Selected engineering projects

### Meterwork — Usage Metering & Billing Analytics

**Problem:** Retried requests, late usage and backdated prices can change a customer's usage statement. Every change needs an explanation without rewriting the original statement.

**Built:** A Python/FastAPI/PostgreSQL system with account isolation, immutable event identities, versioned pricing and transactional statement publication. Separate effective and recorded timestamps preserve what was known at each publication; an event-level comparison explains late usage, corrections and repricing.

**Result:** A **12 November 2026 local PostgreSQL exercise** reconciled **11,760 accepted events across 24 synthetic accounts and 72 statement revisions**, with **960 retries deduplicated** and **zero discrepancy** against independent SQL and fixture arithmetic. Recovery checks cover interrupted publication and backup restoration. The public result is read-only; no hosted backend, real customer traffic or payment collection is claimed.

[View the result](https://vasilendata.github.io/usage-metering-platform/#reconciliation) · [Inspect the engineering](https://github.com/VasilenData/usage-metering-platform/blob/main/docs/LANDMARK.md)

### NYC Taxi Data Platform

**Problem:** Invalid trip records and failed rebuilds can leave analytics incomplete or inconsistent.

**Built:** Python/Dagster/dbt ingestion, explicit quarantine reasons and staged publication of eight consumer tables in DuckDB. Reviewed change plans bind corrections and model changes to source, schema and stored-content fingerprints; failed candidates preserve the last valid consumer release.

**Result:** A **12 November 2026 full-data run** reconciled **31.6M historical trips** through the current publisher. Separate 30,000-row exercises verified selective corrections, failed-candidate recovery and model-only reclassification; seven additional scenarios detected stale plans after same-count data edits and schema changes. This is measured local Windows execution, not a live cloud warehouse. An optional five-row [Iceberg comparison](https://github.com/VasilenData/nyc-taxi-data-platform/blob/main/docs/ICEBERG.md) demonstrates single-table snapshots and rollback separately.

[View the result](https://vasilendata.github.io/projects/nyc-taxi/) · [Inspect the engineering](https://github.com/VasilenData/nyc-taxi-data-platform#evidence-to-inspect)

### E-Commerce Finance Mart

**Problem:** Messy invoices and later source corrections make financial reporting difficult to reconcile and explain.

**Built:** A DuckDB SQL star schema and finance marts over **1.07M historical public invoice lines**, with explicit metric definitions and row/amount reconciliation. SQL, Excel and the sales explorer are checked together in one release. A separate synthetic subscription extension preserves original closes and traces later restatements to source revisions, customer/month MRR and invoice balances.

**Result:** The historical release passed **14 blocking checks** and **124 recalculated workbook-to-SQL comparisons**, with **zero formula errors**. The subscription exercise passed **33 report reconciliations and 44 restatement checks**, distinguishing changed recurring revenue and invoiced amounts from cash collected. These are technical validation results on historical public data and generated subscription records, not employer ROI.

[View the sales explorer](https://vasilendata.github.io/ecommerce-finance-mart/explorer/) · [View the restatement explorer](https://vasilendata.github.io/ecommerce-finance-mart/subscriptions/) · [Inspect the engineering](https://github.com/VasilenData/ecommerce-finance-mart)

## Toolkit

**Professional use:** Python, SQL, PostgreSQL, dbt, Docker, AWS RDS, ETL and API integration, data validation, Tableau and Excel.

**Demonstrated in projects:** FastAPI, PostgreSQL row-level security, Dagster, Airflow (local), Kafka, Spark Structured Streaming, DuckDB, dimensional modeling, data contracts, Git, pytest, GitHub Actions (CI/CD), scikit-learn, temporal backtesting and regression evaluation gates. BigQuery measurements use a sandbox; the Databricks Free Edition work is a SQL port. Terraform configuration is validated in CI and has not been deployed.

## Career progression

| Company | Earlier role | Later role |
|---|---|---|
| Gosian Media LLC | Data Engineer · Jun 2025–May 2026 | Chief Revenue Officer · Jun 2026–Present; continuing hands-on data engineering |
| Influencer Marketing Hub | Data Analyst · Nov 2023–Apr 2024 | Senior Supervisor · May 2024–Jun 2025 |
| Tapin Platforms | Data Administrator · Oct 2021–Sep 2022 | Operations Analyst · Oct 2022–Nov 2023 |

My earlier work includes operations and data administration. That experience helps me connect technical work with the people and decisions it supports. I am studying BSc (Hons) Computer Science at the University of Suffolk, expected 2027, and hold a Higher Certificate in Mathematics and Statistics with Distinction.

## More work

- [HN Pulse](https://vasilendata.github.io/hn-pulse/): live API-to-dashboard pipeline with completeness gates, freshness monitoring and dated [operating evidence](https://github.com/VasilenData/hn-pulse/blob/main/docs/operations-review-2026-11-12.md). The latest outbox ownership fix is published and tested; its rollout to the Railway monitor has not been verified.
- [Demand forecasting](https://vasilendata.github.io/labs/forecast/): historical replay reduced MAE **11.3%** versus a weekly baseline across **16,043 held-out zone-days**. This is not live dispatch.
- [Customer future-value study](https://vasilendata.github.io/labs/customer-value/): 90-day repeat-purchase ROC-AUC **0.748 / 0.762** across two future test windows. The learned revenue candidate lost to a simple spend baseline, which was retained. No retention uplift or lifetime profit is claimed.
- [Additional experiments and reports](https://vasilendata.github.io/labs/): evaluation, search, experimentation and prediction-service evidence, with each report's scope and limitations.

For remote roles involving data quality, financial reporting or pipeline ownership, [contact me on LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) or [email me](mailto:vasilen.business@gmail.com).
