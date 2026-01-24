# Jair Villalobos | Backend Engineer

Backend Engineer specialized in Go and Distributed Systems. I focus on system reliability, concurrency patterns, and infrastructure optimization.

[LinkedIn](https://linkedin.com/in/jjvnz) | [GitHub](https://github.com/jjvnz) | [Email](mailto:jjvnz.dev@gmail.com)

---

## 🏗️ Technical Competencies

- **Languages:** Go (up to 1.25), Python, TypeScript.
- **Infrastructure:** GKE (Google Kubernetes Engine), AWS, Docker, Terraform.
- **Data:** PostgreSQL (Tuning & ACID), Redis, SQL Server (Star Schema).
- **Core:** Concurrency (Goroutines/Channels), Resource Management (cgroups/GOMAXPROCS), ETL Pipelines.

---

## 🚀 Key Performance Metrics

| Metric | Result | Context |
| :--- | :--- | :--- |
| **Database Latency** | **-35%** | Query optimization and indexing strategy in PostgreSQL. |
| **Throughput** | **1M+ Records** | High-concurrency ETL ingestion in Go 1.25. |
| **Efficiency** | **Native** | Container-aware runtime tuning (GOMAXPROCS). |

---

## 🛠️ Engineering Projects

### 🏗️ [CarnicosGoETL](https://github.com/jjvnz/CarnicosGoETL)
**Problem:** High latency in manual reporting and inefficient data ingestion for large datasets.
**Solution:** Built a concurrent ETL pipeline in **Go** for Azure SQL DW.
- Implemented worker pools to manage 1M+ records.
- Designed star schema models to support BI workloads.
- **Stack:** Go, SQL Server, Docker.

### ⚙️ [Votos (Private)](https://github.com/jjvnz)
**Problem:** Data race conditions and integrity risks in high-concurrency financial tracking.
**Solution:** Management system using **Go and PostgreSQL** with strict ACID compliance.
- Applied Mutex-based synchronization for real-time data aggregation.
- Implemented partial payment logic with transactional safety.
- **Stack:** Go, PostgreSQL, Redis.

### 🤖 [Student PQRS Classifier](https://github.com/jjvnz/student-complaints-classifier)
**Problem:** High operational cost in manual classification of student complaints.
**Solution:** REST API integrating a **DistilBERT (NLP)** model for automated categorization.
- Reduced classification time from hours to milliseconds.
- **Stack:** Python, FastAPI, HuggingFace Transformers.

---

## 📑 Work Methodology

1. **System Design:** Architecture first (Cloud-Native, Decoupled).
2. **Reliability:** Strict adherence to ACID and concurrency safety.
3. **Observability:** Monitoring throughput, memory leaks, and latencies.
4. **Performance:** Runtime-level tuning (Go 1.25, Memory layout).
