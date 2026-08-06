# Backend Guide

> Deep-dive checklist for backend engineering — architecture, APIs, auth, data, scaling, and security concepts every backend/full-stack engineer should own.

⬅ [Back to main guide](../README.md) · Related: [Frontend Guide](../frontend/README.md) · [DevOps / Infrastructure Guide](../devops/README.md)

## 📍 Start Here: The Career Roadmap

New to backend, or want the big picture before diving into the checklist below? Start with the **[3-Day Career in Backend Roadmap](career-roadmap/README.md)** — a guided narrative covering the big picture of backend, why it gets hard at scale, and how to grow from junior developer to architect.

## How to read this checklist

- `[x]` — studied / have hands-on working understanding
- `[ ]` — not yet covered
- Each topic has a **Deep Dive** list (the core sub-concepts) and a second list — **Production Knowledge**, **Interview-Level**, or similar — for the harder "why does this matter in production" questions.

## Progress Snapshot

| # | Topic | Core Items |
|---|---|---|
| 1 | Microservices Architecture | 0/5 |
| 2 | Serverless Computing | 0/4 |
| 3 | GraphQL vs REST | 0/4 |
| 4 | OAuth2 & OpenID Connect | 0/4 |
| 5 | JWT Token Management | 0/4 |
| 6 | SQL Injection Prevention | 0/3 |
| 7 | CSRF Tokens | 0/3 |
| 8 | Scaling Systems | 0/4 |
| 9 | Load Balancing | 0/4 |
| 10 | Database Sharding | 0/4 |
| 11 | Caching Layers | 0/4 |
| 12 | Message Queues | 0/4 |
| 13 | Data Encryption | 0/4 |
| 14 | Zero-Trust Security | 0/3 |
| 15 | Security Testing | 0/3 |
| 16 | AI-Driven Chatbots | 0/4 |
| 17 | Web Scraping & Automation | 0/4 |

**Total: 0/65 core items covered**

---

## Topics

### 👉 1. Microservices Architecture

#### Deep Dive

- [ ] Service discovery
- [ ] API Gateway
- [ ] Distributed tracing
- [ ] Service mesh
- [ ] Saga pattern

#### Production Problems

- [ ] Distributed failures
- [ ] Network latency
- [ ] Data consistency

---

### 👉 2. Serverless Computing

#### Deep Dive

- [ ] Cold starts
- [ ] Function concurrency
- [ ] Stateless execution
- [ ] Edge functions

#### Engineering Knowledge

- [ ] Cost optimization
- [ ] Vendor lock-in

---

### 👉 3. GraphQL vs REST

#### Deep Dive

- [ ] Over-fetching vs under-fetching
- [ ] N+1 queries
- [ ] DataLoader
- [ ] Persisted queries

#### Production Knowledge

- [ ] GraphQL security risks
- [ ] Query complexity limits

---

### 👉 4. OAuth2 & OpenID Connect

#### Deep Dive

- [ ] Authorization code flow
- [ ] PKCE
- [ ] Refresh token rotation
- [ ] Identity federation

#### Interview-Level

- [ ] Difference between AuthN vs AuthZ

---

### 👉 5. JWT Token Management

#### Deep Dive

- [ ] Token expiration
- [ ] Refresh token architecture
- [ ] Token revocation
- [ ] JWT attacks

#### Production Knowledge

- [ ] Stateless auth tradeoffs

---

### 👉 6. SQL Injection Prevention

#### Deep Dive

- [ ] Parameterized queries
- [ ] ORM injection risks
- [ ] Blind SQL injection

#### Real Engineering

- [ ] Query validation

---

### 👉 7. CSRF Tokens

#### Deep Dive

- [ ] Double-submit cookies
- [ ] SameSite strategies
- [ ] CSRF in SPAs

---

### 👉 8. Scaling Systems

#### Deep Dive

- [ ] Stateless architecture
- [ ] Sticky sessions
- [ ] Distributed cache
- [ ] Scaling bottlenecks

#### Interview Focus

- [ ] Scale from 1k → 1m users

---

### 👉 9. Load Balancing

#### Deep Dive

- [ ] Round robin
- [ ] Least connections
- [ ] Health checks
- [ ] Layer 4 vs Layer 7

---

### 👉 10. Database Sharding

#### Deep Dive

- [ ] Shard key selection
- [ ] Cross-shard queries
- [ ] Rebalancing
- [ ] Hot partitions

---

### 👉 11. Caching Layers

#### Deep Dive

- [ ] Cache stampede
- [ ] Cache warming
- [ ] Redis eviction policies
- [ ] CDN edge caching

---

### 👉 12. Message Queues

#### Deep Dive

- [ ] At-most-once delivery
- [ ] At-least-once delivery
- [ ] Exactly-once semantics
- [ ] Idempotency

---

### 👉 13. Data Encryption

#### Deep Dive

- [ ] Symmetric vs asymmetric encryption
- [ ] Key rotation
- [ ] Encryption at rest
- [ ] Encryption in transit

---

### 👉 14. Zero-Trust Security

#### Deep Dive

- [ ] Identity verification
- [ ] Principle of least privilege
- [ ] Service authentication

---

### 👉 15. Security Testing

#### Deep Dive

- [ ] Threat modeling
- [ ] Dependency scanning
- [ ] Penetration testing basics

---

### 👉 16. AI-Driven Chatbots

#### Deep Dive

- [ ] Context windows
- [ ] Vector search
- [ ] RAG pipelines
- [ ] Prompt injection attacks

---

### 👉 17. Web Scraping & Automation

#### Deep Dive

- [ ] Headless browsers
- [ ] Anti-bot detection
- [ ] Rate limiting avoidance
- [ ] Browser fingerprinting

---

⬅ [Back to main guide](../README.md) · 📍 [Career Roadmap](career-roadmap/README.md)
