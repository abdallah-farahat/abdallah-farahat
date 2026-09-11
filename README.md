<!--
  GitHub Profile README for github.com/abdallah-farahat
  ─────────────────────────────────────────────────────
  HOW TO USE:
  1. Create a repo with the EXACT same name as your GitHub username: abdallah-farahat/abdallah-farahat
  2. Put this file in it as README.md
  3. Replace every <!-- TODO --> marked item below before publishing
-->

<div align="center">

<!-- Typing effect tagline. Swap text via the &lines= params if you want different rotating lines. -->
<a href="https://github.com/abdallah-farahat">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=560&lines=Data+Engineer+%7C+SQL+%2B+Python+%2B+Cloud;Building+Data+Warehouses+that+don't+break;Final-year+Business+Analytics+%E2%86%92+Data+Engineering" alt="Typing SVG" />
</a>

### Abdallah Ali Abdelgawad
**Data Engineer** — SQL-first data warehouses, Azure pipelines, Airflow orchestration

<!-- TODO: replace with your real contact links -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdallah-ali-da)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:your.email@example.com)

</div>

---

### About

I'm a final-year Business Analytics student who spends most of his time in T-SQL and Airflow DAGs rather than dashboards. My focus is **data engineering**: designing warehouses, building ETL/ELT pipelines, and making sure the data that lands in a table is actually correct — not just present.

I placed **1st in the Data Science track** at my university's Datathon, as the only 3rd-year team competing against seniors — owning the data engineering side of a one-week build under real time pressure.

Currently deepening my Big Data / orchestration skills (PySpark, Hadoop, Spark, dbt) through an intensive training program, on top of DataCamp's Associate Data Engineer and SQL Associate certifications.

---

### Tech Stack

<div align="center">

**Languages & Core**
<br>
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

**Databases**
<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Azure SQL](https://img.shields.io/badge/Azure_SQL_Database-0078D4?style=flat&logo=microsoftazure&logoColor=white)

**Cloud & Orchestration**
<br>
![Azure](https://img.shields.io/badge/Azure_Blob_Storage-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)

**DevOps & Tools**
<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

**BI**
<br>
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

</div>

> **Currently learning:** PySpark · Hadoop · Spark · dbt

---

### Featured Projects

#### 🔹 [Olist Data Warehouse](https://github.com/abdallah-farahat/Olist_Data_Department)
Medallion-architecture data warehouse on Azure SQL Database, built solo for a 7-person team platform — I independently owned the **Bronze, Silver, and Gold** layers end to end.
- Bronze: bulk-loaded 10 source tables (~375K rows) from Azure Blob Storage via T-SQL `BULK INSERT` / External Data Source, orchestrated by a single stored procedure with batch-level run auditing.
- Silver: window-function deduplication, type casting, and repair of corrupted Portuguese-language text encoding.
- Gold: star schema (4 dimensions, 2 facts) powering a deployed analytics dashboard.

<!-- TODO: this repo currently shows as a fork on GitHub. If the commit history in the fork is genuinely yours, keep it. If not, either push your own history here or replace this link with your primary Olist DW repo (Olist-Data-WhareHouse) and drop this one from "Featured." -->

#### 🔹 [Stock Market Data Pipeline](https://github.com/abdallah-farahat/Stock-Market-Data-Pipeline-Analysis)
Solo, production-style pipeline — Airflow-orchestrated, Docker-containerized, 31 tasks — ingesting daily OHLCV data for 10 tickers from the Yahoo Finance API on an automated weekday schedule into PostgreSQL.
- Watermark-based incremental loading with idempotent `INSERT ... ON CONFLICT` upserts — safe to re-run without duplicating data.
- An 8-check automated data quality auditor (nulls, duplicates, price/volume integrity, outlier flags) with full run-level logging.

#### 🔹 [Datathon Winner — Bank Term Deposit Prediction](https://github.com/abdallah-farahat/El_Farghaly_Bros.)
**1st place, Data Science track** — as the only 3rd-year team against senior competitors, delivered in one week on a ~41K-record banking dataset.
- Owned the data engineering layer: ingested, cleaned, and structured raw banking data from Azure SQL using SQL and pandas, feeding the team's feature engineering and modeling work.

<!-- TODO: same fork note as above — confirm commit history or reframe as a case study rather than a "browse the code" link. -->

#### 🔹 [Car Resale Price Prediction](https://github.com/abdallah-farahat/Car_Sales_Regression_Analysis)
Data preprocessing for a 16,733-record used-car dataset (pandas, NumPy), validating the data behind a Random Forest regression model delivered via a Streamlit dashboard.

<!-- TODO: same fork note. -->

---

### GitHub Stats

<div align="center">

<!-- TODO: replace abdallah-farahat below if you rename your GitHub username -->
<img height="165" src="https://github-readme-stats.vercel.app/api?username=abdallah-farahat&show_icons=true&theme=github_dark&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdallah-farahat&layout=compact&theme=github_dark&hide_border=true" />

</div>

---

### Certifications & Training

- DataCamp — Associate Data Engineer
- DataCamp — SQL Associate
- Microsoft Student Ambassadors — Data Engineering Track *(selected via competitive interview)*
- Data Pill Data Engineering Program *(in progress — SQL, Data Warehousing, ETL/ELT, Big Data, dbt)*

---

<div align="center">

📍 Badr City, Cairo, Egypt &nbsp;|&nbsp; 🎓 Business Analytics, Egyptian Russian University — Class of 2026

<!-- TODO: add email + phone once you decide what's public -->
[LinkedIn](https://linkedin.com/in/abdallah-ali-da) · [GitHub](https://github.com/abdallah-farahat)

</div>
