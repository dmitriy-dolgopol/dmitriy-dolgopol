<div align="center">

# Dmitry Dolgopol

Senior Golang Developer · 6+ years of backend experience · GMT+4

[LinkedIn](https://www.linkedin.com/in/mitya-dolgopolsky-29589043a/) · [Email](mailto:dolgopol.dima@gmail.com) · [GitHub](https://github.com/dmitriy-dolgopol/)  
[+995 557 25 37 08](https://wa.me/995557253708)

</div>

---

## About Me

Senior Golang Developer with 6+ years of backend engineering experience in fintech, e-commerce, and marketing platforms.

I build Go microservices, event-driven systems, and high-load APIs where latency, consistency, and fault tolerance directly affect business operations.

My strongest areas are asynchronous processing, Kafka/RabbitMQ pipelines, PostgreSQL optimization, Redis caching, Kubernetes-based services, and production incident debugging.

I focus on making systems predictable under load: reducing bottlenecks, controlling retries, improving observability, and protecting critical flows from unstable external dependencies.

---

## Skills

| Area | Technologies |
| --- | --- |
| Languages | Go, SQL, Python, PHP |
| Backend | REST API, gRPC, microservices, event-driven architecture, distributed systems |
| Messaging | Kafka, RabbitMQ, DLQ, retry policies, idempotency, partitioning, backpressure |
| Databases | PostgreSQL, Redis, ClickHouse, Elasticsearch |
| Observability | Prometheus, Grafana, ELK, logging, metrics, alerting, P95/P99 latency analysis |
| Infrastructure | Docker, Kubernetes, Yandex Cloud, GitLab CI, Nginx, Kong |
| Engineering Practices | Code review, incident response, load-related debugging, SQL optimization, concurrency control |

---

## Experience

### [Swissquote](https://www.swissquote.com/) — Senior Backend / Golang Developer

**November 2023 — Present**

Trading and brokerage services processing tens of thousands of order events daily. Developed Go services, gRPC/REST APIs and Kafka pipelines; maintained PostgreSQL data flows, worker scalability and production reliability.

- Isolated external failures with load limits and controlled timeouts, reducing peak p95 latency from 620-680 to 240-290 ms without cascading degradation.
- Redesigned Kafka status processing with separate synchronous/background stages, order-based partitioning, idempotency and bounded retries; kept event reprocessing below 0.1%.
- Introduced workload-specific worker pools and limits on parallel external calls, cutting processing time for 50,000 events from about 11 to 6-7 minutes.
- Implemented a status state machine and atomic PostgreSQL checks, reducing conflicts during concurrent updates and duplicate delivery.
- Added SLOs, metrics and tracing for latency, errors and backlog, reducing incident diagnosis time from 40-45 to 15-20 minutes.
- Improved Python reconciliation tools for ClickHouse/PostgreSQL, cutting daily status checks from 50 to 20-25 minutes and surfacing discrepancies before trading.

**Technologies:** Go, Python, Kafka, PostgreSQL, ClickHouse, gRPC, REST API, GitLab CI/CD, Prometheus, Grafana, OpenTelemetry, ELK

---

### [Erewhon](https://erewhon.com/) — Backend / Golang Developer

**July 2021 — October 2023**

E-commerce catalog, search, filtering and personalized recommendations for web and mobile. Developed Go services and external API integrations; optimized PostgreSQL, Redis and Elasticsearch.

- Optimized Redis caching and PostgreSQL queries, cutting catalog API p95 from 1.4-1.6 s to 400-480 ms and peak database load by about 30%.
- Designed Elasticsearch indexes and pagination for 35,000 SKUs, reducing search p95 from 2.1 s to 430-560 ms.
- Built adapters for Retail Rocket, KISSmetrics and Symantec.cloud with timeouts, retries and fallbacks, preventing failures from blocking the catalog and recommendations.
- Added Prometheus/Grafana dashboards, ELK logs and integration alerts, cutting MTTR for common integration failures from 35-40 to 15-18 minutes.
- Improved Docker environments, GitLab CI/CD and catalog integration tests, cutting release test environment setup from several hours to 35-45 minutes.

**Technologies:** Go, PostgreSQL, Redis, Elasticsearch, REST API, Docker, GitLab CI/CD, Prometheus, Grafana, ELK

---

### [Andersen Lab](https://andersenlab.com/) — Backend / Golang Developer

**April 2020 — July 2021**

Custom request and event processing service for a commercial client, handling variable loads up to 150 RPS. A synchronous API accepted operations; RabbitMQ distributed background tasks across consumer services, with consistent state under duplicate delivery.

Developed Go asynchronous processing components and PostgreSQL/Redis integrations; investigated concurrency issues, maintained Docker/Kubernetes environments and supported queue incident response.

- Reworked RabbitMQ processing with manual acknowledgements, bounded retries and DLQs, reducing unprocessed messages under load and improving throughput by about 20%.
- Used the Go race detector to isolate race conditions, restructured critical sections and synchronized concurrent updates, reducing recurring processing errors under load.
- Rebalanced consumers and separated queues by event type, reducing background task p95 wait time from 1.8-2.2 s to 650-800 ms at up to 150 RPS.
- Added detailed logging, retry/error/latency metrics and Redis caching for reference data, cutting initial queue incident diagnosis from 30 to 15-20 minutes.

**Technologies:** Go, RabbitMQ, PostgreSQL, Redis, Docker, Kubernetes

---

## Education

### ITMO University — St. Petersburg — Bachelor

**2017 — 2021**  
Information and Computer Science

### ITMO University — St. Petersburg — Master

**2021 — 2023**  
Development and Maintenance of a High-Quality Software Product

---

## Additional

- Production experience with high-load APIs, financial transaction processing, asynchronous pipelines, and external API degradation.
- Strong focus on reliability: idempotency, retries, DLQ, backpressure, circuit breakers, state consistency, and incident-driven improvements.
