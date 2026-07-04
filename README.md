<div align="center">

Dmitry Dolgopol

Senior Golang Developer · 6+ years of backend experience · GMT+4

[LinkedIn](https://www.linkedin.com/in/dmitriy-dolgopol/) · [Email](dolgopol.dima@gmail.com) · [GitHub](https://github.com/dmitriy-dolgopol/)  
[+995 557 25 37 08](http://wa.me/995557253708)

</div>

***
About Me

Senior Golang Developer with 6+ years of backend engineering experience in fintech, e-commerce, and marketing platforms.

I build Go microservices, event-driven systems, and high-load APIs where latency, consistency, and fault tolerance directly affect business operations.

My strongest areas are asynchronous processing, Kafka/RabbitMQ pipelines, PostgreSQL optimization, Redis caching, Kubernetes-based services, and production incident debugging.

I focus on making systems predictable under load: reducing bottlenecks, controlling retries, improving observability, and protecting critical flows from unstable external dependencies.

***
Skills

Area	Technologies
Languages	Go, SQL, Python, PHP
Backend	REST API, gRPC, microservices, event-driven architecture, distributed systems
Messaging	Kafka, RabbitMQ, DLQ, retry policies, idempotency, partitioning, backpressure
Databases	PostgreSQL, Redis, ClickHouse, Elasticsearch
Observability	Prometheus, Grafana, ELK, logging, metrics, alerting, P95/P99 latency analysis
Infrastructure	Docker, Kubernetes, Yandex Cloud, GitLab CI, Nginx, Kong
Engineering Practices	Code review, incident response, load-related debugging, SQL optimization, concurrency control
	***
Experience

[INTERACTIVE BROKERS](https://www.interactivebrokers.com/) — Senior Backend / Golang Developer

November 2023 — Present · 3+ years

Fintech platform for brokerage operations, IPO workflows, transaction processing, asset management, and external financial integrations.

Designed and developed Go microservices for transaction workflows handling more than 10,000 financial operations per day and peak loads above 1,000 RPS.
Reworked the transaction processing model by splitting synchronous and asynchronous paths, reducing latency for critical operations by approximately 35%.
Introduced bulkheads, backpressure, circuit breakers, isolated worker pools, and bounded queues to prevent cascading failures during external API degradation.
Improved Kafka-based processing with entity-key partitioning, idempotency, controlled retry logic, and explicit state transitions, reducing duplicate processing and status conflicts.
Added observability around queue depth, backlog, retry rate, error rate, and P95/P99 latency, making production incidents easier to detect and debug.

Technologies: Go, Kafka, PostgreSQL, Redis, ClickHouse, gRPC, REST, Kubernetes, Docker, Yandex Cloud, Prometheus, Grafana, ELK, Kong

***
[WHOLE FOODS MARKET](https://www.wholefoodsmarket.co.uk/) — Backend / Golang Developer

July 2021 — October 2023 · 2.4 years

E-commerce platform with catalog, ordering, personalization, analytics, user services, and multiple external integrations.

Developed and optimized Go services for an e-commerce platform processing up to 1 million requests per day and approximately 1,200 RPS at peak load.
Implemented Redis cache-aside for product cards, filters, and frequently accessed catalog data, increasing service throughput by approximately 30%.
Optimized PostgreSQL access by rewriting heavy SQL queries, reducing JOIN complexity, removing N+1 queries, and lowering database load during peak traffic.
Reduced critical request-path latency by removing unnecessary synchronous service calls and simplifying hot-path data processing.
Stabilized integrations with Retail Rocket, KISSmetrics, and Symantec.cloud by adding timeouts, retries with backoff, fallback behavior, and dedicated integration metrics.

Technologies: Go, PostgreSQL, Redis, Elasticsearch, REST API, Docker, Kubernetes, Yandex Cloud, GitLab CI, Prometheus, Grafana, ELK

***
[OGILVY](https://www.ogilvy.com/) — Backend / Golang Developer

April 2020 — July 2021 · 1.4 years

Internal marketing and brand-management platform with event-driven microservices for brand data, reports, analytics, notifications, and external integrations.

Built and maintained Go microservices for a marketing platform serving approximately 20,000 MAU, around 150 RPS at peak load, and about 1 TB of operational data.
Reworked RabbitMQ message processing by replacing auto-ack with manual ack, adding retry queues, DLQ, and idempotent handlers to eliminate message loss under load.
Split hot queues by event type and rebalanced consumers, improving event-processing throughput by approximately 20%.
Fixed race conditions in concurrent event handlers using Go race detector, reduced shared mutable state, added targeted synchronization, and covered critical paths with tests.
Improved production debugging by adding structured logs and metrics for retry count, processing errors, and event-processing delays.

Technologies: Go, RabbitMQ, PostgreSQL, Redis, REST API, Docker, Kubernetes, Yandex Cloud, GitLab CI, Nginx

***
Education

ITMO University — St. Petersburg — Bachelor

2017 — 2021  
Information and Computer Science

ITMO University — St. Petersburg — Master

2021 — 2023  
Development and Maintenance of a High-Quality Software Product

***
Additional

Production experience with high-load APIs, financial transaction processing, asynchronous pipelines, and external API degradation.
Strong focus on reliability: idempotency, retries, DLQ, backpressure, circuit breakers, state consistency, and incident-driven improvements.
