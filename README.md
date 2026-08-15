# Jonatas Ribeiro

**Technical Lead and Senior Full-Stack Software Engineer focused on applied AI, data-intensive systems, and self-hosted products.**

I combine hands-on engineering with technical leadership, working across system architecture, product delivery, team development, and engineering practices.

My experience includes TypeScript, React, Next.js, Go, Python, PostgreSQL, microservices, AWS, applied AI, and distributed systems.

## Leadership

I lead a senior full-stack engineering squad in a fast-moving product environment while remaining hands-on with architecture and delivery.

My leadership approach emphasizes:

- Clear ownership and engineering autonomy
- Async-first communication and documented decisions
- Iterative agile planning and sustainable delivery
- Continuous feedback and professional growth
- High standards for architecture, testing, and maintainability
- Creating the context for experienced engineers to make strong decisions independently

I see technical leadership as designing an environment where people, systems, and delivery practices can evolve together.

## Applied AI and agentic engineering

My current work and research include:

- LLM application and harness architecture
- Agent and tool-loop design
- AI-assisted, specification-driven development with Claude Code, Cortex Code, and Codex
- LangGraph, Deep Agents, MCP, and application-owned runtime contracts
- RAG, embeddings, local inference, and LLM evaluation
- Model adaptation and fine-tuning experiments
- Human approval, observability, and safety boundaries for agentic systems
- Data analysis and reproducible machine-learning experimentation

I use AI coding agents as part of a structured engineering process: requirements, architecture, specifications, implementation, automated verification, review, and documented trade-offs.

## Master's research

I am completing my Master's thesis and expect to defend it next semester.

The research evaluates whether clinical notes provide trustworthy predictive signal for mortality and length of stay beyond structured biological measurements in MIMIC-III.

The work combines Python data pipelines, clinical NLP, embeddings, RAG and LLM experiments, classical machine learning, temporal validation, leakage controls, ablation studies, and reproducible Docker-based execution.

The experimental pipeline runs within my homelab, keeping protected data and model execution under local control.

## Selected projects

> The source repositories are private. These summaries describe their architecture and engineering decisions without exposing proprietary code, protected data, or private infrastructure details.

### Personal LLM Harness

An experimental Python harness for studying reliable agent runtimes, tool use, and local models.

It compares a direct model/tool loop, LangGraph, and Deep Agents behind common application-owned contracts. The architecture explores durable execution, typed events, provider portability, tool policies, human approval, idempotency, replay, observability, and local Ollama inference.

`Python · LangGraph · Deep Agents · Ollama · MCP · Agent loops`

### Clinical Decision Support

A leakage-aware clinical AI research pipeline comparing clinical notes, structured measurements, combined feature families, and controlled baselines for mortality and length-of-stay prediction.

`Python · MIMIC-III · Machine learning · RAG · LLM evaluation · Docker · Data analysis`

### ClubCore SaaS

A self-hosted, multi-tenant platform for managing sports clubs, members, events, attendance, and documents.

It combines a Go modular monolith, Next.js, PostgreSQL Row-Level Security, centralized RBAC/ABAC authorization, audit events, Docker-based delivery, and a private Linux operations stack.

`Go · Next.js · PostgreSQL · RLS · RBAC/ABAC · Docker · Self-hosting`

### Garmin Watch Faces

Local-first Garmin Connect IQ watch faces supporting multiple MIP and AMOLED devices.

The architecture separates platform APIs, device capabilities, metrics, display models, layouts, themes, and rendering while respecting battery, privacy, permission, and constrained-device requirements.

`Monkey C · Connect IQ · Embedded systems · Local-first architecture`

### Mesada

A self-hosted household task-planning, allowance, and settlement platform moving from product and architecture definition toward implementation.

Its design uses explicit business boundaries, a Go modular monolith, React, PostgreSQL, Auth0, Docker, and a private Linux deployment environment. Microservices are deliberately deferred until independent scaling, availability, or ownership requirements justify their operational cost.

`Go · React · PostgreSQL · Auth0 · Docker · Product architecture`

## Self-hosted infrastructure

I operate a private Linux homelab for application hosting, AI research, local inference, and infrastructure experimentation.

The environment includes:

- Multiple open-source LLMs hosted through Ollama
- Open WebUI and GPU-accelerated local inference
- Docker-based service isolation and Portainer operations
- Tailscale private networking and remote access
- Nginx reverse-proxy and routing responsibilities
- PostgreSQL and supporting application services
- Private deployment of my Master's research pipeline

I use the homelab as an operational learning environment for privacy-aware AI, self-hosted applications, infrastructure hardening, model comparison, and deployment automation.

## Core experience

- Technical leadership and engineering management
- Full-stack product engineering
- Applied AI and data-intensive systems
- Agent runtime and loop architecture
- Go and Python backend development
- React, Next.js, and TypeScript
- Microservices, AWS, and cloud-native delivery
- PostgreSQL, data modeling, and multi-tenant security
- Linux, containers, and self-hosted infrastructure

## Contact

[LinkedIn](https://www.linkedin.com/in/jonatas-ribeiro/) ·
[ORCID](https://orcid.org/0009-0009-6287-2289) ·
[Email](mailto:jonatas@prottaribeiro.com)

Outside engineering: surfing, rugby, and motorcycles.
