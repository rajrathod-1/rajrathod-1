## Raj Rathod

Computer science at the University of Manitoba (co-op), graduating 2026. Most
recently a software developer intern at Citigroup; before that Ericsson and
Proofpoint.

I'm interested in programming languages and type systems, testing and
correctness, and distributed systems.

### What I'm building

**Limit order book and matching engine** — C++, Python

A price-time priority matching engine supporting limit, market and cancel
orders, with sorted price levels and an order-id index so cancels don't scan
the book. I test it by replaying randomly generated order streams against a
deliberately simple Python reference implementation and diffing every fill,
which catches the partial-fill and cancel edge cases my hand-written unit tests
missed.

**Interpreter for a small functional language** — Python

A parser and evaluator for a language with closures, algebraic data types and
pattern matching. I'm adding Hindley-Milner type inference so ill-typed
programs are rejected before they run, with errors that point at the offending
expression.

### Recent work

**Citigroup** · Software Developer Intern · May – Sep 2026

Full-stack user management platform in React and TypeScript over Spring Boot
APIs, reshaped around how the data grid actually paged, cutting retrieval
latency by 40%. Event-driven services in Java 21 with Kafka and Oracle DB, plus
Elasticsearch search across 500K+ records.

**Ericsson** · Software Developer Intern · Jan – Apr 2026

Backend services in Java and Python on multi-cluster Kubernetes, improving
uptime by 25% by isolating faults in code I had inherited rather than written.
Added monitoring to services that had none, so the team heard about failures
before users did.

**Proofpoint** · Software Developer Intern · Oct 2024 – Dec 2025

Python and Flask services on MySQL handling 10,000+ daily requests at 99.9%
uptime, with circuit breakers and retries so downstream failures degraded
gracefully. Automated multi-step workflows on AWS for the operations team.

### Also built

- **[Retrieval-augmented question answering service](https://github.com/rajrathod-1/AI-Content-Generation)**
  — Python, Flask, FAISS, Redis. Timed every stage before optimising and found
  retrieval, not the model call, was the bottleneck.
- **TCP proxy server** — C++, POSIX sockets. A multithreaded Layer 4 proxy with
  event-driven I/O, simple routing and load balancing, with per-connection
  telemetry so I could see where throughput dropped and why.
- **[Interactive portfolio](https://github.com/rajrathod-1/portfolio)** — React,
  TypeScript, Tailwind. A terminal you can actually type in.

### Tools

Python · C++ · Java · TypeScript · SQL

Linux · Git · Kafka · Elasticsearch · Redis · Docker · Kubernetes · AWS ·
GitLab CI · Jenkins

### Elsewhere

[LinkedIn](https://linkedin.com/in/raj-rathod1) ·
[LeetCode](https://leetcode.com/u/popple_1) ·
[Portfolio](https://github.com/rajrathod-1/portfolio) ·
[rajrathod23232@gmail.com](mailto:rajrathod23232@gmail.com)
