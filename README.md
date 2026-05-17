# EUNWHA PARK

Backend Software Engineer | Distributed Systems | Java/Spring | AWS/EKS

I build backend systems where correctness, scale, and operating cost matter. At Samsung Electronics, I work on high-traffic production platforms with a focus on database migration, IAM modernization, batch processing, and cloud-native infrastructure.

[LinkedIn](https://www.linkedin.com/in/eunhwa-park-20a286248) | [GitHub](https://github.com/eunhwa99) | [Blog](https://silver-programmer.tistory.com) | [Email](mailto:eun.h.engineer@gmail.com)

---

## Professional Focus

- Distributed backend systems with Java, Kotlin, Spring Boot, and production-grade data stores
- Large-scale database modernization across DynamoDB, Cassandra, and relational systems
- Cloud-native infrastructure on AWS, EKS, Kubernetes, Docker, Jenkins, and GitHub Actions
- Reliability-focused engineering: zero-downtime migration, data integrity, cost reduction, and incident recovery
- Agent-based engineering harnesses for production-code delivery, including branch hygiene, verification gates, review loops, and PR handoff

## Impact Highlights

- Led a zero-downtime migration of 78B+ rows and 50TB+ of data across 3 global regions, achieving 100% data integrity through dual write, shadow read, and per-user flag routing.
- Reduced database operating costs by 95%, saving $2M+ per year by replacing a legacy ClustrixDB architecture with DynamoDB and Cassandra.
- Redesigned a legacy relational schema into a DynamoDB single-table model, reducing critical-path database access from 4 calls to 1.
- Migrated write-heavy workloads to Cassandra at 18K+ QPS, reducing RDB write load by 50%, lock wait time by 68%, and infrastructure cost by $700K+ per year.
- Modernized a 10-year legacy IAM monolith into a DDD-based modular architecture, helping decouple 10+ downstream services and reduce potential PII exposure.
- Optimized batch processing for a 56M+ user platform, reducing runtime by up to 61% and eliminating critical production OOM failures.

## Agent-Based Harness Engineering

I am also interested in agent-based harness engineering: turning AI-agent workflows into repeatable delivery systems with scoped commits, validation gates, fresh review loops, and clean PR handoff. I have applied this approach to real production-code changes in a Spring Boot backend repository, keeping implementation, API documentation, verification, and review feedback separated and traceable.

## Core Stack

| Area | Technologies |
| --- | --- |
| Languages | Java, Kotlin, Python |
| Backend Architecture | Spring Boot, Hexagonal Architecture, DDD |
| Data Systems | DynamoDB, Cassandra, MySQL, Kafka, S3 |
| Cloud & DevOps | AWS, EKS, Kubernetes, Docker, Jenkins, GitHub Actions |
| Certification | AWS Certified Solutions Architect - Professional |

## Selected GitHub Work

Public repositories that show adjacent tooling and delivery interests.

### [MCPContentSearch](https://github.com/eunhwa99/MCPContentSearch)
MCP-based document indexing and search server for personal Notion and Tistory content, powered by LlamaIndex, ChromaDB, and a custom tool API.

`Python` `LlamaIndex` `ChromaDB` `FastMCP` `Notion API` `Asyncio`

### [ImageGallery](https://github.com/eunhwa99/ImageGallery)
React and Flask image application built to practice end-to-end CI/CD, container delivery, and Kubernetes deployment workflows.

`React` `Flask` `Docker` `Kubernetes` `Helm` `Jenkins` `GHCR`

### [Today-I-Learned](https://github.com/eunhwa99/Today-I-Learned)
Learning archive application with categorization features and a Kotlin/Spring backend.

`React` `Kotlin` `Spring Boot` `MongoDB`

## Open Source

### Apache Zeppelin

Awarded Grand Prize (1st place) in the Apache Zeppelin Open Source Contribution Program for impactful upstream contributions across code quality, reliability, and maintainability.

- [ZEPPELIN-6306](https://github.com/apache/zeppelin/pull/5069) Prevented NPE in `StaticRepl` with fail-fast JavaCompiler validation.
- [ZEPPELIN-6299](https://github.com/apache/zeppelin/pull/5048) Refactored `StaticRepl` for readability, correctness, and modern Java usage.
- [ZEPPELIN-6264](https://github.com/apache/zeppelin/pull/5005) Refactored `InfluxDBInterpreter` for maintainability.
- [ZEPPELIN-6242](https://github.com/apache/zeppelin/pull/4975) Improved `Neo4jConnectionManager` enum parsing and default handling.
- [ZEPPELIN-6220](https://github.com/apache/zeppelin/pull/4970), [ZEPPELIN-6243](https://github.com/apache/zeppelin/pull/4978), [ZEPPELIN-6285](https://github.com/apache/zeppelin/pull/5033), [ZEPPELIN-6300](https://github.com/apache/zeppelin/pull/5049) Additional cleanup and refactoring contributions merged upstream.

### Kubernetes Website

- [Kubernetes/website#52238](https://github.com/kubernetes/website/pull/52238) Synced Korean ingress-minikube documentation with the English version.
