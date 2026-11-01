<div align="center">

![Sanjeev Kumar Pandey — Data Engineer to AI Engineer](https://capsule-render.vercel.app/api?type=waving&color=0:0B1F3A,100:0A66C2&height=190&section=header&text=Sanjeev%20Kumar%20Pandey&fontSize=38&fontColor=FFFFFF&desc=Data%20Engineer%20%E2%86%92%20AI%20Engineer&descSize=18&descAlignY=62&animation=fadeIn)

![Typing: Building intelligent data platforms on Azure](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=0A66C2&center=true&vCenter=true&width=700&lines=Building+intelligent+data+platforms+on+Azure;Databricks,+PySpark,+Delta+Lake,+RAG,+Agentic+AI)

[![Open to Work](https://img.shields.io/badge/Open_to_Work-India-16a34a?style=for-the-badge)](https://www.linkedin.com/in/sanjeev-pandey-7a45831ba)
![Location: India, On-site, Hybrid, Remote](https://img.shields.io/badge/India-On--site_%E2%80%A2_Hybrid_%E2%80%A2_Remote-0A66C2?style=for-the-badge)
![Experience: 3+ Years, Azure / Databricks](https://img.shields.io/badge/3%2B_Years-Azure_%2F_Databricks-FF3621?style=for-the-badge)

</div>

---

## About

Data Engineer at **Multiapps Technologies** (Jul 2023 – Present), building reliable data platforms on Azure — and the AI systems that sit on top of them.

I work end-to-end: ingestion and modelling in Databricks, streaming and batch pipelines in production, and RAG / LLM applications grounded in that same data, with traceable sources. My focus now is where data engineering meets GenAI: **Unity Catalog, Delta Lake, vector search, and agentic workflows on one platform.**

**Currently focused on**

- Disaster recovery for Unity Catalog — metadata, data, and grants rebuilt idempotently in a DR workspace
- Grounded RAG over unstructured documents, with citations a reader can verify
- Production PySpark: performance, cost, and reliability, not just pipelines that run once

---

## Featured Work

| Project | What it does | Result / highlight |
|---|---|---|
| **[Unity Catalog DR Sync](https://github.com/sanjeevpandeydata/unity-catalog-dr-sync)** | Disaster recovery for Unity Catalog: two workflows, six notebooks that recreate credentials, external locations, catalogs, and schemas in a DR workspace, then sync data, volumes, and views, and apply grants. | Metadata skeleton first, then DEEP CLONE data and delta-only grants. CSV-driven, no hardcoded names or secrets. |
| **[Azure ETL Pipeline](https://github.com/sanjeevpandeydata/azure-etl-pipeline)** | Scalable ELT pipeline for CRM data, using Azure Data Factory + Databricks and Medallion architecture. | 50M+ records/month. Data availability **T+2 days → under 4 hours**, runtime **2 hours → 35 minutes**, ~40% compute cost reduction. |
| **[Event Hub Streaming Pipeline](https://github.com/sanjeevpandeydata/eventhub-streaming-pipeline)** | Real-time streaming ingestion on Databricks, consuming Avro messages from Azure Event Hubs with Structured Streaming and Auto Loader. | Dynamic schemas, JSON validation, ROW_NUMBER deduplication, and idempotent MERGE upserts for at-least-once delivery. |
| **[Delta Lake to MySQL Data Copy](https://github.com/sanjeevpandeydata/delta-to-mysql-datacopy)** | Copies a leads report table from Delta Lake to MySQL in full-reload and daily modes, replacing driver-side `collect()` + `executemany()` with distributed `mapInPandas` inserts and a JDBC anti-join for dedup. | Parallel inserts across executors with per-partition MySQL connections; serverless-compatible, with no driver bottleneck. |
| **[Spark Performance & Cost Optimisation](https://github.com/sanjeevpandeydata/spark-performance-optimization)** | Measured benchmark for Spark layout optimisation: partitioning, Z-ordering with `OPTIMIZE`, and broadcast joins on a synthetic sales dataset, with the same queries run unchanged against each layout. | Median of repeated runs, with files touched recorded; no result claimed until run on Databricks. |
| **News Knowledge Assistant** — *in progress* | A RAG assistant over daily newspaper PDFs on Databricks. Text is chunked with metadata (newspaper, date, page, article), embedded for vector search, and answered with Llama 3.1 — citing the exact source for every answer. | *Databricks · RAG · Llama 3.1 · Vector Search* — repository coming soon. |

---

## Tech Stack

<div align="center">

**Cloud & Data Platform**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Unity Catalog](https://img.shields.io/badge/Unity_Catalog-00ADD8?style=flat-square)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=flat-square)
![ADLS Gen2](https://img.shields.io/badge/ADLS_Gen2-0078D4?style=flat-square)
![Azure Data Factory](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure Event Hubs](https://img.shields.io/badge/Azure_Event_Hubs-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**Data Engineering**

![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Spark SQL](https://img.shields.io/badge/Spark_SQL-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**AI / GenAI**

![RAG](https://img.shields.io/badge/RAG-6C5CE7?style=flat-square)
![LLMs](https://img.shields.io/badge/LLMs-6C5CE7?style=flat-square)
![Agentic AI](https://img.shields.io/badge/Agentic_AI-6C5CE7?style=flat-square)
![Vector Databases](https://img.shields.io/badge/Vector_Databases-6C5CE7?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-6C5CE7?style=flat-square)

</div>

---

<div align="center">

### Let's connect

[![LinkedIn — Sanjeev Pandey](https://img.shields.io/badge/LinkedIn-Sanjeev_Pandey-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanjeev-pandey-7a45831ba)
[![GitHub — sanjeevpandeydata](https://img.shields.io/badge/GitHub-sanjeevpandeydata-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sanjeevpandeydata)

*Open to Data / AI Engineering roles in India — On-site · Hybrid · Remote — where data engineering meets GenAI.*

**B.Tech, Computer Science Engineering** · Oriental Group of Institutes, 2019–2023

</div>
