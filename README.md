# Hi, I'm Wale 👋  
Backend-Focused Software Engineer | Java & Spring Boot | Secure & Real-Time Systems

🔗 LinkedIn: https://www.linkedin.com/in/waally-7707xyz  
📺 YouTube: https://www.youtube.com/@tgc-707  

---

## 👨🏽‍💻 About Me

I'm a Computer Science student at the University of New Brunswick focused on building secure, production-oriented backend systems.

I enjoy designing RESTful APIs, enforcing authentication and authorization flows, and thinking through edge cases in distributed systems. My work centers around reliability, clean architecture, and real-time service design.

I'm particularly interested in backend infrastructure, secure transaction systems, and cloud-native architectures. I also actively maintain and open-source the software I build.

---

## 🚀 Selected Projects

### LazyDrop — Real-Time File Sharing Platform (Open Source)  
**Live:** [lazydrop.app](https://lazydrop.app) · **Source:** [GitHub](https://github.com/10xDeVv/LazyDrop)  
Java 21 · Spring Boot 4 · PostgreSQL · WebSockets (STOMP) · Supabase Auth · Stripe · DigitalOcean Spaces CDN · Docker

- Architected a modular monolith backend for session-based, real-time file sharing across any device.
- Implemented two-phase file uploads via S3 pre-signed URLs — the backend never handles file bytes.
- Built CDN-backed download delivery by configuring dual S3 presigners (origin for writes, CDN edge for reads).
- Designed idempotent Stripe webhook processing backed by a persistent event log with deduplication and retry tracking.
- Enforced subscription plan limits server-side (file size, session count, participants) — cannot be bypassed via API.
- Implemented hybrid identity resolution supporting both JWT-authenticated users and cookie-based guest sessions.
- Set up CI/CD with GitHub Actions: automated tests, Docker builds, and code quality scans on every push.
- Optimized container memory footprint from 50% to 30% through JVM tuning, connection pool sizing, and dependency cleanup.
- Wrote comprehensive documentation: system design diagrams, data model ERDs, scaling roadmap, and security model.
- Containerized the full stack with Docker Compose for one-command local development.

Focus areas: signed URL uploads, CDN delivery, webhook idempotency, real-time events, plan enforcement, CI/CD.

---

### KingdomTrack — Role-Based Assignment Platform  
Spring Boot · PostgreSQL · JWT (Access/Refresh Tokens) · Docker

- Developed secure REST APIs supporting 100+ users.
- Implemented access/refresh token authentication with role separation.
- Structured backend using controller → service → repository layering.
- Designed permission-aware endpoints with defensive validation.

Focus areas: secure session handling, backend modularization, API design.

---

## 🛠 Technical Focus

### Backend & Architecture
- Java 21 (Spring Boot 4)
- RESTful API Design
- Modular Monolith Architecture
- Role-Based Access Control
- WebSockets (STOMP)
- S3 Pre-Signed URL Workflows
- Database Migrations (Flyway)

### Security & Reliability
- JWT & OAuth2 Resource Server Validation
- Hybrid Auth (JWT + Guest Cookie Sessions)
- Idempotent Webhook Processing
- Server-Side Plan Enforcement
- Structured Exception Handling
- Defensive Input Validation

### Testing & Quality
- JUnit 5 (Service + Controller Tests)
- Mockito (Mocking Dependencies)
- TestContainers (Integration Tests)
- MockMvc (Controller Layer Testing)
- CI-Based Automated Test Execution

### DevOps & Infrastructure
- Docker & Docker Compose
- GitHub Actions (CI/CD)
- DigitalOcean Spaces CDN (S3-Compatible)
- PostgreSQL (Indexing, Normalization)
- JVM Performance Tuning
- Environment-Based Configuration

---

## 🧠 Engineering Interests

- Secure-by-design backend systems  
- Real-time communication patterns  
- Object storage and CDN architectures  
- Financial & transaction-based system reliability  
- Observability & structured logging  
- Open-source project maintenance  

---

## 🎯 Current Direction

Actively deepening my expertise in backend engineering, cloud infrastructure, and secure transaction systems.

Currently maintaining [LazyDrop](https://github.com/10xDeVv/LazyDrop) as an open-source project — iterating on the architecture, growing the contributor base, and shipping improvements in the open.

Long-term goal: build and operate high-trust, high-availability backend platforms at scale.

---

📫 Contact: adebowale.ca@gmail.com
