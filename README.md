# Engineering Foundation Guide

> This repository is a comprehensive Web Engineering Checklist covering essential frontend, backend, full-stack, and DevOps topics for modern developers. It includes advanced concepts, best practices, security, performance, and real-world tools that are crucial for building scalable, secure, and high-performance web applications, as well as for preparing for top developer roles and interviews.

## Frontend Topics (23)

| #   | Topic                              | Description                                                                      |
| --- | ---------------------------------- | -------------------------------------------------------------------------------- |
| 1   | Service Workers & Cache Strategies | Cache data in the browser to enable offline usage (important for PWAs)           |
| 2   | HTTP/2 & HTTP/3                    | Modern protocols handling multiple requests simultaneously for faster load times |
| 3   | Content Security Policy (CSP)      | Controls which scripts run in the browser to prevent XSS attacks                 |
| 4   | Rate Limiting & Throttling         | Protects APIs from overload by limiting excessive requests                       |
| 5   | Code Splitting & Lazy Loading      | Splits large JS files, loads only required code for faster performance           |
| 6   | Tree Shaking                       | Removes unused code to reduce bundle size (Webpack/Vite)                         |
| 7   | Core Web Vitals                    | Metrics (LCP, FID, CLS) to measure site performance and UX                       |
| 8   | Progressive Enhancement            | Ensures basic functionality works even without JS, supports older browsers       |
| 9   | WebAssembly (WASM)                 | Run faster code (C++, Rust) in the browser for heavy computations                |
| 10  | Advanced CSS Grid & Flexbox        | Create complex, responsive layouts efficiently                                   |
| 11  | CSS Custom Properties & Houdini    | Dynamic CSS variables and custom styling capabilities                            |
| 12  | JavaScript Closures & Currying     | Manage private data and create reusable functions                                |
| 13  | Memoization & useMemo Hooks        | Optimize rendering by avoiding unnecessary computations                          |
| 14  | Generators & Async Iterators       | Handle large datasets or streams efficiently                                     |
| 15  | Proxy & Reflect API                | Customize object behavior and enable meta-programming                            |
| 16  | WebRTC                             | Real-time peer-to-peer video/audio communication                                 |
| 17  | Server-Sent Events (SSE)           | Server-to-client real-time updates                                               |
| 18  | Core JavaScript Event Loop & Async | Understand promises, async/await, microtasks/macrotasks                          |
| 19  | Frontend Security Basics           | XSS, CSRF protection, input validation                                           |
| 20  | Performance Optimization           | Lazy loading images, minimizing render-blocking scripts                          |
| 21  | Accessibility Auditing             | WCAG 2.2 compliance, screen readers, keyboard navigation                         |
| 22  | SEO Technical Optimization         | Schema.org, sitemap, meta tags for search ranking                                |
| 23  | Internationalization (i18n)        | Multi-language support and locale detection                                      |

## Backend Topics (17)

| #   | Topic                             | Description                                                           |
| --- | --------------------------------- | --------------------------------------------------------------------- |
| 1   | Microservices Architecture        | Split large apps into independent services for scaling and resilience |
| 2   | Serverless Computing              | Run functions on cloud (AWS Lambda) without managing servers          |
| 3   | GraphQL vs REST                   | Fetch only required data efficiently, optimize API calls              |
| 4   | OAuth 2.0 & OpenID Connect        | Secure login systems and user data protection                         |
| 5   | JWT Token Management              | Verify user identity and permissions securely, refresh tokens         |
| 6   | SQL Injection Prevention          | Use prepared statements to prevent DB hacking                         |
| 7   | CSRF Tokens                       | Protect against fake form submissions                                 |
| 8   | Horizontal vs Vertical Scaling    | Scale server capacity or add more servers for high traffic            |
| 9   | Load Balancing                    | Distribute traffic across multiple servers (e.g., NGINX)              |
| 10  | Database Sharding & Partitioning  | Split DB into smaller parts to speed up queries for large apps        |
| 11  | Caching Layers & CDN Optimization | Use Redis/Memcached to reduce server load and improve speed           |
| 12  | Message Queues                    | Asynchronous task processing (RabbitMQ, Kafka)                        |
| 13  | Data Encryption                   | AES-256 encryption for storage and transit                            |
| 14  | Zero-Trust Security               | Verify everything, never fully trust any source                       |
| 15  | Security Testing                  | OWASP ZAP to check vulnerabilities                                    |
| 16  | AI-Driven Chatbots                | NLP-based bots (Dialogflow) for 24/7 support                          |
| 17  | Web Scraping & Automation         | Extract data from websites (Cheerio, Puppeteer)                       |

## Full-Stack / DevOps & Others (12)

| #   | Topic                           | Description                                                    |
| --- | ------------------------------- | -------------------------------------------------------------- |
| 1   | Containerization with Docker    | Package apps and environment to run anywhere                   |
| 2   | Orchestration with Kubernetes   | Manage and auto-scale multiple containers                      |
| 3   | CI/CD Pipelines                 | Automate build, test, and deployment (GitHub Actions, Jenkins) |
| 4   | Infrastructure as Code          | Manage servers using code (Terraform)                          |
| 5   | Blue-Green & Canary Deployments | Deploy new releases without downtime and test gradually        |
| 6   | End-to-End Testing              | Full app flow testing (Cypress, Playwright)                    |
| 7   | Performance Budgeting           | Set limits for load time & resource usage                      |
| 8   | Jamstack Architecture           | Static sites + APIs for speed and security                     |
| 9   | Headless CMS                    | Manage content separately from frontend (Strapi)               |
| 10  | Event-Driven Architecture       | Apps driven by events, scalable and decoupled                  |
| 11  | Circuit Breakers                | Prevent whole system failure if one service fails              |
| 12  | Monitoring & Observability      | Real-time health checks (Prometheus, Grafana)                  |
