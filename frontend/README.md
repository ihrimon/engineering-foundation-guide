# Frontend Guide

> Deep-dive checklist for modern frontend engineering — performance, rendering internals, security, browser APIs, and the concepts that separate "uses React" from "understands the browser."

⬅ [Back to main guide](../README.md) · Related: [Backend Guide](../backend/README.md) · [DevOps / Infrastructure Guide](../devops/README.md)

## How to read this checklist

- `[x]` — studied / have hands-on working understanding
- `[ ]` — not yet covered
- Each topic has a **Deep Dive** list (the core sub-concepts) and a second list — **Interview-Level**, **Production Knowledge**, or similar — for the harder "why does this matter in the real world" questions.

## Progress Snapshot

| # | Topic | Core Items |
|---|---|---|
| 1 | Service Workers & Cache Strategies | 2/10 |
| 2 | HTTP/2 & HTTP/3 | 8/8 ✅ |
| 3 | Content Security Policy (CSP) | 0/6 |
| 4 | Rate Limiting & Throttling | 2/6 |
| 5 | Code Splitting & Lazy Loading | 0/6 |
| 6 | Tree Shaking | 0/5 |
| 7 | Core Web Vitals | 3/5 |
| 8 | Progressive Enhancement | 0/4 |
| 9 | WebAssembly (WASM) | 0/5 |
| 10 | Advanced CSS Grid & Flexbox | 0/5 |
| 11 | CSS Houdini | 0/4 |
| 12 | Closures & Currying | 0/4 |
| 13 | Memoization & useMemo | 0/4 |
| 14 | Generators & Async Iterators | 0/4 |
| 15 | Proxy & Reflect API | 0/4 |
| 16 | WebRTC | 0/5 |
| 17 | Server-Sent Events (SSE) | 0/4 |
| 18 | JavaScript Event Loop & Async | 1/4 |
| 19 | Frontend Security | 0/5 |
| 20 | Performance Optimization | 0/5 |
| 21 | Accessibility Auditing | 0/4 |
| 22 | SEO Technical Optimization | 0/5 |
| 23 | Internationalization (i18n) | 0/4 |

**Total: 16/116 core items covered (~14%)**

---

## Topics

### 👉 1. Service Workers & Cache Strategies

#### Deep Dive

- [x] Cache First vs Network First
- [x] Stale While Revalidate
- [ ] Background Sync
- [ ] Offline-first architecture
- [ ] Cache invalidation problems
- [ ] Runtime caching
- [ ] Pre-caching
- [ ] Service Worker lifecycle
- [ ] Push notifications
- [ ] IndexedDB sync patterns

#### Interview-Level Understanding

- [ ] Difference between HTTP cache and SW cache
- [ ] Why cache invalidation is hard
- [ ] Race conditions in caching
- [ ] Offline consistency problems

---

### 👉 2. HTTP/2 & HTTP/3

#### Deep Dive

- [x] Head-of-line blocking
- [x] Multiplexing
- [x] Binary framing
- [x] HPACK compression
- [x] QUIC protocol
- [x] TLS handshake optimization
- [x] Connection reuse
- [x] Streaming responses

#### Engineering Focus

- [ ] Why HTTP/3 is faster on unstable networks
- [ ] CDN optimization
- [ ] Browser connection limits
- [ ] Keep-alive tuning

---

### 👉 3. Content Security Policy (CSP)

#### Deep Dive

- [ ] nonce vs hash strategy
- [ ] strict-dynamic
- [ ] unsafe-inline risks
- [ ] XSS mitigation patterns
- [ ] CSP reporting
- [ ] Third-party script isolation

#### Production Knowledge

- [ ] How CSP breaks analytics scripts
- [ ] Real-world CSP rollout strategy
- [ ] CSP debugging in browsers

---

### 👉 4. Rate Limiting & Throttling

#### Deep Dive

- [ ] Token bucket algorithm
- [ ] Leaky bucket
- [x] Sliding window
- [x] Fixed window
- [ ] Distributed rate limiting
- [ ] Redis-based rate limiting

#### Interview-Level

- [ ] Difference between debounce vs throttle
- [ ] API abuse protection
- [ ] DDoS mitigation basics

---

### 👉 5. Code Splitting & Lazy Loading

#### Deep Dive

- [ ] Dynamic imports
- [ ] Route-based splitting
- [ ] Component-level splitting
- [ ] Hydration cost
- [ ] Suspense boundaries
- [ ] Waterfall loading problems

#### Production Knowledge

- [ ] Bundle analysis
- [ ] Chunk optimization
- [ ] Over-splitting problems
- [ ] Predictive prefetching

---

### 👉 6. Tree Shaking

#### Deep Dive

- [ ] ES Modules static analysis
- [ ] sideEffects flag
- [ ] Dead code elimination
- [ ] CommonJS limitations
- [ ] Bundle graph analysis

#### Real Engineering

- [ ] Why tree shaking sometimes fails
- [ ] Library design for tree shaking

---

### 👉 7. Core Web Vitals

#### Deep Dive

- [x] LCP optimization
- [x] CLS debugging
- [x] INP vs FID
- [ ] Render-blocking resources
- [ ] Critical rendering path

#### Production Engineering

- [ ] Real User Monitoring (RUM)
- [ ] Synthetic testing
- [ ] Lighthouse limitations

---

### 👉 8. Progressive Enhancement

#### Deep Dive

- [ ] Server-first rendering
- [ ] Resilient UI patterns
- [ ] Graceful degradation
- [ ] No-JS architecture

#### Real-World

- [ ] Why over-JS apps fail
- [ ] Accessibility benefits

---

### 👉 9. WebAssembly (WASM)

#### Deep Dive

- [ ] JS ↔ WASM bridge
- [ ] Memory model
- [ ] Rust/WASM integration
- [ ] WASM threading
- [ ] SIMD

#### Use Cases

- [ ] Video editing
- [ ] Image processing
- [ ] Game engines
- [ ] AI inference in browser

---

### 👉 10. Advanced CSS Grid & Flexbox

#### Deep Dive

- [ ] Subgrid
- [ ] Intrinsic sizing
- [ ] Container queries
- [ ] Layout thrashing
- [ ] Rendering performance

#### Engineering Knowledge

- [ ] Why layouts break
- [ ] Responsive system architecture

---

### 👉 11. CSS Houdini

#### Deep Dive

- [ ] Paint API
- [ ] Layout API
- [ ] Typed OM
- [ ] Worklets

#### Engineering Insight

- [ ] Browser rendering extensibility
- [ ] Custom rendering systems

---

### 👉 12. Closures & Currying

#### Deep Dive

- [ ] Closure memory leaks
- [ ] Scope chain internals
- [ ] Partial application
- [ ] Functional composition

#### Interview Focus

- [ ] Closures in async systems
- [ ] Real-world closure bugs

---

### 👉 13. Memoization & useMemo

#### Deep Dive

- [ ] Referential equality
- [ ] React reconciliation cost
- [ ] Memoization tradeoffs
- [ ] Cache eviction

#### Engineering Insight

- [ ] When memoization hurts performance
- [ ] useMemo misuse

---

### 👉 14. Generators & Async Iterators

#### Deep Dive

- [ ] Lazy evaluation
- [ ] Streaming architectures
- [ ] Async generators
- [ ] Backpressure handling

#### Real Systems

- [ ] File streaming
- [ ] Large dataset processing

---

### 👉 15. Proxy & Reflect API

#### Deep Dive

- [ ] Reactive systems internals
- [ ] Vue reactivity model
- [ ] Meta programming
- [ ] Runtime validation

#### Interview-Level

- [ ] Building your own reactive store

---

### 👉 16. WebRTC

#### Deep Dive

- [ ] ICE candidates
- [ ] STUN/TURN servers
- [ ] NAT traversal
- [ ] Peer negotiation
- [ ] Media streams

#### Production Knowledge

- [ ] Scaling WebRTC systems
- [ ] Mesh vs SFU vs MCU

---

### 👉 17. Server-Sent Events (SSE)

#### Deep Dive

- [ ] SSE vs WebSocket
- [ ] Reconnection handling
- [ ] Streaming AI responses
- [ ] Event ordering

#### Real-World

- [ ] ChatGPT-style streaming

---

### 👉 18. JavaScript Event Loop & Async

#### Deep Dive

- [x] Microtasks vs macrotasks
- [ ] Starvation problems
- [ ] Rendering synchronization
- [ ] Task scheduling

#### Interview Focus

- [ ] Predict async execution order
- [ ] Browser vs Node.js event loop

---

### 👉 19. Frontend Security

#### Deep Dive

- [ ] DOM XSS
- [ ] Sanitization
- [ ] Trusted Types
- [ ] CSRF token architecture
- [ ] Clickjacking

#### Production Knowledge

- [ ] Secure auth storage
- [ ] SameSite cookies

---

### 👉 20. Performance Optimization

#### Deep Dive

- [ ] Main-thread blocking
- [ ] Long tasks
- [ ] GPU compositing
- [ ] Virtualization
- [ ] Resource prioritization

#### Engineering Tools

- [ ] Chrome Performance tab
- [ ] Flamegraphs

---

### 👉 21. Accessibility Auditing

#### Deep Dive

- [ ] Screen reader testing
- [ ] Focus management
- [ ] Accessible modals
- [ ] ARIA misuse

#### Real Engineering

- [ ] Accessibility architecture

---

### 👉 22. SEO Technical Optimization

#### Deep Dive

- [ ] Crawl budget
- [ ] Rendering SEO
- [ ] SSR vs CSR SEO
- [ ] Structured data
- [ ] Canonicalization

#### Production Knowledge

- [ ] Indexing failures
- [ ] SEO debugging

---

### 👉 23. Internationalization (i18n)

#### Deep Dive

- [ ] ICU message formatting
- [ ] RTL rendering
- [ ] Locale negotiation
- [ ] Translation loading optimization

#### Real Engineering

- [ ] Multi-region architecture

---

⬅ [Back to main guide](../README.md)
