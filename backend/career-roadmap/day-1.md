# Career in Backend — A Life Long Roadmap

**By HM Nayem** — Author & Educator, Founder & CTO at Stack Learner, Technical Screener & Full-stack Developer at Toptal

⬅ [Roadmap index](README.md) · Next: [Day 2 — Problem with Backend](day-2.md)

## Day 1 — Big Picture of Backend

### Agenda

- **Day 1** – Big Picture of Backend
- **Day 2** – Problem with Backend
- **Day 3** – Journey to Become an Architect

---

## Frontend vs Backend

- **Frontend**: Users see it, ~20% of total effort.
- **Backend**: Users don't see it, ~80% of total effort, repetitive.
- They meet at the **API** (like the visible tip of an iceberg vs. the massive body underwater).
- Frontend has a **boundary** because the scope of the browser is very limited.
- But... **possibilities in backend are endless** — it's easy to get "lost in the deep sea." Once you learn to navigate it, you get to "enjoy the beauty of the sea."

---

## What is Backend?

### How does a computer help us?

- Storing information that can easily be accessed
- Doing heavy calculations on stored information
- Doing automation to reduce repetitive tasks

### We need to store information — but how?

**File System**

- We can store all kinds of data inside a text file and it will persist.

**Problems with the File System**

- Very slow
- Difficult to access
- Limited structuring
- Not scalable for large volumes of data
- No pre-processing
- No search
- ...and a lot of other problems

**Database**

- Smart people addressed all these issues and developed the database to store all kinds of information in a way that's easy to access.
- Database is the core component of modern web applications.

### Direct database access

- Users could directly access the database to store and retrieve information (e.g., Microsoft Access, Microsoft Excel).

**Drawbacks**

- Lack of security
- Lack of permissions
- No custom business logic
- No validation check
- We can't give direct database access to our users

### We need control over our database → Business Logic

- Add an application layer on top of the database.
- Users communicate with the database via the application.
- This gives us control over access and lets us validate data before inserting it.

**Drawbacks**

- No visual layer
- Bad user experience
- No dynamic content
- Only prewritten scripts

### User Interface Layer

- Add an extra layer for the user.
- Users can see and interact with the data.
- Dynamic content, with prewritten scripts that can interact with that dynamic content.
- Package it all together: **User Interface → Business Logic → Database**.

### Package & Ship

- Traditional software package that integrates all components (UI + Business Logic + Database).
- Easy to ship, but everything lives on the client's machine.
- No centralized or distributed solution.
- Distribution media of the era: CD-ROM, Flash Drive, Floppy Disk, Hard Disk, Zip Drive, Magnetic Tape.

---

## The Internet is Born

- Packaged software distribution is no longer sufficient once the internet exists.
- We need a different solution: a **central database** that can be accessed by all users, so everyone sees the same data.
- This requires **networking** to connect clients to a central application/database.

### Networking Concepts

- IP Address
- Domain Name System (DNS)
- Protocol
- Packet
- Buffer
- SSL / TLS

**The DNS process (step-by-step):**
1. Computer requests a domain (e.g. `www...`) from the DNS Resolver.
2. Resolver queries the Root Server.
3. Root Server points to the TLD Server.
4. TLD Server points to the Authoritative Server.
5. Authoritative Server returns the IP.
6. Resolver returns IP to the computer.
7. Computer connects directly to the website/server.

### Putting it together: the Web Server

- Client sends a request to an IP (e.g. `192.172.168.21`), resolved via DNS.
- The **Web Server** receives the Request, routes it to **Application/Business Logic**, which talks to the **Database**, and returns a **Response**.

**This is Backend.**

---

## From now on, we focus on four things

| Component | Description |
|---|---|
| **Web Server App** | Accepts and routes HTTP requests |
| **Application** | Business logic that processes requests |
| **Database** | Stores and retrieves data |
| **Server** | The machine everything runs on |

---

## Web Server

A web server is computer software (and underlying hardware) that accepts requests via HTTP or its secure variant, HTTPS. Common examples: **Apache**, **Nginx**.

**Responsibilities**

- Handling HTTP requests
- Serving static files
- Processing dynamic content
- Load balancing and reverse proxy
- Logging & monitoring
- ...and a lot more

---

## Application

- Requests are "selfish" — Request → Response.
- Flow: **Request → Validation/Security → Business Logic → (Other Services / Database) → Process Response → Response**

**Types of Response**

- Text
- XML
- JSON
- Files

**Main Responsibilities**

- Authentication / Authorization
- Validation
- Database access
- Synchronous communication
- Asynchronous communication
- Schedule / CRON jobs
- CRUD operations
- Generate final response

Applications can be built with **any programming language** and **any associated framework**.

---

## Database

**SQL**, and **NoSQL** — which includes:

- Document
- Key-value
- Graph
- Timeseries
- Wide column
- Multi-model

Popular systems: Oracle, MongoDB, Couchbase, Azure, SQL Server, PostgreSQL, IBM DB2, Redis, Firebird, SAP HANA, and more.

---

## Server

We need somewhere to run our code.

- Basic server administration
- Common Linux commands
- Basic networking
- DNS configuration
- SSL/TLS

---

## Now You Are a Backend Developer

**What is the objective?**

- Respond to a request.
- Understand the request.
- Do whatever it takes to send a response.

This is the straightforward approach: if you can write code and solve problems, you're already a backend developer.

**But there are a lot of flaws** in this simple view — that's the subject of Day 2.

---

⬅ [Roadmap index](README.md) · Next: [Day 2 — Problem with Backend](day-2.md)
