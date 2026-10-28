# Hi, I'm Sanjeev Pandey 👋

**Data Engineer → AI Engineer | Building intelligent data platforms on Azure**

I build reliable data pipelines and, increasingly, the AI systems that sit on top of them — RAG, LLM applications, and agentic workflows — using Azure Databricks as the common platform.

📍 India · 💼 Data Engineer, Multiapps Technologies (Jul 2023 – Present)

---

### What I do

- **Data engineering at scale:** ETL/ELT pipelines with PySpark, SQL, and Python on Azure — ADF for orchestration, ADLS Gen2 for storage, Delta Lake for reliable tables
- **Streaming:** Real-time ingestion with Azure Event Hubs, Spark Structured Streaming, and Auto Loader, with MERGE-based deduplication for at-least-once delivery
- **AI on data:** RAG pipelines with Databricks, vector search, and Llama 3.1 — grounded answers with traceable source citations, not just generated text
- **Modelling & optimisation:** Medallion architecture (Bronze → Silver → Gold), Spark optimisation, and data modelling for reporting-ready Gold layers

---

### Tech Stack

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=flat&logo=delta&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Azure Data Factory](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Azure Event Hubs](https://img.shields.io/badge/Azure_Event_Hubs-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6C5CE7?style=flat)
![LLMs](https://img.shields.io/badge/LLMs-6C5CE7?style=flat)
![Agentic AI](https://img.shields.io/badge/Agentic_AI-6C5CE7?style=flat)
![Vector Databases](https://img.shields.io/badge/Vector_Databases-6C5CE7?style=flat)

---

### Featured Projects

#### 🔹 Azure ETL Pipeline
Scalable ELT pipeline for 50M+ CRM records per month, using ADF + Databricks and Medallion architecture.
**Result:** Data availability from T+2 days to under 4 hours, pipeline runtime from 2 hours to 35 minutes, ~40% compute cost reduction.

→ [sanjeevpandeydata/azure-etl-pipeline](https://github.com/sanjeevpandeydata/azure-etl-pipeline)

#### 🔹 Event Hub Streaming Pipeline
Real-time streaming ingestion on Databricks, consuming Avro messages from Azure Event Hubs with Structured Streaming and Auto Loader.
**Highlights:** Dynamic schema loading, JSON validation, ROW_NUMBER deduplication, and idempotent MERGE upserts into Delta Lake.

→ [sanjeevpandeydata/eventhub-streaming-pipeline](https://github.com/sanjeevpandeydata/eventhub-streaming-pipeline)

#### 🔹 News Knowledge Assistant — *currently building*
A RAG assistant over daily newspaper PDFs on Databricks. It extracts and chunks text with metadata (newspaper, date, page, article), generates embeddings for vector search, retrieves the most relevant chunks for a question, and answers with Llama 3.1 — citing the exact newspaper, date, page, and article so every answer can be verified.

---

### GitHub Stats

![Sanjeev's GitHub stats](https://github-readme-stats.vercel.app/api?username=sanjeevpandeydata&show_icons=true&theme=default)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sanjeevpandeydata&layout=compact&theme=default)

---

### Connect with me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sanjeev_Pandey-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanjeev-pandey-7a45831ba)

Open to roles in India — On-site · Hybrid · Remote — where data engineering meets GenAI.
