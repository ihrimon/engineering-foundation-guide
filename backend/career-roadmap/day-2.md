# Career in Backend — A Life Long Roadmap

**By HM Nayem** — Author & Educator, Founder & CTO at Stack Learner, Technical Screener & Full-stack Developer at Toptal

⬅ [Roadmap index](README.md) · Previous: [Day 1 — Big Picture of Backend](day-1.md) · Next: [Day 3 — Journey to Become an Architect](day-3.md)

## Day 2 — Problem with Backend

### Congratulations, we are a backend developer

Recap of the Day 1 flow: **Client → DNS lookup → Web Server → Application/Business Logic → Database → Response**.

Building a single-server setup like this is easy... **but things get complicated over time.**

### Why?

- **We own the server**, and a server has limitations: a fixed amount of processing power, RAM, and storage.
- **Thousands of requests at the same time** means:
  - Our server gets really busy.
  - Users experience slow responses.
  - The system runs out of resources and shuts down.
  - The business loses customers.

Think of it like a single room: it can comfortably hold a few people, but not thousands crammed into the same space.

- Previously, the **client machine** was responsible for computation (packaged software).
- Now, **our server** is responsible for everything — and that responsibility doesn't scale by itself.

**We want to serve 1M users.** Now we need engineering.

---

## Three Interrelated Phases

We run into problems across three phases — and they depend on each other; a change in one impacts the others.

| Phase | Focus |
|---|---|
| **Development** | Writing the application itself |
| **Deployment** | Getting the application running reliably |
| **Distribution** | Making the application reachable, resilient, and trustworthy at scale |

---

## Development Phase

**How to develop an application?** Naively: pick a language, pick a framework, and code. **Actually, not that simple.**

### Application Architecture

- Monolithic
- N-Tier
- Modular Monolith
- Microservice
- Event Driven
- Cloud Native
- Serverless

### High Performant Code

- Data Structures
- Algorithms
- Design Patterns
- Design Principles
- Schema Optimization
- Query Optimization
- Scalable code
- Testing

---

## Deployment Phase

### Cloud Computing

Core building blocks: AI & Machine Learning, Security, Storage, Databases and Data Centres, Networking, Containers, Virtual Machines, Compute.

Simplified view — all deployed within a **VPC** (Virtual Private Cloud):

- Compute / VM
- Storage
- Database
- Networking

### Development + Deployment = DevOps

Development + Deployment (Operations) together form **DevOps** — a continuous infinity loop:

**Dev side:** Plan → Code → Build → Test
**Ops side:** Release → Deploy → Operate → Monitor

Supporting practices at each stage: Source Code & Version Control, Infrastructure as Code, Provisioning, Configuration Management, Virtualization, Containerization, Quality Control, CI/CD, Visualizations, Logging.

### General (Manual) Process

- Write code
- Test the code locally
- Push to GitHub
- Pull the code on the server
- Build the code
- Deploy the code
- Monitor

### DevOps (Automated) Process

- Write code
- Push to GitHub
- Test automatically on the integration server
- Build the code and generate an artifact on the integration server
- Deploy the artifact automatically to the server
- Monitor

This is a **continuous process** for every change.

### Common DevOps Toolchain

| Stage | Tools |
|---|---|
| Code | Git, GitLab |
| Build | Gradle, Sonatype Nexus |
| Test | Azure, OpenStack, Jenkins |
| Deploy | AWS, Docker |
| Operate | Chef, Ansible, Kubernetes |
| Monitor | Grafana, Graylog |

---

## Distribution Phase

**Distribution decides everything.**

**What do users want? Reliability!**

### Non-Functional Requirements

- Performance
- Scalability
- Reliability
- Security

All of this falls under **System Design**, which encompasses:

- System Architecture
- Data
- Interfaces
- Modules
- Components
- Performance
- Reliability
- Scalability
- Maintainability
- Security

### Common System Design Concepts

- Application Architectures
- Computer Networking
- OSI (Open Systems Interconnection) Model
- Synchronous / Asynchronous communication between services
- Server scaling, clustering and load balancing
- Caching and CDN
- Scaling databases
- Fault tolerance, failures and disaster recovery

### A Real-World Reference Stack (ByteByteGo)

`Client App` → **Cloudflare** (edge) / **Nginx** (reverse proxy) → Load balancer / service registry (**Zookeeper**, **Netflix Eureka**, **Spring Boot**) → a cluster of services backed by:

- **Kafka** (messaging)
- **Elasticsearch** (search)
- **Redis / Memcached** (caching)
- **AWS / Google Cloud** (infrastructure)
- **RPC** via **Thrift** / **gRPC**
- **Management & Monitoring**: Prometheus, Kubernetes, Elastic

...ultimately persisting to **Cassandra**, **Amazon S3**, **MySQL**, **PostgreSQL**.

---

## Backend Boundary

Backend spans:

- **Development**
- **Deployment**
- **Distribution**
- **DevOps**

Backend is full of theory and a lot of fancy words that seem really hard to understand. However, backend is easy, challenging, and exciting.

---

⬅ [Roadmap index](README.md) · Previous: [Day 1 — Big Picture of Backend](day-1.md) · Next: [Day 3 — Journey to Become an Architect](day-3.md)
