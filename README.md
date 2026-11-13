# Vasilen Kanchev

**Data Engineer | Python, SQL & dbt | Financial reporting and reliable pipelines**

I build data systems that make reporting consistent and changes explainable. At Gosian Media, I built and maintain agency-wide cash-flow reporting, refreshed daily since October 2026. I progressed from Data Engineer to **Chief Revenue Officer** in June 2026 and continued hands-on engineering. I am now seeking a dedicated Data Engineer or Analytics Engineer role.

**Porto, Portugal · EU citizen · Open to full-time remote roles with teams that can hire in Portugal.**

[Portfolio](https://vasilendata.github.io/) · [Data Engineer CV](https://vasilendata.github.io/vasilen-kanchev-cv.pdf) · [Analytics Engineer CV](https://vasilendata.github.io/vasilen-kanchev-cv-analytics.pdf) · [LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) · [Email](mailto:vasilen.business@gmail.com)

## Three projects to inspect

### Meterwork — explain a changed usage statement

Built Python/FastAPI/PostgreSQL usage processing that handles retries, late events and historical prices. **72 statement revisions across 24 synthetic accounts** reconciled to independent calculations. Separate HTTP tests verify restricted database credentials and account-specific request limits.

[View the result](https://vasilendata.github.io/usage-metering-platform/#reconciliation) · [Inspect the engineering](https://github.com/VasilenData/usage-metering-platform)

*Synthetic local/CI exercises; public demo is read-only.*

### NYC Taxi — keep valid reporting available after a failed refresh

Built a Dagster/dbt/DuckDB pipeline that validates a candidate before publishing eight tables together. A local run reconciled **31.6M historical trips**; separate failure and correction tests verify that rejected changes preserve the previous valid release.

[View the result](https://vasilendata.github.io/projects/nyc-taxi/) · [Inspect the engineering](https://github.com/VasilenData/nyc-taxi-data-platform)

*Historical public data; AWS configuration remains undeployed.*

### Finance Mart — reconcile reports and explain corrections

Built SQL reporting over **1.07M public invoice lines**, with **124 Excel-to-SQL comparisons**. A separate dbt subscription exercise preserves original closes and verifies that late corrections and backfills match full rebuilds on DuckDB and PostgreSQL.

[View the result](https://vasilendata.github.io/ecommerce-finance-mart/explorer/) · [Inspect the engineering](https://github.com/VasilenData/ecommerce-finance-mart)

*Historical retail data; subscription records are synthetic.*

## Toolkit

**Professional:** Python, SQL, dbt, PostgreSQL, Docker, AWS RDS, Tableau and Excel.

**Portfolio:** Dagster, DuckDB, FastAPI, GitHub Actions, pytest and data contracts.

[Professional case study](https://vasilendata.github.io/gosian/) · [Additional experiments](https://vasilendata.github.io/labs/)

Project implementation and review are AI-assisted; each repository documents reproducible evidence and its limits.
