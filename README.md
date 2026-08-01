![AI Portfolio](ChatGPT%20Image%20Feb%2022,%202026,%2001_25_08%20PM.png)
# Aditya Girish

AI/ML engineer. Retrieval systems, unsupervised methods, and production ML.
B.Tech Computer Science, PES University · Bengaluru, India

[LinkedIn](https://www.linkedin.com/in/adityagirishh) · [adityadeepa634@gmail.com](mailto:adityadeepa634@gmail.com)

---

## Research

**When Does Structure Help? Graph vs. Tabular Models for Agent-Workflow Cost Prediction**
*Under review — AAAI 2027, main technical track · Solo author*

Establishes when graph neural networks beat tabular models for agent-workflow cost prediction. Across 357K real coding-agent rounds, graph models lose when execution costs do not propagate through workflow structure.

**MSTRAE: Multi-Scale Temporal Recurrent Autoencoder for Flight Manoeuvre Recognition**
*Accepted — FTC 2026, Berlin · Springer LNNS · Lead author*

Zero-shot manoeuvre recognition on Cessna 172 telemetry using a multi-scale LSTM autoencoder in PyTorch, HMM-based unsupervised clustering, and an LLM-based evaluation framework in place of hand-labelled ground truth.

---

## Selected work

### [QRAG](https://github.com/adityagirishh/Quantized-RAG) — quantized bi-level retrieval

Dual-level quantization across coarse and fine retrieval tiers, built for memory-constrained deployment.

- **95.1% recall@10** on FIQA at a **3–4× memory reduction**
- Beats **FAISS IVF-PQ by 21.5pp in recall** at comparable memory budgets, benchmarked across 57,000 documents

### [OriginScale](https://github.com/adityagirishh/OriginScale-a-novel-initialisation) — deterministic clustering initialization

Replaces data-dependent sampling in the standard initialization path with a deterministic scheme.

- Constant **26ms** initialization against a **~3.5s** average, on datasets up to 200K entries
- Applied to real-time food-delivery dispatch: **1.68× lower latency**, no loss in assignment quality

### FinFusion — multimodal financial forecasting

LSTM time-series forecasting fused with real-time news sentiment, evaluated using stability metrics that weight tail-risk behaviour during regime shifts and volatility spikes.

---

## Experience

**TruEstate** — AI/ML Engineer *(Jul 2026 – present)* · SWE Intern, AI *(Jan – Jul 2026)*

Voice-AI stack specification and per-lead context curation for an outbound calling pipeline. Previously: an agent-based CMS on GCP that cut broker site-build time from **2 hours to 5 minutes** and lifted lead quality **60%**; consolidated a three-agent support system into a single classification-routed agent.

**Viable Ideas** — AI Backend Engineer Intern *(Apr – May 2025)*

LLM-based inventory prediction on transaction data from 4 bank sources, deployed at **85% classification accuracy**. Automated multi-source ingestion cut manual workflows **70%**.

---

## Stack

| | |
|---|---|
| **Languages & ML** | Python, PyTorch, scikit-learn, SQL |
| **Cloud & infra** | GCP (Vertex AI, Cloud Run, BigQuery, Pub/Sub), Docker, Kubernetes, Terraform |
| **Data** | Kafka, Redis, MySQL |
| **LLM tooling** | LangChain, RAG, embedding quantization |

---

Open to research collaborations and ML engineering roles in retrieval and algorithmic systems work.
