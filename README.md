# Achraf Gasmi — AI · ML · MLOps Engineer

**3 years in production.** KYC/AML compliance systems, fraud detection, multi-agent LLM pipelines — built and shipped in regulated financial environments.

---

## What I build

- **ML systems end-to-end** — data pipelines → model training → inference APIs → monitoring → drift detection
- **LLM & agent engineering** — LangGraph multi-agent workflows, RAG pipelines, self-correcting agentic loops
- **ML platform layer** — A/B testing, shadow deployment, experiment tracking, Terraform IaC, CI/CD
- **Compliance AI** — AML screening, KYC risk scoring, SHAP-explainable predictions, regulatory reporting automation

**Domain:** KYC · AML · FATF · Insurance · Fintech · GDPR  
**Stack:** Python · PyTorch · LangGraph · FastAPI · Docker · Kubernetes · MLflow · Terraform · Airflow · AWS

---

## Selected projects

### [Neural Fraud Detector](https://github.com/achraf-gasmi/neural-fraud-detector)
FT-Transformer + anomaly head for real-time transaction fraud detection.  
**AUPRC 0.9676 · AUROC 0.9947 · F1 0.9439 · <15ms inference latency**  
Full MLOps: MLflow · FastAPI · Docker · GitHub Actions CI/CD · Streamlit dashboard

### [Picnic ML Platform](https://github.com/achraf-gasmi/picnic-ml-platform)
Production-grade ML platform: recommendation, fraud detection, demand forecasting, ticket classification.  
Platform layer: deterministic A/B testing (SHA256) · KS + PSI drift detection · automated retraining triggers  
Infrastructure: FastAPI · Docker Compose · MLflow · Terraform on AWS (EC2 + S3)

### [Waraka — STR Drafting Agent](https://github.com/achraf-gasmi/waraka)
LangGraph agent that takes plain French descriptions of suspicious transactions and produces goAML-compatible STR XML for CTAF submission — under BCT circular n°2025-17.  
Stack: Claude Sonnet · OpenSanctions · FastAPI · PostgreSQL · Redis · ChromaDB · 38/38 tests passing

### [AML Detection Model](https://github.com/achraf-gasmi/aml-detection)
Ensemble AML scoring system calibrated on the Tunisian BCT/CTAF regulatory framework.  
49 features · 10 FATF typologies · XGBoost + LightGBM ensemble · SHAP explanations (auditability requirement)  
Feeds the Waraka STR drafting pipeline upstream.

### [AI Document Intelligence Agent](https://github.com/achraf-gasmi/ai-document-intelligence-agent)
LangGraph multi-agent pipeline: parallel analysis agents (asyncio) + self-correcting improvement loop (Critique → Improve → Adversarial Verifier, score ≥ 85).  
~60% faster than sequential · SQLite checkpointing · React/Vite frontend · FastAPI

### [Insurance RAG System](https://github.com/achraf-gasmi/insurance-rag-system)
RAG API for insurance policy Q&A: multi-stage retrieval, category-aware intent detection, hybrid reranking.  
Qdrant · Ollama · FastAPI

---

## Production impact (BH Assurance)

| System | Result |
|---|---|
| AML entity matching + risk scoring | ~30% reduction in false-positive compliance flags |
| ETL pipelines over 100K+ client records | ~40% reduction in manual compliance work |
| OCR model for document ingestion | ~60% reduction in manual data entry |
| RPA automation bots | ~20% operational capacity recovered |

---

## Stack

**AI / LLMs:** Python · PyTorch · LangGraph · LangChain · RAG · GraphRAG · Hugging Face · OpenAI · Groq  
**ML / MLOps:** scikit-learn · XGBoost · LightGBM · MLflow · GitHub Actions · pytest · NLP · OCR · SHAP  
**Platform / Infra:** Docker · Kubernetes · Terraform · Apache Airflow · FastAPI · A/B Testing · Drift Detection  
**Vector DBs:** Pinecone · ChromaDB · Qdrant · pgvector  
**Data / Backend:** PostgreSQL · MySQL · MongoDB · Flask · Spring Boot · REST APIs  
**Domain:** KYC · AML · FATF · Financial Risk · Insurance · GDPR  
**Languages:** French C2 · English C2 · German A1 (active)

---

## Stats

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs?username=achraf-gasmi&layout=compact&hide_border=true)
![GitHub Streak](https://streak-stats.demolab.com?user=achraf-gasmi&hide_border=true)

---

[LinkedIn](https://www.linkedin.com/in/achraf-gasmi-592766134/) · [Kaggle](https://www.kaggle.com/gasminix) · achrafgasmi58@gmail.com  
**Open to relocation — Netherlands · Germany · France · Belgium · Switzerland · Luxembourg**
