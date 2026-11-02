# Achraf Gasmi · AI Engineer

**3+ years building AI and ML systems in production for a regulated insurer.** LLM agents, KYC/AML compliance, fraud and risk scoring, and the MLOps layer that keeps them reliable.

Only ML/AI engineer in my department at BH Assurance (BH Bank Group, Tunis): I take systems from the business need to production and own them after launch.

---

## In production

| System | What it does |
|---|---|
| **LLM tender agent** | Finds public insurance tenders, extracts them from PDF, scores them against products and past offers, drafts complete offers for the top five. Human validation before any submission. Self-hosted models, per-run tracking of model calls and latency. Used daily by 3 teams after 2 months of testing with them on real cases. |
| **KYC risk-scoring model** | Gradient-boosting model deployed next to the existing rules engine behind an administrator switch, so compliance compared model and rules on live cases before switching over. |
| **KYC screening platform** | Filtering, batch screening and risk-scoring modules (team of 3): customer base matched against six watchlists (PEP, sanctions, national lists) under configurable rules. |
| **Portfolio monitoring platform** | FastAPI on a SQL Server star schema, CI/CD with migration checks, Trivy and SBOM, 130 tests. Server-side recalculation exposed a combined ratio of **94,56 %** where the old dashboard showed **88,14 %**. |
| **OCR model** | Custom model in the customer mobile app, reading ID cards, vehicle registration documents and business registry extracts. |

---

## Selected projects

### [Waraka · STR drafting agent](https://github.com/achraf-gasmi/waraka)
LangGraph agent that turns plain-French descriptions of suspicious activity into goAML-compatible STR XML for the Tunisian financial intelligence unit (CTAF). Banking and insurance. Decisions come from explicit rule registries (6 banking rules, 29 insurance indicators); the LLM only writes the narrative.
Claude Sonnet · OpenSanctions · FastAPI · PostgreSQL · Redis · ChromaDB · typed Pydantic state · 54 tests

### [Neural Fraud Detector](https://github.com/achraf-gasmi/neural-fraud-detector)
FT-Transformer for transaction fraud detection, chosen after evaluating a graph neural network approach (HeteroGAT).
**AUPRC 0,9676 · AUROC 0,9947 · F1 0,9439** on [dataset name]
MLflow · Hydra · FastAPI · Docker · GitHub Actions CI/CD · Streamlit monitoring dashboard

### [AML Detection Model](https://github.com/achraf-gasmi/aml_detection_ML)
Ensemble AML scoring built around Tunisian CTAF typologies.
49 features · 10 typologies · XGBoost + LightGBM + Isolation Forest · SHAP explanations for auditability

### [MLOps Platform](https://github.com/achraf-gasmi/mlops-platform)
Four model types behind one FastAPI service: recommendation (XGBoost), ticket classification, anomaly detection (Isolation Forest) and time-series forecasting (Prophet).
Deterministic A/B routing · Kolmogorov-Smirnov + PSI drift detection · MLflow · Docker Compose · Terraform on AWS (EC2, S3, IAM)

### [AI Document Intelligence Agent](https://github.com/achraf-gasmi/ai-document-intelligence-agent)
Six-agent LangGraph pipeline: parallel analysis agents (asyncio) and a self-correcting loop (critique → improve → adversarial verifier, capped at three rounds). SQLite checkpointing so interrupted runs resume.
FastAPI · React/Vite

### [Insurance RAG System](https://github.com/achraf-gasmi/insurance-rag-system)
RAG API for insurance policy Q&A: multi-stage retrieval, category-aware intent routing, re-ranking, answers returned with their sources.
Qdrant · Ollama · FastAPI

---

## Stack

**LLMs & agents:** LangGraph · LangChain · RAG · tool calling · structured outputs (Pydantic) · LLM-as-judge evaluation · Ollama · Claude · Hugging Face
**ML:** PyTorch · scikit-learn · XGBoost · LightGBM · SHAP · anomaly detection · OCR · Prophet
**MLOps & infra:** MLflow · Airflow · Docker · Kubernetes · Terraform · AWS · GitHub Actions · pytest · drift detection
**Back end & data:** Python · TypeScript · FastAPI · Flask · Node.js · PostgreSQL · SQL Server · MongoDB · Redis
**Vector DBs:** Qdrant · ChromaDB
**Domain:** KYC · AML · FATF · goAML · insurance · GDPR · EU AI Act
**Daily tools:** Claude Code

**Languages:** Arabic (native) · French C2 · English C2 · German A1 (learning)

---

[LinkedIn](https://www.linkedin.com/in/achraf-gasmi-592766134/) · [Kaggle](https://www.kaggle.com/gasminix) · achrafgasmi58@gmail.com

**Based in Tunis (UTC+1) · Open to relocation or remote**
