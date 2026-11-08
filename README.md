# Vasilen Kanchev

**Data Engineer and Chief Revenue Officer** in Porto, Portugal. Python, dbt, PostgreSQL, AWS.

I have 7 years in data roles across operations, analytics and engineering, and I lead people as well as pipelines: 80 employees at Gosian Media (where revenue grew 7.5x) and 150 at Influencer Marketing Hub. I build automated ETL pipelines, manage PostgreSQL databases and develop BI reporting workflows, turning messy, unstructured data into optimized relational schemas. I also competed internationally as a professional esports athlete, and I work well in high-pressure, analytical environments.

[Portfolio](https://vasilendata.github.io) · [CV (PDF)](https://vasilendata.github.io/vasilen-kanchev-cv.pdf) · [LinkedIn](https://www.linkedin.com/in/vasilenkanchev/) · [Email](mailto:vasilen.business@gmail.com)

Open to full-time data engineering and data leadership roles.

## How I work

- **Architecture first.** I design normalized, scalable schemas before writing application code.
- **Data integrity.** Automated validation, idempotent pipelines and strict ELT/ETL testing with dbt.
- **Automation over manual effort.** If a process needs manual data entry, I script it, containerize it with Docker and schedule it with GitHub Actions.

## Projects

| Project | What it does | Stack |
|---|---|---|
| [**Wikipedia Streaming Lakehouse**](https://github.com/VasilenData/wiki-stream-lakehouse) | Live Wikipedia edits through Kafka and Spark Structured Streaming into Parquet, queried with DuckDB. Late and malformed events are handled and tested on real Kafka in CI. Terraform for AWS is validated, not deployed. | Kafka, Spark, DuckDB, Terraform |
| [**NYC Taxi Data Platform**](https://github.com/VasilenData/nyc-taxi-data-platform) | 31.6 million trips through Dagster and dbt with an enforced contract, a quarantine table that keeps every rejected row and its reason, and blocking checks that stop a corrupted month. 10 months build in 62 s. | Dagster, dbt, DuckDB, Docker |
| [**Taxi Trip Duration Service**](https://github.com/VasilenData/taxi-eta-service) | LightGBM with 62% lower error than a baseline on a held-out future month (3.52 vs 9.33 min), served by a validated FastAPI with MLflow, champion/challenger promotion and drift monitoring. | LightGBM, FastAPI, MLflow, Docker |
| [**Evaluated AI Research Assistant**](https://github.com/VasilenData/research-assistant-eval) | A local 1.5B model answering from 2,835 recent arXiv abstracts. Retrieval lifts answers with the reference fact from 3.8% to 50.6%, a gate blocks fabricated-topic answers, and the claim checker's own accuracy (85.5%) is measured. | llama.cpp, BM25, fastembed, NLI |
| [**E-Commerce Finance Mart**](https://github.com/VasilenData/ecommerce-finance-mart) ([live explorer](https://vasilendata.github.io/ecommerce-finance-mart/explorer/)) | 1.07M real invoice lines from a UK retailer normalized into a star schema, reconciled to the penny, with finance and customer marts, an Excel workbook of live formulas and a self-serve explorer and a [Tableau dashboard](https://public.tableau.com/app/profile/vasilen.kanchev/viz/E-CommerceFinanceMartSalesDashboard/E-CommerceFinanceMartsalesdashboard). Public practice data. | DuckDB, SQL, Excel, Python |
| [**A/B Test Analysis**](https://github.com/VasilenData/ab-test-analysis) | A tested toolkit and analysis of a real 90,189-player experiment: sample-ratio check, z-test with confidence intervals, Holm correction, power and A/A validation, plus sequential testing and CUPED checked by simulation. Moving the gate cut day-7 retention by 0.82 points (p = 0.0016). Public dataset. | Python, SciPy, pytest |
| [**BigQuery Cost Lab**](https://github.com/VasilenData/bigquery-cost-lab) | Measured BigQuery query costs on a public table and a sandbox (SELECT * with LIMIT scans 2.38 TB; clustering cut a range scan 11.6x), plus a tested SQL linter and bytes estimator. Public data, no money spent. | Python, sqlglot, BigQuery |
| [**HN Pulse**](https://github.com/VasilenData/hn-pulse) ([live](https://vasilendata.github.io/hn-pulse/)) | Hacker News API, then dbt models under enforced data contracts with 27 automated tests, then DuckDB and a dashboard. Orchestrated by an Airflow DAG and published on a schedule with GitHub Actions. | Python, dbt, DuckDB, Airflow, GitHub Actions |
| [**Four-Engine Benchmark**](https://github.com/VasilenData/taxi-engines-benchmark) | The same four queries on DuckDB, Polars, pandas and Spark over 79 million NYC taxi trips, answers cross-checked. DuckDB 1.4 s against 32.8 s for pandas. | DuckDB, Polars, pandas, Spark |
| [**Retrieval Evaluation for RAG**](https://github.com/VasilenData/rag-retrieval-eval) | BM25, Qdrant vectors, rank fusion and reranking measured on 2,000 labeled questions; recall@1 from 76% to 86% with reranking. Retrieval only. | Qdrant, BM25, fastembed |
| [**Tech Job Market ETL**](https://github.com/VasilenData/tech-job-market-etl) | Python ingestion from public REST APIs. It validates and normalizes JSON payloads and loads them idempotently into PostgreSQL, scheduled daily with GitHub Actions cron and error logging. | Python, PostgreSQL, GitHub Actions |
| [**E-Commerce Sales & Logistics Dashboard**](https://github.com/VasilenData/ecommerce-logistics-dashboard) ([live](https://vasilendata.github.io/ecommerce-logistics-dashboard/)) | SQL with CTEs, joins and window functions over 100,000+ orders. It maps revenue against delivery delays to find regional logistics bottlenecks. | SQL, PostgreSQL, Chart.js |
| [**Customer Churn Model**](https://github.com/VasilenData/customer-churn-model) | Supervised Random Forest pipeline with feature engineering and EDA. ROC-AUC 0.84 and 78% recall on churners (76% accuracy, held-out test set). | Python, Pandas, Scikit-Learn |

## Toolkit

- **Languages and databases:** Python, SQL, PostgreSQL, Bash
- **Data engineering:** dbt, Airflow, Kafka, Spark, DuckDB, Polars, Terraform, Docker, GitHub Actions, AWS, Pandas
- **BI and analytics:** Tableau, Scikit-Learn, Git
