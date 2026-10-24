# Hi, I'm Khang 👋

**AI / RAG Engineer** building 100% local question-answering systems that stay grounded in the source documents.

Ho Chi Minh City · Background in AI engineering (real-time & batch pipelines) · **Open to work**

## Currently building

**Graph RAG for Vietnamese legal documents** — combining vector search with a citation graph so answers cite the exact legal articles. (Neo4j · Chroma · Ollama)

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)

## Featured Projects

| Project | What it does | Stack |
|---|---|---|
| [**rag-chatbot-document-QA**](https://github.com/nguyenkhang-1902/rag-chatbot-document-QA) | 100% local RAG chatbot for document Q&A (.md / .docx / .pdf). Hybrid search + reranker, **97.7% Recall@4**, no paid API. | LangChain · Chroma · Ollama · FastAPI · Streamlit |
| [**recruitment-cdc-pipeline**](https://github.com/nguyenkhang-1902/recruitment-cdc-pipeline) | Real-time CDC pipeline (Kappa architecture) cutting data latency from 24h to **under 30s**. | Kafka · Spark Streaming · Cassandra · Airflow |
| [**graph-rag-legal-qa**](https://github.com/nguyenkhang-1902/graph-rag-legal-qa) | Graph RAG over a Vietnamese legal corpus: vector retrieval plus citation-graph traversal. | Neo4j · Chroma · Ollama |

## Professional Experience

**Assistant to the CEO — AI & Internal Systems** · HR-services company · Jul 2026 – present

Building and running internal web apps and data services for HR, payroll and operations teams. Projects are in their early rollout phase, so no usage metrics yet.

- **Multi-domain web platform:** designed a cluster architecture (per-site brand, shared page registry, dynamic routing) and used it to launch about 6 branded SEO/lead-gen sites, all live; wrote the clone SOP and handover docs.
- **Deployment & infrastructure:** configured and deployed a FastAPI/React customer-lifecycle platform to a self-managed Linux VPS (rootless Docker, self-hosted Postgres, shared Cloudflare Tunnel); also deployed web apps to Vercel with Neon Postgres.
- **Security & reliability for a data-sync service:** set the requirements and reviewed the implementation for encrypted secrets and phone numbers, masked national IDs, database-level deduplication, audit log, reconciliation reports and CI (about 14 PRs).
- **Authentication:** integrated Google Workspace SSO into internal apps following the company auth standard.
- **Integration:** connected content web apps to an internal work-desk app so incoming content becomes tasks and records.
- **Network & server administration:** configured and secured the company's VPS fleet (per-app Linux users, firewall isolation, Tailscale access rules, Cloudflare Tunnel) and troubleshot network failures such as tunnel errors, offline nodes and DNS loss, documenting the fixes in an incident runbook.
- **ERP platform support:** helped build the foundation of an ERP deployment (backup-restore drills, database credential rotation, production health-check scripts); features and mockups were owned by other team members.
- Work spec-first (specs, plans, task breakdowns) and direct AI coding agents (Claude Code), reviewing changes before merge.

## Most Used Languages

<img src="./profile/top-langs.svg" alt="Top languages" height="165" />

## Contact

- LinkedIn: [khangnguyen1902](https://www.linkedin.com/in/khangnguyen1902/)
- GitHub: [@nguyenkhang-1902](https://github.com/nguyenkhang-1902)
