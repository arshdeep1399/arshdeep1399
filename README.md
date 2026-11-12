# Hi, I'm Arshdeep Singh

### Data Engineer | Data Pipelines, Cloud Data Platforms, Data Quality, AI

I build reliable, well-tested data pipelines. I spent nearly 3 years at Capgemini on Bayer's enterprise data platform, which loaded 2 TB+ a day from about 20 source systems into 10+ production reports. Today I build lakehouse pipelines on AWS and Databricks with automated data quality checks. M.P.S. in Data Science from UMBC (GPA 3.87).

Based in the Washington, DC area (Maryland). Open to data engineering roles: on-site, hybrid, or remote, anywhere in the U.S.

---

## What I work on

- **Lakehouse pipelines:** S3 to Delta Lake across raw, cleansed and curated layers, scheduled with Databricks Workflows
- **Data quality:** automated checks that fail the pipeline and alert before bad data reaches analysts; root-causing defects so they stay fixed
- **Production operations:** owned 9 of 150+ production process chains at a 99% SLA; cut load runtime 50% during a large-scale platform migration
- **Data for AI:** RAG pipelines, document-to-JSON extraction, and LLM agents. I use Claude Code in my day-to-day engineering work

---

## Experience

| Role | Where | When |
| :--- | :--- | :--- |
| Data Engineer | Community Dreams Foundation (remote) | Aug 2026 - present |
| Graduate Research Analyst | University of Maryland, Baltimore County | Sep 2024 - Jan 2026 |
| Associate Consultant, Data and Analytics | Capgemini (client: Bayer) | Sep 2021 - Jul 2024 |
| Reporting Analyst | EXL Services | Jun 2021 - Sep 2021 |

---

## Tech stack

| Area | Tools |
| :--- | :--- |
| **Languages** | Python, SQL, PySpark / Spark SQL, Bash, HANA SQLScript, ABAP |
| **Processing & storage** | Databricks, Delta Lake, Apache Spark, DuckDB, Parquet, Hadoop / Hive, SAP BW/HANA |
| **Orchestration & transformation** | Apache Airflow, dbt, Databricks Workflows, AWS Step Functions |
| **Cloud & DevOps** | AWS (S3, Glue, Lambda, Step Functions, Athena, IAM, QuickSight), Terraform, Docker, Git, GitHub Actions |
| **Databases** | PostgreSQL, SQL Server, MongoDB Atlas |
| **BI** | Power BI, Tableau, QuickSight, Streamlit |
| **AI & ML** | LLM agents, RAG, embeddings, vector search, Claude and Llama APIs, Playwright, scikit-learn, PyTorch |

---

## Featured projects

### [Spec-Driven AI QA Agent](https://github.com/arshdeep1399/agentic-qa-agent)
**Python · Playwright · Claude / Llama 3.3 via Groq · pytest** (Agentic AI Hackathon, Oct 2026)

- Reads a product spec, extracts 36 testable requirements and runs 42 normal, negative and edge-case scenarios in a real browser
- Checks what actually changed (balances, records in both account histories, the app's own API) instead of trusting UI success messages
- One full run: 190 assertions, 6 defects found (4 critical), with screenshots and reproduction steps for each
- Uses the LLM only where judgment is needed, so a run costs cents

### [Cloud Data Pipeline on Databricks and AWS](https://github.com/arshdeep1399/Baltimore-Crime-hotspot-and-Prediction)
**Databricks · PySpark · AWS (S3, Glue, Athena, QuickSight)**

- 350K+ Baltimore crime records, 2010 to 2025, from the city's open data portal (updated weekly)
- S3 data lake with schema alignment, regex extraction and data quality validation in PySpark, cataloged in Glue
- K-Means hotspot clustering (silhouette about 0.60) and classification models (gradient boosting, AUC 0.777)

### [AI Legal Advisor](https://github.com/arshdeep1399/ai-legal-advisor)
**Python · Streamlit · MongoDB Atlas Vector Search · Llama 3.3 via Groq** (UMBC capstone, team of 3)

- RAG pipeline: document chunking, embeddings, vector search and structured prompts
- Redacts PII (SSNs, card numbers, emails, phone numbers and more) before any text reaches the model

### Also
- [Metastatic cancer detection](https://github.com/arshdeep1399/ImageClassification): PyTorch CNNs on histopathology images, 0.877 ROC AUC
- [NHTSA vehicle safety ratings](https://github.com/arshdeep1399/CarRatingsNHTSA): multi-class classification with scikit-learn

---

## Let's connect

<p align="left">
  <a href="https://www.linkedin.com/in/singharsh1399"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:singharshi1999@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>
