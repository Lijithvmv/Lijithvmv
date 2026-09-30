<p align="center">
  <img src="assets/banner.svg" alt="Lijith V M — AI/ML Security Engineer & Solution Architect" width="100%">
</p>

# Hi, I'm Lijith 👋

### AI/ML Security Engineer & Solution Architect · Bengaluru, India

> **Forward-deployed engineer** — I take AI products from problem statement to production and own them there end to end: architecture, full-stack build, deployment, and operations — under real enterprise security, approval-gate, and scale constraints.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lijith-v-m/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Lijithvmv)

For **4+ years** I've shipped **production AI at enterprise scale** — usually as the whole delivery
unit: product and architecture, backend and frontend, DevOps and deployment, and reporting to senior
leadership. My work sits where **AI engineering meets security and governance**, so I design the
controls in from day one rather than bolt them on, and I ship through real approval gates instead of
stopping at a demo. When something has to go from *idea* to *live, monitored system*, I'm the person
who carries it the whole way.

My range is the part I'd point to. I started in **applied ML and computer vision**, moved into
**production multi-agent GenAI platforms**, and now build **secure agentic systems and GRC
automation** — so I can move from the model layer to the prompt layer to the business and compliance
layer in one conversation.

🎓 DeepLearning.AI Machine Learning Specialization · Microsoft Azure AI Engineer (AI-102), certified 2024

### 🧭 What I do — end to end
- **Architect** enterprise AI: multi-agent orchestration (LangGraph), enterprise RAG / GraphRAG over knowledge graphs and vector stores, and the security & governance controls designed in from day one.
- **Build** full-stack: Python / FastAPI microservices, React / TypeScript SPAs, async workers (Celery), SQLAlchemy / Alembic, and the evaluation harnesses that prove a system works — not just demos.
- **Deploy & operate**: containerized on Kubernetes across Azure and GCP, with Terraform IaC, CI/CD, managed-identity secrets, and observability.
- **Secure & govern**: prompt-injection defense, guardrails, tool-call & egress policy, RBAC / non-human identity, agent evaluation & red-teaming, and GRC frameworks (ISO 27001 · PCI DSS · DPDP).

### 💼 Selected experience
- **Production multi-agent GenAI platform** — 30+ agents orchestrated in LangGraph with a runtime **plugin architecture** (agents and workflows loaded from configuration, not hardcoded), typed shared state with custom reducers, and parallel execution. Multi-tenant, with a JWT-driven security context and per-tenant data isolation enforced before retrieval.
- **Enterprise RAG at scale** — hybrid vector search (HNSW) over **100K+ records** with metadata tenant isolation and audit logging. Re-architected embedding generation from per-item to batched calls, cutting **P95 latency 36s → 2s and cost ~96%**.
- **Agentic GRC & security-automation platforms** — knowledge-graph controls, evidence pipelines, human-in-the-loop approval gates, and a hybrid **deterministic-agentic** design (*"AI writes the rules and the words; deterministic code computes the numbers"*) for a large enterprise security organization; sole architect and builder.
- **Enterprise-scale cloud infrastructure** — Terraform-driven virtual-desktop platform with golden-image pipelines and a planned scale-out path to **300 VMs / 1,500 sessions**, cross-subscription private networking, and RBAC / managed-identity hardening.
- **Applied ML & computer vision** (earlier) — CNN document-image classification across 200+ component types, **GAN-based multi-view 3D / CAD generation** (hackathon winner), and regression models predicting engineering test outcomes at ~92% accuracy.

### 🚀 Open-source
| Project | What it is |
|---------|------------|
| **[SOC-Graph-Guard](https://github.com/Lijithvmv/SOC-Graph-Guard)** | A security-first agentic SOC on LangGraph: verdicts computed from evidence (never from attacker-written text), graded autonomy, human approval before irreversible actions, injection screening and a tamper-evident audit. On labelled attack scenarios: guarded graph 7/7 with zero unsafe actions vs a naive agent's 2/7. |
| **[GuardLayer](https://github.com/Lijithvmv/Guard-Layer)** | A production-grade security layer for LLM & agent apps — prompt-injection defense, tool-call & egress policy, session taint tracking, tamper-evident audit log. Zero-dependency core, hundreds of tests, an honest public benchmark. |
| **[Newton](https://github.com/Lijithvmv/newton)** | A fully local, offline coding agent that makes a small on-device model genuinely useful by planning work into verifiable steps and engineering its context. Took the same 7B model from 0/6 to 6/6 on cross-file tasks. |
| **[Sequel](https://github.com/Lijithvmv/Sequel)** | An agentic natural-language-to-SQL assistant with a dedicated validation stage — plain-English questions to correct, checked SQL. |

### 🧰 Tech stack

**AI & agents**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Multi-agent](https://img.shields.io/badge/Multi--agent%20orchestration-2B2B2B?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG%20%2F%20GraphRAG-2B2B2B?style=for-the-badge)
![Knowledge Graphs](https://img.shields.io/badge/Knowledge%20Graphs-2B2B2B?style=for-the-badge)
![Agent Evaluation](https://img.shields.io/badge/Agent%20Evaluation-2B2B2B?style=for-the-badge)

**Models & AI security**

![OpenAI](https://img.shields.io/badge/GPT--4%20%2F%204o-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20%2F%20Vertex%20AI-886FBF?style=for-the-badge&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Prompt Injection Defense](https://img.shields.io/badge/Prompt--Injection%20Defense-C3002F?style=for-the-badge)
![Guardrails](https://img.shields.io/badge/Guardrails-C3002F?style=for-the-badge)
![Red Teaming](https://img.shields.io/badge/Red--Teaming-C3002F?style=for-the-badge)
![RBAC / NHI](https://img.shields.io/badge/RBAC%20%2F%20NHI-C3002F?style=for-the-badge)

**Backend & data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2F%20pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant%20%2F%20FAISS%20%2F%20Chroma-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)

**Cloud & infra**

![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![CNNs](https://img.shields.io/badge/CNNs-2B2B2B?style=for-the-badge)
![GANs](https://img.shields.io/badge/GANs-2B2B2B?style=for-the-badge)

### 📊 GitHub

[![Lijith's GitHub stats](https://github-readme-stats.vercel.app/api?username=Lijithvmv&show_icons=true&hide_border=true&count_private=true)](https://github.com/Lijithvmv)
[![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Lijithvmv&layout=compact&hide_border=true&langs_count=8)](https://github.com/Lijithvmv)
