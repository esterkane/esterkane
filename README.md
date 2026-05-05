# Sanja Ruzic

Elasticsearch-focused Support Engineer with nearly 5 years at Elastic and 12+ years in technical support and application engineering.

I work at the intersection of Elasticsearch search systems, production diagnostics, indexing and data modelling, relevance evaluation, observability, and AI-assisted knowledge workflows.

Most of the projects below are active work in progress. I use them as practical labs for testing search ideas, shaping diagnostics, comparing relevance strategies, and turning support and engineering experience into reproducible workflows.

## Current focus areas

- Elasticsearch search, mappings, indexing, ingest pipelines, and production diagnostics
- Product search relevance, BM25, hybrid retrieval, semantic search, vectors, reranking, and RAG
- Relevance evaluation with judgment lists, Precision@k, MRR, nDCG, and latency benchmarks
- Search quality gates, explainable query behavior, and evidence-based troubleshooting
- Python, TypeScript, Node.js, Docker, Elasticsearch

## Featured projects

### [kcs-control-plane](https://github.com/esterkane/kcs-control-plane)

Version 3 of my duplicate-detection work for knowledge base articles. This is the current, more operational evolution of the earlier prototype line: it turns the ideas from version 2 into a local control plane with ingestion, resumable embedding backfills, chunking, checkpointed duplicate materialization, a live review UI, and optional remote analysis publishing.

What it demonstrates:

- duplicate analysis as a resumable operational pipeline, not just a one-off experiment
- local-first workflows with optional shared remote analysis snapshots
- hybrid search, embeddings, chunk evidence, duplicate edges, and duplicate clusters in one system
- reviewable duplicate families with evidence and editorial decisions in a browser UI

### [elastic-product-search-lab](https://github.com/esterkane/elastic-product-search-lab)

E-commerce product search relevance lab with Elasticsearch mappings, deterministic ingestion, `search_profile` enrichment, BM25 strategy comparison, ESCI-based relevance metrics, latency benchmarks, and local search quality gates.

What it demonstrates:

- product search relevance is measured, not guessed
- ingestion quality affects search quality
- ranking changes are compared with Precision@5, MRR@10, nDCG@10, and p95 latency
- search quality gates can catch relevance or latency regressions

### [elastic-search-policy-control-plane](https://github.com/esterkane/elastic-search-policy-control-plane)

TypeScript/Node.js search governance prototype that turns raw e-commerce queries into deterministic Elasticsearch execution plans with filters, boosts, exclusions, strategy routing, and explainable policy traces.

What it demonstrates:

- governed search behavior through policy data
- explainable query rewriting and boosting
- deterministic conflict handling
- safer handling of exclusions such as allergens, blocked categories, or business constraints

### [elastic-repo-inventory](https://github.com/esterkane/elastic-repo-inventory)

Release-intelligence and retrieval app for Elasticsearch technical content, with provenance-aware indexing, hybrid retrieval, metadata filters, evidence snippets, and version-aware search workflows.

What it demonstrates:

- provenance-first retrieval
- hybrid ranking
- metadata-aware search
- evidence-based technical research workflows

### [elastic-ai-search-decision-lab](https://github.com/esterkane/elastic-ai-search-decision-lab)

Small Elasticsearch/TypeScript lab that turns AI search documentation drafts into an indexed decision system and evaluates findability with practitioner questions, judgment sets, MRR, nDCG, and Precision@k.

What it demonstrates:

- documentation can be tested as a retrieval surface
- AI search concepts can be organized into decision-oriented workflows
- practitioner questions, judgment sets, and ranking metrics make findability measurable

## Additional pinned projects

### [duplicate_detection_project-v2-jinaai](https://github.com/esterkane/duplicate_detection_project-v2-jinaai)

Version 2 of this duplicate-detection line of work: a Streamlit workflow for knowledge base articles using Jina AI embeddings, Elasticsearch hybrid search, reranking, HDBSCAN clustering, and a Docker-based local setup. It was the prototype stage that proved out the retrieval, reranking, and clustering ideas before they were expanded into `kcs-control-plane` as version 3.

### [elasticsearch-resilience-quiz](https://github.com/esterkane/elasticsearch-resilience-quiz)

Interactive Google Colab quiz covering Elasticsearch, Kafka, Kubernetes, gRPC, Node.js, and resilience concepts.

## How I work

- I prefer evidence over guessing.
- I focus on reproducible diagnostics, measurable improvements, and clear communication.
- I enjoy bridging support, engineering, documentation, search relevance, and product thinking.
