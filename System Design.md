# System Design Fundamentals Learning Sheet

| Topic | Subtopic / Learning Item | Status (To Do / Done) |
|-------|--------------------------|----------------------|
| **System Design Fundamentals** | What is System Design & Importance | |
|  | High-Level Design vs Low-Level Design | |
|  | Components of a System: Client, Server, Database, Cache, Load Balancer | |
|  | System Design Interview Process | |
|  | System Design Documentation | |
|  | Understanding Functional Requirements (Performance, Scalability, Reliability, Security) | |
|  | Understanding Non-Functional Requirements (Latency, Throughput, Availability, Fault Tolerance) | |
|  | Trade-offs in System Design (Consistency vs Availability vs Partition Tolerance) | |
|  | Capacity Planning Basics (CPU, Memory, Disk, Network considerations) | |
|  | SLA vs System Design Alignment | |
| **Requirements Gathering & Estimation** | Gathering Requirements from Stakeholders | |
|  | Estimating Traffic & Load (QPS, RPS, Peak vs Average Load) | |
|  | Understanding Storage & Data Requirements | |
|  | Bottleneck Identification & Hotspots | |
|  | SLA, SLO, SLI Definitions | |
|  | Estimating Concurrency & User Behavior Models | |
|  | Back-of-the-Envelope Calculations (Quick Estimations) | |
| **Scalability & Load Handling** | Vertical vs Horizontal Scaling | |
|  | Database Sharding & Partitioning | |
|  | Data Replication Strategies: Master-Slave, Multi-Master, Leaderless | |
|  | Cache Design: Local vs Distributed, Write-Through, Write-Back, Expiration Strategies | |
|  | Load Balancing Strategies: Round Robin, Least Connections, IP Hash | |
|  | CDN (Content Delivery Network) Basics | |
|  | Auto-Scaling (Reactive vs Predictive) | |
|  | Queue-Based Load Leveling | |
| **High Availability & Fault Tolerance** | Redundancy & Failover Mechanisms | |
|  | Hot, Warm, Cold Standby | |
|  | Disaster Recovery Planning & RTO/RPO | |
|  | Heartbeat & Health Checks | |
|  | Graceful Degradation Strategies | |
|  | Chaos Engineering Basics (Fault Injection, Netflix Chaos Monkey) | |
| **Databases & Storage Patterns** | SQL vs NoSQL Databases | |
|  | When to Use Relational vs Non-Relational DB | |
|  | CAP Theorem in Practice | |
|  | Data Indexing & Query Optimization | |
|  | Transaction Management & Isolation Levels | |
|  | Event Sourcing & CQRS Patterns | |
|  | Multi-Tenancy & Partitioned Databases | |
|  | OLTP vs OLAP Systems | |
|  | Database Caching Layers (Query Cache, Materialized Views) | |
| **Messaging & Event-Driven Systems** | Message Queue vs Pub/Sub | |
|  | Event-Driven Architecture | |
|  | Kafka Basics: Topics, Partitions, Producers, Consumers, Offsets | |
|  | RabbitMQ Basics: Exchanges, Queues, Bindings | |
|  | Ordering Guarantees & Delivery Semantics (At Least Once, At Most Once, Exactly Once) | |
|  | Asynchronous Processing & Worker Queues | |
|  | Dead Letter Queues | |
|  | Stream Processing Basics (Apache Flink, Spark Streaming) | |
| **Microservices Design Patterns** | API Gateway Pattern | |
|  | Service Registry & Discovery (Eureka, Consul) | |
|  | Circuit Breaker Pattern | |
|  | Retry & Bulkhead Patterns | |
|  | Saga Pattern for Distributed Transactions | |
|  | Idempotency & Data Consistency | |
|  | Versioning of APIs | |
|  | Sidecar Pattern | |
|  | Strangler Fig Pattern (Legacy to Microservices Migration) | |
|  | Service Mesh Basics (Istio, Linkerd) | |
| **Caching & Performance Optimization** | Cache Aside vs Read-Through vs Write-Through | |
|  | In-Memory Caches: Redis, Memcached | |
|  | TTL (Time-To-Live) Strategies | |
|  | Cache Eviction Policies: LRU, LFU, FIFO | |
|  | Query Optimization & Indexing | |
|  | CDN Cache Strategies (Edge Caching, Cache Invalidation) | |
| **Security in System Design** | Authentication & Authorization (OAuth2, JWT) | |
|  | Rate Limiting & Throttling | |
|  | Data Encryption at Rest & In Transit | |
|  | API Security Best Practices | |
|  | Network Segmentation & Firewalls | |
|  | Secrets Management (Vault, AWS KMS) | |
|  | Zero Trust Architecture Basics | |
| **Monitoring, Logging & Observability** | Logging: Centralized Logging, Correlation IDs | |
|  | Metrics: Latency, Error Rate, Throughput | |
|  | Distributed Tracing: Jaeger, Zipkin | |
|  | Alerting & Incident Response | |
|  | Performance Profiling & Bottleneck Detection | |
|  | Dashboarding & Visualization (Grafana, Kibana) | |
| **Real-World System Design Case Studies** | Designing a URL Shortener | |
|  | URL Shortener – Database Design & Scaling | |
|  | Designing a Social Media Feed | |
|  | Social Media Feed – Timeline & Recommendation | |
|  | Designing a Messaging System (WhatsApp/Slack) | |
|  | Messaging System – Real-time & Persistence | |
|  | Designing an E-Commerce Platform | |
|  | E-Commerce Platform – Inventory & Payment | |
|  | Designing a Video Streaming Service | |
|  | Video Streaming – CDN & Encoding | |
|  | Designing a Real-Time Analytics Platform | |
|  | Real-Time Analytics – Data Pipeline | |
|  | Designing a Ride-Sharing App (Uber, Lyft) | |
|  | Ride-Sharing – Matching & Tracking | |
|  | Designing Online Payment Systems (PayPal, Stripe) | |
|  | Payment Systems – Security & Compliance | |
| **Distributed Systems Fundamentals** | Definition & Characteristics of Distributed Systems | |
|  | Monolithic vs Distributed Systems | |
|  | Key Challenges: Latency, Partial Failure, Concurrency, Data Consistency | |
|  | Types of Distributed Systems: Client-Server, Peer-to-Peer, Event-Driven | |
|  | Clock Synchronization & Time in Distributed Systems (NTP, Lamport Clocks) | |
| **Communication in Distributed Systems** | Synchronous vs Asynchronous Communication | |
|  | RPC (Remote Procedure Call) Basics | |
|  | REST APIs & gRPC Communication | |
|  | Messaging Protocols: AMQP, MQTT, Apache Thrift | |
|  | Message Queues & Pub/Sub Pattern | |
|  | WebSockets & Real-Time Communication | |
| **Consistency & Reliability** | ACID vs BASE | |
|  | CAP Theorem (Consistency, Availability, Partition Tolerance) | |
|  | PACELC Theorem | |
|  | Eventual Consistency & Causal Consistency | |
|  | Idempotency & Retry Mechanisms | |
|  | Strong vs Weak Consistency Models | |
| **Data Management & Storage** | Database per Service Pattern | |
|  | Shared Database Anti-Pattern | |
|  | Data Replication: Single Leader, Multi-Leader, Leaderless | |
|  | Sharding & Partitioning | |
|  | Caching Strategies: Local Cache, Distributed Cache (Redis, Memcached) | |
|  | Handling Money & Critical Data | |
|  | Data Lifecycle Management (Cold, Warm, Hot Storage) | |
| **Transactions in Distributed Systems** | Distributed Transactions Basics | |
|  | Two-Phase Commit (2PC) | |
|  | Saga Pattern | |
|  | Outbox Pattern | |
|  | Event Sourcing & CQRS | |
|  | TCC (Try-Confirm-Cancel) Transactions | |
| **Scalability & High Availability** | Horizontal vs Vertical Scaling | |
|  | Load Balancing: L4, L7, Round Robin, Least Connection | |
|  | Failover Strategies | |
|  | Clustering & Replication | |
|  | CAP & Trade-offs in Scaling | |
|  | Multi-Region Deployments & Geo-Replication | |
| **Resiliency & Fault Tolerance** | Circuit Breaker Pattern (Resilience4j, Hystrix) | |
|  | Bulkhead Pattern | |
|  | Retry & Backoff Strategies | |
|  | Rate Limiting & Throttling | |
|  | Monitoring Upstream & Downstream Services | |
|  | Timeout & Fallback Strategies | |
| **Distributed System Patterns** | Leader Election: Paxos, Raft | |
|  | Event-Driven Architecture | |
|  | Publish-Subscribe Pattern | |
|  | Saga & CQRS Patterns | |
|  | Idempotent APIs & Deduplication | |
|  | Gossip Protocols (Cluster Membership, Failure Detection) | |
| **Observability & Monitoring** | Logging: Structured Logs, Correlation IDs | |
|  | Metrics Collection (Prometheus, Grafana) | |
|  | Distributed Tracing (Jaeger, Zipkin) | |
|  | Alerting & Incident Response | |
|  | Health Checks & Heartbeats | |
| **Security in Distributed Systems** | Authentication & Authorization (JWT, OAuth2, OpenID Connect) | |
|  | Secure Communication (TLS/SSL) | |
|  | API Gateway Security | |
|  | Rate Limiting & Throttling | |
|  | Data Encryption at Rest & In Transit | |
|  | Federation & Single Sign-On (SSO) | |
| **Advanced System Design & Scalability** | Designing Systems for Millions of Users | |
|  | Load Balancing Strategies (L4, L7, Weighted, Least Connections) | |
|  | Caching Strategies (Local, Distributed, Write-Through, Write-Back) | |
|  | Database Sharding & Partitioning | |
|  | Data Replication & Multi-Region Architecture | |
|  | Event-Driven Architecture for Scalability | |
|  | Distributed Systems Design Patterns (Leader Election, Circuit Breaker, CQRS, SAGA) | |
|  | Designing for Fault Tolerance, High Availability & Disaster Recovery | |
|  | Real-World High-Level System Design Case Studies (Google Maps, YouTube, WhatsApp) | |
|  | Multi-Tenant SaaS Architecture | |
|  | Edge Computing & IoT Considerations | |
| **Domain-Specific Knowledge (DDD)** | Introduction to Domain-Driven Design (DDD) | |
|  | Ubiquitous Language & Bounded Contexts | |
|  | Aggregates, Entities, Value Objects, Repositories | |
|  | Strategic Design Patterns in DDD | |
|  | Context Mapping & Integration Patterns | |
|  | Industry-Specific Use Cases: FinTech & Payments (Transaction Processing, Security, Compliance) | |
|  | Industry-Specific Use Cases: E-Commerce (Catalog Management, Inventory, Order Processing) | |
|  | Industry-Specific Use Cases: Healthcare (Patient Records, Data Privacy, HIPAA Compliance) | |
|  | Applying DDD in Spring Boot Microservices | |
|  | Event Storming Workshop Methodology | |
|  | DDD Anti-Patterns (Anemic Domain Model, Big Ball of Mud) | |
