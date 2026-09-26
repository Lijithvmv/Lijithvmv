# Hi, I'm Lijith 👋

### AI/ML Engineer & Solution Architect — building secure, production AI · Bengaluru, India

I design, build, and ship **production AI systems end to end** — architecture and data modelling,
full-stack development, deployment, and operations — and I've done it at enterprise scale for the
last **~5 years**. I usually own a product across its whole lifecycle: problem statement →
architecture → backend and frontend → DevOps and deployment → reporting to senior leadership. On my
current work I *am* the delivery unit — product, architecture, engineering, and SRE for a portfolio
of AI products.

My range is the part I'd point to. I started in **applied ML and computer vision**, moved into
**production multi-agent GenAI platforms**, and now work where **AI engineering meets security and
governance** — so I can move from the model layer to the prompt layer to the business and compliance
layer in one conversation.

### What I do — end to end
- **Architect** enterprise AI: multi-agent orchestration (LangGraph), enterprise RAG / GraphRAG over knowledge graphs and vector stores, and the security & governance controls designed in from day one.
- **Build** full-stack: Python / FastAPI microservices, React / TypeScript SPAs, async workers (Celery), SQLAlchemy / Alembic, and the evaluation harnesses that prove a system works — not just demos.
- **Deploy & operate**: containerized on Kubernetes across Azure and GCP, with Terraform IaC, CI/CD, managed-identity secrets, and observability.
- **Secure & govern**: prompt-injection defense, guardrails, tool-call & egress policy, RBAC / non-human identity, agent evaluation & red-teaming, and GRC frameworks (ISO 27001 · PCI DSS · DPDP).

### Selected experience
- **Production multi-agent GenAI platform** — 30+ agents orchestrated in LangGraph with a runtime **plugin architecture** (agents and workflows loaded from configuration, not hardcoded), typed shared state with custom reducers, and parallel execution. Multi-tenant, with a JWT-driven security context and per-tenant data isolation enforced before retrieval.
- **Enterprise RAG at scale** — hybrid vector search (HNSW) over **100K+ records** with metadata tenant isolation and audit logging. Re-architected embedding generation from per-item to batched calls, cutting **P95 latency 36s → 2s and cost ~96%**.
- **Agentic GRC & security-automation platforms** — knowledge-graph controls, evidence pipelines, human-in-the-loop approval gates, and a hybrid **deterministic-agentic** design (*"AI writes the rules and the words; deterministic code computes the numbers"*) for a large enterprise security organization; sole architect and builder.
- **Enterprise-scale cloud infrastructure** — Terraform-driven virtual-desktop platform scaling from 2 to **300 VMs / 1,500 sessions**, golden-image pipelines, cross-subscription private networking, and RBAC / managed-identity hardening.
- **Applied ML & computer vision** (earlier) — CNN document-image classification across 200+ component types, **GAN-based multi-view 3D / CAD generation** (hackathon winner), and regression models predicting engineering test outcomes at ~92% accuracy.

### Open-source
| Project | What it is |
|---------|------------|
| **[GuardLayer](https://github.com/Lijithvmv/Guard-Layer)** | A production-grade security layer for LLM & agent apps — prompt-injection defense, tool-call & egress policy, session taint tracking, tamper-evident audit log. Zero-dependency core, hundreds of tests, an honest public benchmark. |
| **[Newton](https://github.com/Lijithvmv/newton)** | A fully local, offline coding agent that makes a small on-device model genuinely useful by planning work into verifiable steps and engineering its context. Took the same 7B model from 0/6 to 6/6 on cross-file tasks. |
| **[Sequel](https://github.com/Lijithvmv/Sequel)** | An agentic natural-language-to-SQL assistant with a dedicated validation stage — plain-English questions to correct, checked SQL. |

### Tech stack
- **AI & agents:** Python · LangGraph · LangChain · multi-agent orchestration · RAG / GraphRAG · knowledge graphs · agent evaluation
- **Models & AI security:** GPT-4 / 4o · Gemini / Vertex AI · local LLMs (Ollama) · prompt-injection defense · guardrails · red-teaming · RBAC / non-human identity
- **Backend & data:** FastAPI · SQLAlchemy / Alembic · Celery · PostgreSQL / pgvector · MySQL · Cosmos DB · Snowflake · Redis · vector DBs (Qdrant · FAISS · Chroma)
- **Cloud & infra:** Azure (Functions · Container Apps · Cosmos DB · Key Vault · Managed Identity · APIM · Log Analytics) · GCP (Vertex AI · Firestore) · Kubernetes · Docker · Terraform · CI/CD
- **Frontend:** React · TypeScript · Vite
- **ML:** PyTorch · TensorFlow · CNNs · GANs

### Certifications
- Microsoft Certified: **Azure AI Engineer Associate (AI-102)**
- Microsoft Certified: **Azure Administrator Associate (AZ-104)**
- **DeepLearning.AI** Machine Learning Specialization

### Connect
- LinkedIn: https://www.linkedin.com/in/lijith-v-m/
