# Hi, I'm Caio Souza

<p align="left">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

I am a Computer Engineering student and Software Engineer focused on backend architecture, distributed systems, data privacy engineering, and full-stack web platforms.

My background centers on understanding how complex software behaves under the hood. I enjoy analyzing systems, finding architectural bottlenecks, and building software that balances reliability, performance, maintainability, and security. For me, engineering is about understanding the core problem before writing the first line of code.

---

## Engineering Philosophy

- **Clear boundaries:** Decouple domain rules from infrastructure and presentation layers so systems remain modular, testable, and resilient to change.
- **Evidence-based decisions:** Ground architectural choices in profiling, automated testing, and observable system metrics rather than assumptions.
- **Privacy and security by design:** Treat data protection, access controls, and log sanitization as core architectural requirements from the start.
- **Reliability and observability:** Build predictable error recovery into services and instrument clear trace context so operational issues are straightforward to diagnose.

---

## Core Focus Areas

- **Distributed Systems and Microservices:** Building asynchronous data ingestion pipelines, managing inter-service communication, and standardizing distributed tracing across service boundaries.
- **Data Privacy and Healthcare Informatics:** Protecting sensitive user records, implementing regulatory requirements like LGPD, and engineering streaming data pipelines for large municipal datasets.
- **Full-Stack and Monorepo Architectures:** Applying patterns like Hexagonal Architecture to isolate core business rules, structuring TypeScript monorepos, and building decoupled client-side state engines.
- **Mobile and Client Engineering:** Developing cross-platform applications with React Native, focusing on offline-first caching, accessibility, and strict privacy consent gates.

---

## Featured Engineering Case Studies

Detailed architectural studies categorized across engineering tracks in the [**`case-studies`**](https://github.com/Fcsscoder/case-studies) repository:

### [1. Interactive Degree Curriculum Graph Engine and Collaborative Whiteboard](https://github.com/Fcsscoder/case-studies/tree/main/fullstack-and-monorepos/academic-curriculum-dag-whiteboard)
*TypeScript, React 19, Express, Prisma, PostgreSQL, MinIO, Docker, Zod*
- Structured a TypeScript monorepo that models university curricula as interactive directed acyclic graphs (DAGs).
- Implemented an idempotent analytics ingestion pipeline with database concurrency locks and cohort reporting.
- Designed a single-writer write-behind queue for a collaborative whiteboard, decoupling stroke rendering from database persistence to maintain steady 60 FPS drawing.

### [2. High-Throughput Node.js Distributed Tracing and Structured Logging Library](https://github.com/Fcsscoder/case-studies/tree/main/backend-and-distributed-systems/distributed-observability-lib)
*TypeScript, Node.js, Pino, Axios, AsyncLocalStorage*
- Authored a lightweight distributed observability library that standardizes logging across internal microservices.
- Implemented trace correlation header propagation (`X-Correlation-Id`, `X-Installation-Id`) across asynchronous callbacks and HTTP client requests.
- Engineered intelligent health-check filtering that mutes routine 200 OK probes while capturing complete diagnostic telemetry on degraded services.

### [3. Scalable Clinical Record Ingestion and PII Sanitization Architecture](https://github.com/Fcsscoder/case-studies/tree/main/data-engineering-and-privacy/clinical-record-pii-sanitization)
*Python, Flask, PostgreSQL, Docker, Nginx*
- Refactored healthcare data pipelines to eliminate Personally Identifiable Information (PII) from URL paths, query parameters, and web server access logs.
- Engineered a generator-based streaming CSV ingestion pipeline that processes large municipal registries within a flat memory footprint to prevent memory exhaustion.
- Optimized relational database performance using composite indexes, normalized citizen keys, and automated risk stratification workflows.

### [4. Hexagonal Architecture Identity and Access Management Microservice](https://github.com/Fcsscoder/case-studies/tree/main/backend-and-distributed-systems/hexagonal-auth-service)
*TypeScript, Node.js, Express, PostgreSQL, JWT, Mutation Testing*
- Architected an IAM microservice using Hexagonal Architecture (Ports and Adapters), keeping domain logic independent of web frameworks and database drivers.
- Resolved race-condition session invalidations during parallel token refreshes by implementing concurrent refresh token rotation locks.
- Validated authorization policies and multi-tenant access gates using mutation testing suites to ensure conditional branches cannot be bypassed.

### [5. Fault-Tolerant Unstructured Document Ingestion Pipeline and Hardened Gateway](https://github.com/Fcsscoder/case-studies/tree/main/backend-and-distributed-systems/fault-tolerant-ingestion-gateway)
*Python 3, PyPDF, Node.js, Express, Docker Compose, Nginx, MongoDB*
- Built an extraction worker backed by 31 automated regression tests to reliably parse complex multi-column tabular PDF documents.
- Designed ownership fencing contracts to prevent automated sync daemons from overwriting manual administrative corrections.
- Hardened the reverse proxy gateway with burst limits, connection caps, and route-level protection against abuse.

### [6. Real-Time Fleet Transit Navigation and Privacy-Preserving Mobile Application](https://github.com/Fcsscoder/case-studies/tree/main/mobile-engineering/campus-mobility-transit-app)
*React Native, Expo, TypeScript, NativeWind, Android Exact Alarms*
- Developed a cross-platform mobile application for institutional transit fleet tracking and route navigation.
- Created an accessible single-stroke SVG transit timeline with an animated pulsating origin, designed to respect user reduced-motion accessibility settings.
- Built a technical consent gate that halts background network communication and telemetry until explicit user privacy consent is granted.

---

## Technical Stack

| Domain | Technologies and Frameworks |
|---|---|
| **Languages and Runtimes** | TypeScript, JavaScript, Python 3, C++ (Embedded/Arduino), SQL |
| **Backend and Microservices** | Node.js, Express.js, Flask, Prisma ORM, Hexagonal Architecture, Zod, RESTful APIs |
| **Frontend and Mobile** | React, React Native, Expo, Next.js (App Router), Tailwind CSS, NativeWind, TanStack Query |
| **Data and Storage** | PostgreSQL, MongoDB, SQLite, Turso (libSQL), MinIO (S3-compatible), Caching |
| **Messaging and Telemetry** | MQTT (Mosquitto), Socket.IO (WebSockets), Server-Sent Events (SSE), Pino |
| **DevOps and Infrastructure** | Docker, Docker Compose, Nginx, GitHub Actions, GHCR, Linux VPS, Git |
| **Testing and Security** | Playwright, Jest, Vitest, Pytest, Mutation Testing, Cosign, Trivy |

---

## Browse Case Studies by Track

Explore production engineering case studies in [**`Fcsscoder/case-studies`**](https://github.com/Fcsscoder/case-studies):

- [**Backend and Distributed Systems**](https://github.com/Fcsscoder/case-studies/tree/main/backend-and-distributed-systems)
- [**Mobile Engineering**](https://github.com/Fcsscoder/case-studies/tree/main/mobile-engineering)
- [**Frontend and Web Applications**](https://github.com/Fcsscoder/case-studies/tree/main/frontend-and-web-apps)
- [**Data Engineering and Privacy**](https://github.com/Fcsscoder/case-studies/tree/main/data-engineering-and-privacy)
- [**Full-Stack and Monorepos**](https://github.com/Fcsscoder/case-studies/tree/main/fullstack-and-monorepos)
- [**Embedded Systems and IoT**](https://github.com/Fcsscoder/case-studies/tree/main/embedded-systems-and-iot)

---

## Connect

- GitHub: [@Fcsscoder](https://github.com/Fcsscoder)
- Contact: Reach out through my GitHub profile
