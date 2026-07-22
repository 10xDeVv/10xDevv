# Hi, I'm Wale 👋
Backend-Focused Software Engineer | Java & Spring Boot | Secure, Real-Time, and Data-Driven Systems

🔗 LinkedIn: https://www.linkedin.com/in/waally-7707xyz  
📺 YouTube: https://www.youtube.com/@tgc-707

---

## 👨🏽‍💻 About Me

I'm a Computer Science student at the University of New Brunswick focused on building production-grade backend systems that are secure, reliable, and observable.

I enjoy designing APIs, enforcing authentication and authorization flows, and translating product ideas into software that can scale in the real world.

Lately, I've been shipping across multiple products: real-time infrastructure, privacy-first AI workflows, and developer-facing web experiences.

---

## 🚀 Projects

### LazyDrop — Real-Time File Sharing Platform (Open Source)
**Live:** [lazydrop.app](https://lazydrop.app) · **Source:** [GitHub](https://github.com/10xDeVv/LazyDrop)

Java 21 · Spring Boot · PostgreSQL · WebSockets · Stripe · Docker · GitHub Actions

- Architected a modular monolith backend for session-based, real-time file sharing.
- Implemented signed URL upload/download workflows with CDN-backed delivery.
- Built idempotent payment webhook handling with deduplication and retry-safe processing.
- Enforced plan limits server-side so constraints cannot be bypassed via API clients.

---

## 🆕 Recent Work

### Wayward — Scenic Route Generation Platform
**Source:** [GitHub](https://github.com/10xDeVv/Wayward)

Next.js · Java/Spring Boot · Kafka · PostgreSQL/PostGIS · Redis · OSRM · Docker Compose

- Built a revisioned route-job pipeline that supports async processing, primary-result delivery, and resilient status updates.
- Combined spatial scoring (H3 + PostGIS) with route engine outputs to rank scenic driving loops by vibe and drive quality.
- Structured the system into focused services (`route-api`, `route-worker`, `notification-service`) with production deployment discipline.

### WhereDidIApply — Privacy-First AI Job Tracker
**Live:** [wheredidiapply.tech](https://wheredidiapply.tech) · **Source:** [GitHub](https://github.com/10xDeVv/WhereDidIApply)

Next.js 15 · React 19 · Java 21/Spring Boot WebFlux · Gemini · Docker · Cloud Run

- Built a hybrid rules engine + LLM pipeline to classify job-application emails into interview, rejection, offer, and action-required states.
- Designed around strict privacy guarantees: Gmail tokens stay client-side and server-side processing is stateless/in-memory.
- Added reliability controls (rate limits, quotas, circuit breaker) for predictable behavior under API uncertainty.

### Portfolio — Personal Engineering Portfolio
**Source:** [GitHub](https://github.com/10xDeVv/Portfolio)

Vanilla JS (ES Modules) · Custom build scripts · CSS system design · Vercel deploy

- Rebuilt portfolio UX as a lightweight static web app focused on performance and clear project storytelling.
- Structured content and component layers to keep iteration fast while preserving visual consistency.
- Used a minimal toolchain to optimize for maintainability and deployment simplicity.

---

## 🛠 Technical Focus

### Backend & Platform Engineering
- Java 21 (Spring Boot)
- RESTful API design
- Async workflows and event-driven processing
- Modular architecture and service boundaries
- WebSockets and real-time delivery

### Security & Reliability
- JWT/OAuth2 patterns
- Role-based access control
- Idempotent processing and defensive validation
- Rate limiting, quotas, and circuit breakers
- Operationally safe deploy/rollback workflows

### Data & Infrastructure
- PostgreSQL + PostGIS
- Redis caching strategies
- Containerized environments (Docker / Compose)
- CI/CD with GitHub Actions
- Environment-based configuration and observability practices

---

## 🎯 Current Direction

I'm currently focused on advancing backend system design through three parallel tracks:

- **Real-time and geospatial infrastructure** (Wayward)
- **Privacy-first AI product engineering** (WhereDidIApply)
- **Clear technical storytelling and developer branding** (Portfolio)

In parallel, I continue maintaining and evolving [LazyDrop](https://github.com/10xDeVv/LazyDrop) as an open-source backend platform.

Long-term goal: build and operate high-trust, high-availability systems that solve practical problems at scale.

---

📫 Contact: adebowale.ca@gmail.com
