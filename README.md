# Hi, I'm Caio Souza

Software Engineer with a background in **Computer Engineering**, specializing in distributed microservices architectures, data privacy engineering, and interactive web graphics. My work centers on building resilient systems that solve complex technical problems: from event-driven backend pipelines and low-latency WebGL physics simulations to regulatory data privacy protection and offline-first mobile applications.

---

## Core Focus Areas

- **Distributed Systems & Microservices:** Event-driven architectures, asynchronous data ingestion pipelines, reverse-proxy gateway security, and distributed tracing.
- **Data Privacy & Healthcare Informatics:** Regulatory compliance (LGPD), PII sanitization in web access logs and API paths, streaming data processing, and large-scale data aggregation.
- **Interactive 3D Web & Physics Simulation:** WebGL2, Three.js, React Three Fiber, WebAssembly physics engines (Rapier 3D), and procedural vector graphics.
- **Modern Full-Stack & Clean Architecture:** Hexagonal Architecture (Ports and Adapters), TypeScript monorepos, strict layered architectures, and offline-first mobile applications with React Native.

---

## Featured Engineering Case Studies

Detailed architectural studies categorized across engineering tracks in the [**`case-studies`**](https://github.com/Fcsscoder/case-studies) repository:

### [1. Interactive Degree Curriculum Graph Engine & Collaborative Whiteboard](https://github.com/Fcsscoder/case-studies/tree/main/fullstack-and-monorepos/academic-curriculum-dag-whiteboard)
*TypeScript · React 19 · Express · Prisma · PostgreSQL · MinIO · Docker · Zod*
- Engineered a TypeScript monorepo modeling complex university degree curricula as interactive directed acyclic graphs (DAGs).
- Implemented an idempotent analytics event ingestion pipeline with concurrency locks and cohort reporting.
- Designed a single-writer write-behind queue for a collaborative whiteboard, decoupling stroke rendering from database persistence to eliminate input latency.

### [2. First-Person 3D WebGL Clinical Laboratory & Physics Simulation](https://github.com/Fcsscoder/case-studies/tree/main/3d-graphics-and-simulation/clinical-lab-webgl-physics-simulation)
*Three.js · React Three Fiber · Rapier 3D (Wasm) · TypeScript · Vite · Playwright*
- Developed a first-person 3D laboratory simulation running entirely client-side in WebGL2 browsers without remote server rendering.
- Built a 1:1 screen-space aligned quaternion object inspection camera with depth-of-field bokeh blur, eliminating gimbal lock and rotational drift.
- Modeled clinical equipment finite-state machines (centrifuges, incubators, analytical precision scales) with automated Playwright performance tests.

### [3. High-Throughput Node.js Distributed Tracing & Structured Logging Library](https://github.com/Fcsscoder/case-studies/tree/main/backend-and-distributed-systems/distributed-observability-lib)
*TypeScript · Node.js · Pino · Axios · AsyncLocalStorage*
- Authored a lightweight, in-house distributed observability module standardizing telemetry across internal microservices.
- Implemented end-to-end trace correlation header propagation (`X-Correlation-Id`, `X-Installation-Id`) across asynchronous callbacks and HTTP client requests.
- Engineered intelligent health-check noise suppression, filtering redundant 200 OK probes while guaranteeing full diagnostic capture on degraded services.

### [4. Scalable Clinical Record Ingestion & PII Sanitization Architecture](https://github.com/Fcsscoder/case-studies/tree/main/data-engineering-and-privacy/clinical-record-pii-sanitization)
*Python · Flask · PostgreSQL · Docker · Nginx*
- Refactored healthcare data pipelines to eliminate Personally Identifiable Information (PII) from URL paths, query parameters, and web server access logs.
- Engineered an O(1) memory generator-based streaming CSV ingestion pipeline capable of processing massive municipal health registries without memory spikes.
- Optimized relational database performance using composite indexes, normalized citizen keys, and automated risk stratification workflows.

### [5. Hexagonal Architecture Identity & Access Management Microservice](https://github.com/Fcsscoder/case-studies/tree/main/backend-and-distributed-systems/hexagonal-auth-service)
*TypeScript · Node.js · Express · PostgreSQL · JWT · Mutation Testing*
- Architected an IAM microservice under strict Hexagonal Architecture (Ports and Adapters), isolating core domain rules from frameworks and database adapters.
- Solved race condition session invalidations during parallel token refreshes by engineering concurrent refresh token rotation locks.
- Verified authorization policies and multi-tenant access gates using formal mutation testing suites.

### [6. Real-Time Fleet Transit Navigation & Privacy-Preserving Mobile Application](https://github.com/Fcsscoder/case-studies/tree/main/mobile-engineering/campus-mobility-transit-app)
*React Native · Expo · TypeScript · NativeWind · Android Exact Alarms*
- Engineered a cross-platform mobile application supporting thousands of daily active users for institutional transit fleet tracking.
- Developed an accessible single-stroke SVG transit timeline with an animated pulsating origin, respecting user `reduce motion` settings.
- Built an architectural consent gate enforcing complete telemetry and network communication dormancy until explicit user privacy consent is granted.

---

## Technical Stack & Competencies

| Domain | Technologies & Frameworks |
|---|---|
| **Languages & Runtimes** | TypeScript, JavaScript, Python 3, C++ (Embedded/Arduino), SQL |
| **Backend & Microservices** | Node.js, Express.js, Flask, Prisma ORM, Hexagonal Architecture, Zod, RESTful APIs |
| **Frontend & Mobile** | React, React Native, Expo, Next.js (App Router), Tailwind CSS, NativeWind, TanStack Query |
| **3D Graphics & Game Engines** | Three.js, React Three Fiber, Rapier 3D (Wasm), HTML5 Canvas 2D, Web Audio API |
| **Data & Storage** | PostgreSQL, MongoDB, SQLite, Turso (libSQL), MinIO (S3-compatible), Redis/Caches |
| **Messaging & Telemetry** | MQTT (Mosquitto), Socket.IO (WebSockets), Server-Sent Events (SSE), Pino |
| **DevOps & Infrastructure** | Docker, Docker Compose, Nginx, GitHub Actions, GHCR, Linux VPS, Git |
| **Testing & Security** | Playwright, Jest, Vitest, Pytest, Mutation Testing, Cosign, Trivy |

---

## Browse Case Studies by Track

Explore the complete collection of 14 engineering case studies in [**`Fcsscoder/case-studies`**](https://github.com/Fcsscoder/case-studies):

- 🌐 [**Backend & Distributed Systems**](https://github.com/Fcsscoder/case-studies/tree/main/backend-and-distributed-systems)
- 📱 [**Mobile Engineering**](https://github.com/Fcsscoder/case-studies/tree/main/mobile-engineering)
- 💻 [**Frontend & Web Applications**](https://github.com/Fcsscoder/case-studies/tree/main/frontend-and-web-apps)
- 🎮 [**3D Graphics, WebGL & Simulation**](https://github.com/Fcsscoder/case-studies/tree/main/3d-graphics-and-simulation)
- 🔒 [**Data Engineering & Privacy**](https://github.com/Fcsscoder/case-studies/tree/main/data-engineering-and-privacy)
- 📦 [**Full-Stack & Monorepos**](https://github.com/Fcsscoder/case-studies/tree/main/fullstack-and-monorepos)
- ⚡ [**Embedded Systems & IoT**](https://github.com/Fcsscoder/case-studies/tree/main/embedded-systems-and-iot)

---

## Connect

- **GitHub:** [@Fcsscoder](https://github.com/Fcsscoder)
- **Email:** Contact available via GitHub profile
