# Rodney Tigges — Senior Site Reliability Engineer
**Observability · Predictive Analytics · AI/ML Infrastructure**

20+ years in SRE, infrastructure, and large-scale healthcare systems. I move monitoring from reactive to anticipatory, and I'm applying that discipline to the reliability of AI/LLM systems. I care about *why* systems fail, not just how to fix them.

🟢 **Open to fully remote (US) roles:** Senior/Staff SRE · AI Platform / MLOps · reliability-focused Forward Deployed Engineering

## 📈 Track Record
- **99.99% uptime** across 130+ applications and 1.5M accounts (IBM Security Access Manager migration)
- **300+ monthly S.M.A.R.T. recommendations** from a generative-AI workflow at America's largest hospital system
- **Multi-tier synthetic monitoring strategy** now standard across that system
- **35% fewer incidents** via a predictive-analytics remediation platform; **60% faster deployments** via Ansible automation

---

## 🔧 What I Work On
- **Reliability & Observability** — SLIs/SLOs, error budgets, incident response, Golden Signals; Dynatrace, AppDynamics, Splunk, open-source stacks
- **AI/ML Infrastructure** — RAG (hybrid retrieval, reranking), LangChain/LangGraph agents, Qdrant, Ollama, MCP, LLM evaluation & observability, quantization/right-sizing
- **Platforms & Automation** — AWS, Kubernetes, Docker, Ansible, Terraform
- **Languages** — Python (PyTorch primary), PostgreSQL; past R, C++, Ruby
- **Workflow** — daily AI-assisted development (Cursor, Claude Code)

---

## 📌 Featured Projects

### [verses-rag](https://github.com/assimilatereality/RAG)
**A RAG pipeline that checks its own work before answering.**
Hybrid retrieval over the KJV Bible and a theological article corpus: dense (BGE-large-en-v1.5) + BM25 with RRF fusion in Qdrant, then cross-encoder reranking. A LangGraph state machine grades retrieved documents, reformulates failed queries, and verifies answer faithfulness before returning. FastAPI/SSE backend, Streamlit UI, full evaluation harness. Local generation via Ollama; OpenAI/Anthropic for judgment-critical steps.
*Stack:* Python · LangGraph · Qdrant · Ollama · FastAPI · Streamlit
*Why it matters for SRE:* retrieval quality gates, faithfulness checks, and evaluation as guardrails for LLM systems in production.

### [qdrant-quantization-benchmark](https://github.com/assimilatereality/qdrant-quantization-benchmark)
**Right-sizing vector search: what quantization really costs.**
Benchmarks scalar, binary, and product quantization in Qdrant for latency, accuracy retention, and memory. Written for SRE/DevOps engineers sizing AI infrastructure.
*Stack:* Python · Qdrantcross scalar, binary, and product quantization. Built for SRE/DevOps engineers right-sizing AI infrastructure and optimizing RAG pipelines.

---

## ✍️ Writing

Systems thinking, resilience engineering, and AI in operations at [assimilatereality.github.io](https://assimilatereality.github.io/).

Recent posts:
- [We've Been Here Before: AI, Calculators, and the Shifting Floor of "Real" Skills](https://assimilatereality.github.io/ai/software%20development/2026/03/05/shifting-floor-of-skills.html)
- [The Failure Points We Build Into Our Systems](https://assimilatereality.github.io/engineering-practices/system-reliability/2026/02/01/failure-points-prevention.html)
- [Building Organizations That Learn from Chaos](https://assimilatereality.github.io/resilience/devops/reliability/systems-thinking/2025/12/20/learn-from-chaos.html)

---

## 📫 Connect

- 💼 [LinkedIn](https://linkedin.com/in/rodneytigges)
- 📧 AssimilateReality@gmail.com
