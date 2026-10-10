# Senior Backend Engineer and System Architect

Hands-on engineer focused on backend systems, distributed architecture, cloud infrastructure, and production AI/RAG applications.

バックエンド開発とシステム設計を中心に、大規模トラフィック、分散処理、クラウド、AI・RAGサービスの設計・開発・公開・運用まで一貫して取り組んでいます。英語を使用するグローバルチームにも対応可能です。

**Explore my work:** [XSocial — Go architecture and social platform](https://github.com/aspirit/xsocial) · [AskNews — bilingual AI/RAG application](https://github.com/aspirit/asknews)

## Professional strengths

- Approximately 20 years of experience in backend development, system architecture, and production operations
- Former CTO and hands-on technical lead with experience in architecture, technology selection, implementation, troubleshooting, and engineering support
- Five years of remote collaboration with a U.S.-based team, using English for technical discussions, documentation, requirements clarification, and code reviews
- Experience building and operating high-traffic, high-concurrency, distributed systems
- End-to-end product delivery covering requirements, architecture, backend, frontend, data pipelines, testing, deployment, and ongoing operations

## Selected experience

- Led the architecture and backend development of an online service that grew to more than **60 million registered users**, **10 million monthly active users**, and **2 million daily active users**, with peaks of approximately **10 billion API requests per day**
- Contributed to sports information systems for a major internet platform serving more than **100 million users per day** during the 2008 Olympics
- Worked in both large cross-functional development organizations and international remote teams
- Independently designed, developed, tested, deployed, and operated an AI/RAG information retrieval service
- Delivered its initial production version in approximately four months and reduced generation costs by approximately **46%** through caching and model selection

## Featured projects

### XSocial — Go backend architecture showcase

A social platform with a live demo and a public, runnable architectural core extracted from the full backend. The repository demonstrates a complete post → like → asynchronous notification flow; the live application includes the broader product.

- **Service architecture:** a Go monorepo with separate API and worker services, shared models and tooling, interface-based boundaries, and compile-time dependency injection
- **Concurrency and consistency:** idempotent writes and event handling, MongoDB transactions, versioned compare-and-set reconciliation, and tests for concurrent requests and failure scenarios
- **Scale-out design:** stateless APIs, shared Redis caching and rate limiting, Kafka / Google Cloud Pub/Sub abstractions, and a runnable multi-instance development setup
- **Engineering practices:** automated architecture checks, linting, code generation with drift checks, real-database integration tests, CI, and OpenTelemetry observability
- **Long-term ownership:** documented design decisions and trade-offs, repeatable development workflows, and service boundaries designed for product evolution and maintainability

The design grew from ideas I began exploring about five years ago and lessons from earlier projects, refined through repeated implementation and testing.

[Live demo](https://xsocial.dev/) · [Project overview](https://xsocial.dev/about) · [Architecture code](https://github.com/aspirit/xsocial) · [Engineering decisions](https://github.com/aspirit/xsocial/blob/main/docs/ENGINEERING.md)

### AskNews

A bilingual RAG application for exploring official central-bank communications in English and Japanese.

- Hybrid keyword and vector retrieval over a large document archive
- Source-cited answers with links to original documents
- Timestamped transcript references that open videos at the relevant moment
- Out-of-domain refusal, retrieval evaluation, verified-answer caching, rate limiting, and LLM budget controls
- Automated data ingestion and production deployment

[Live application](https://asknews.jp/) · [Source code](https://github.com/aspirit/asknews)


## Core technologies

### Languages and runtimes

Python · Go · PHP · Node.js · TypeScript · JavaScript

### Databases, search and messaging

PostgreSQL · MySQL · MongoDB · Redis · Kafka · pgvector · Full-text search · Vector search

### Cloud and systems

AWS · GCP · Linux · Docker · Git

### Engineering

Backend APIs · Distributed systems · Asynchronous processing · Caching · Database partitioning · Performance optimization · CI/CD · Production operations

### Applied AI

LLM integration · RAG · Hybrid retrieval · OCR · Speech recognition · Source-grounded generation · AI-assisted development

