# Hi, I'm Wale 👋

**Backend & Platform Engineer** building secure, event-driven, and data-intensive systems with Java, Go, Rust, and TypeScript.

[LinkedIn](https://www.linkedin.com/in/waally-7707xyz) · [YouTube](https://www.youtube.com/@tgc-707) · [Email](mailto:adebowale.ca@gmail.com)

## About me

I'm a Computer Science student at the University of New Brunswick, Co-Founder & Engineering Lead at Hack Atlantic, and Software Developer, Database Systems at Steel Plus Network.

I like working where correctness matters: authorization boundaries, transactional workflows, asynchronous processing, geospatial data, failure recovery, and release engineering. My current work spans a Go/PostgreSQL event-operations platform, financial data systems, scenic routing infrastructure, and deterministic traffic modeling.

## Current work

### Hack Atlantic — Application & Event Operations Platform

Next.js · TypeScript · Go · PostgreSQL · Terraform · Docker

- Leading engineering on a platform that carries participants from versioned applications and private reviews through decisions, secure QR passes, and event-day checkpoint redemptions.
- Implemented concurrency-safe checkpoint redemption with PostgreSQL row locks and idempotency keys; the team-built release path adds staged validation, immutable artifacts, observability, and backup/restore controls.

### Steel Plus Network — Internal Financial Data Systems

SQL · Microsoft Access · VBA

- Returned after a 2025 internship to build a larger rebate-management system with normalized supplier, member, contract, purchase, and exchange-rate data.
- Translating undocumented business rules into auditable internal workflows while keeping unresolved financial assumptions explicit.

## Selected engineering projects

### [Breakpoint](https://github.com/10xDeVv/Breakpoint) — Multi-City Road-Disruption Modeling

Rust · Python · React · TypeScript · Mapbox GL · deck.gl

- Built a five-city modeled beta with a deterministic Rust traffic-assignment engine, reproducible city packages, and an interactive road-disruption analysis UI.
- Added validation for schema and graph invariants, solver convergence, and flow conservation, plus a containerized Azure deployment path with metrics, alerts, backup/restore, infrastructure as code, and OIDC-based CI/CD.

### [Wayward](https://github.com/10xDeVv/Wayward) — Scenic Route Generation

Next.js · Java/Spring Boot · Kafka · PostgreSQL/PostGIS · Redis · H3 · OSRM

- Built an asynchronous route pipeline with transactional outbox dispatch, Kafka retries, lease-fenced workers, revisioned job states, and WebSocket progress with polling fallback.
- Reduced a 1,500-tile real-Redis lookup benchmark from 3,213 ms to 90 ms using batched `MGET`, bulk PostGIS miss queries, pipelined cache fills, and a local LRU.

### [LazyDrop](https://github.com/10xDeVv/LazyDrop) — Real-Time File Sharing

**Live:** [lazydrop.app](https://lazydrop.app)

Next.js · Java/Spring Boot · PostgreSQL · WebSockets · S3-Compatible Storage · Stripe

- Implemented two-phase signed uploads so object storage handles file bytes while the API retains authorization, validation, and metadata control.
- Prevented duplicate Stripe entitlement updates with signature validation, server-side plan enforcement, and an idempotent leased-retry ledger.

### [WhereDidIApply](https://github.com/10xDeVv/WhereDidIApply) — Privacy-First Job Tracking

**Live:** [wheredidiapply.tech](https://wheredidiapply.tech)

Next.js · TypeScript · Java/Spring Boot · Gmail API · Gemini · Cloud Run

- Kept Gmail OAuth tokens client-side and avoided server-side email persistence while using deterministic parsing before bounded Gemini fallback.
- Added configured quotas, concurrency limits, retries, and circuit breaking around email scanning and classification.

## Toolbox

- **Languages:** Java, Go, Rust, TypeScript, Python, SQL
- **Backend:** Spring Boot, REST APIs, WebSockets, Kafka
- **Data:** PostgreSQL, PostGIS, Redis, H3
- **Infrastructure:** Docker, Terraform, GitHub Actions, observability, backup and rollback workflows
- **Frontend:** Next.js, React, React Native, Mapbox GL, deck.gl

## What I'm exploring next

- Reliable distributed workflows and transaction design
- Geospatial and data-intensive systems
- Systems performance, validation, and observability
- Deployment paths that are measurable, reversible, and boring in the best way

📫 **Contact:** [adebowale.ca@gmail.com](mailto:adebowale.ca@gmail.com)
