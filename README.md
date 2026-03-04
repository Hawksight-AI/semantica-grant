# Semantica — FLOSS/fund Grant Application

Funding application for Semantica submitted to [FLOSS/fund](https://floss.fund) by Zerodha.

| Field | Details |
|---|---|
| **Project** | Semantica — Open-Source Semantic Layer & Context Graph Framework |
| **Repository** | https://github.com/Hawksight-AI/semantica |
| **License** | MIT |
| **Funding request** | $50,000 USD (one-time, 12-month grant) |
| **Maintainer** | Mohd Kaif — `kaifahmad087@gmail.com` |
| **Manifest** | [funding.json](./funding.json) |

## What is Semantica?

Semantica is a Python framework that provides the **semantic intelligence layer** that AI applications are missing. It transforms raw, unstructured data into governed, explainable, auditable knowledge — enabling trustworthy AI in high-stakes domains like healthcare, finance, legal, and cybersecurity.

It is not a wrapper around existing frameworks. It is the semantic layer that sits *beneath* your agents and makes their decisions traceable, their reasoning explainable, and their outputs auditable.

## Why this grant?

I left my job to work on Semantica full-time after seeing no credible open-source option for semantic reasoning infrastructure. Over the past year, working solo and self-funded, I shipped:

- **29 production-ready modules** covering ingestion, parsing, extraction, KG construction, GraphRAG, reasoning, provenance, and more
- **50+ Jupyter notebook tutorials** across 14 real-world domains
- **W3C PROV-O compliant provenance tracking** across 17 module integrations
- **Integrations** with FAISS, Neo4j, AWS Neptune, Apache AGE, Docling, and 100+ LLMs via LiteLLM

This $50,000 grant funds 12 months of development with a **small, distributed part-time team** rather than a single maintainer. The lead maintainer stipend is deliberately reduced to fund two part-time engineers, a technical writer, and an open bounty pool for community contributors. This is a conscious choice: more people, more resilience, faster progress.

## Budget at a glance

| Item | Amount |
|---|---|
| Lead maintainer stipend (12 months, full-time) | $26,000 |
| Part-time engineer #1 — KG algorithms & backend (~10 hrs/week) | $7,200 |
| Part-time engineer #2 — integrations & vector stores (~8 hrs/week) | $5,760 |
| Part-time technical writer & community manager (~6 hrs/week) | $3,600 |
| Open bounty pool (community PRs, bug fixes, cookbooks) | $2,440 |
| Infrastructure, CI/CD, cloud databases | $3,000 |
| API credits for integration tests (OpenAI, Groq, Anthropic) | $2,000 |
| **Total** | **$50,000** |

## Planned deliverables (12 months)

1. Stable **v1.0 release** with frozen public API and migration guides
2. Full **test coverage** (unit + integration) across all 29 modules
3. Published **performance benchmarks** — GraphRAG vs. plain RAG across 5 domains
4. Expanded integrations: Weaviate, Qdrant, ChromaDB, Pinecone; Anthropic and Gemini LLM providers
5. Healthcare and finance **compliance guides** (HIPAA, SOX) with working code examples
6. **10+ community-contributed cookbooks** via bounty programme
7. Active, self-sustaining **community**: Discord, GitHub Discussions, monthly release notes
