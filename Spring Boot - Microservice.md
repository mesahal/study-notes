| Topic                          | Subtopic / Learning Item                                                                 | Status (To Do / Done) |
|--------------------------------|-------------------------------------------------------------------------------------------|-----------------------|
| Microservices Fundamentals     | What is Microservices Architecture                                                        |                       |
|                                | Monolith vs Microservices Comparison                                                      |                       |
|                                | Benefits & Challenges of Microservices                                                    |                       |
|                                | Service Boundaries & Domain-Driven Design (DDD)                                           |                       |
|                                | Hexagonal (Ports & Adapters) Architecture                                                 |                       |
|                                | Decomposition Strategies – Business Capability, Subdomain                                |                       |
|                                | Communication Patterns – Synchronous vs Asynchronous                                      |                       |
|                                | REST vs gRPC vs Messaging – Comparison                                                    |                       |
|                                | API Contracts & Documentation – OpenAPI / Swagger                                         |                       |
|                                | Versioning & Backward Compatibility                                                       |                       |
|                                | Microservices Security Basics – Authentication, Authorization, JWT                        |                       |
|                                | Twelve-Factor App Principles                                                              |                       |
|                                | Containerization Basics – Dockerizing Spring Boot apps                                    |                       |
|                                | Deployment Strategies – Blue-Green, Canary, Rolling Updates                               |                       |
|                                | Service Mesh Basics – Istio, Linkerd (concepts)                                           |                       |
|                                | Secrets Management – Vault, K8s Secrets                                                   |                       |
|                                | Resiliency Testing – Chaos Engineering Basics                                             |                       |
| Spring Boot Basics             | Introduction to Spring Framework & Spring Boot                                            |                       |
|                                | Project Setup with Spring Initializr                                                      |                       |
|                                | Understanding pom.xml / Gradle build                                                      |                       |
|                                | Dependency Injection in Spring                                                            |                       |
|                                | DI Exceptions (UnsatisfiedDependencyException, NoSuchBeanDefinitionException)             |                       |
|                                | Spring Boot Annotations Overview (@RestController, @Service, @Repository, @Primary, etc.) |                       |
|                                | Core Annotations – @Component, @Bean, @Configuration (breakdown)                          |                       |
|                                | Stereotype Annotations – @Service, @Repository (breakdown)                                |                       |
|                                | Conditional Annotations – @Profile, @ConditionalOnProperty (breakdown)                    |                       |
|                                | Web Annotations – @RequestMapping, @GetMapping, etc. (breakdown)                          |                       |
|                                | Creating Controllers & REST Endpoints                                                     |                       |
|                                | Request Mapping – GET, POST, PUT, DELETE                                                   |                       |
|                                | Path Variables vs Request Params                                                          |                       |
|                                | Service Layer in Spring Boot                                                              |                       |
|                                | Repository Layer with JPA                                                                 |                       |
|                                | JPA Advanced – Pagination, Sorting, Custom Queries                                        |                       |
|                                | Validation in Spring Boot – @Valid, Custom Validators                                     |                       |
|                                | File Upload & Download in REST APIs                                                       |                       |
|                                | Spring Boot Profiles – dev, test, prod                                                    |                       |
|                                | Configuration with application.yml / application.properties                               |                       |
| Spring Boot Advanced           | Exception Handling in Spring Boot (@ControllerAdvice)                                     |                       |
|                                | Global Exception Handling (breakdown)                                                     |                       |
|                                | Custom Exception Classes (breakdown)                                                      |                       |
|                                | Validation Exception Handling (breakdown)                                                 |                       |
|                                | Spring Profiles & Configuration Management                                                |                       |
|                                | Spring Boot Actuator – Monitoring Endpoints                                               |                       |
|                                | Externalized Configuration (application.properties / YAML)                                |                       |
|                                | Spring Boot DevTools – Hot Reload                                                         |                       |
|                                | Logging with SLF4J                                                                        |                       |
|                                | DTOs & ModelMapper                                                                        |                       |
|                                | Why DTOs are needed (breakdown)                                                           |                       |
|                                | Manual Mapping vs ModelMapper vs MapStruct (breakdown)                                    |                       |
|                                | Nested Object Mapping (breakdown)                                                         |                       |
|                                | Testing with JUnit + Mockito                                                              |                       |
|                                | Circular Dependency Detection & Resolution                                                |                       |
|                                | Custom Servlet Filters & Interceptors                                                     |                       |
|                                | AOP (Aspect-Oriented Programming)                                                         |                       |
|                                | Spring Boot Async – @Async, Thread Pools                                                  |                       |
|                                | Spring Boot Caching – @Cacheable, Redis Integration                                       |                       |
|                                | Health Checks – readiness & liveness probes                                               |                       |
|                                | Spring Boot GraphQL Basics                                                                |                       |
|                                | Spring Boot Integration with External APIs – RestTemplate, WebClient                      |                       |
| Spring Cloud Components        | Service Discovery with Eureka                                                             |                       |
|                                | Client-Side Load Balancing with Ribbon                                                    |                       |
|                                | API Gateway – Spring Cloud Gateway                                                        |                       |
|                                | API Gateway Filters – Global & Custom                                                     |                       |
|                                | Circuit Breaker – Resilience4j                                                            |                       |
|                                | Config Server – Centralized Configuration                                                 |                       |
|                                | Distributed Tracing Basics – Sleuth + Zipkin                                              |                       |
|                                | Spring Cloud Sleuth Advanced – Trace IDs, Span Propagation                                |                       |
|                                | Spring Cloud Bus – Event Propagation                                                      |                       |
|                                | Spring Security Basics – JWT Authentication                                               |                       |
|                                | Spring Security Filter Chain                                                              |                       |
|                                | Spring Cloud OAuth2 – Keycloak/Okta Integration                                           |                       |
| Inter-Service Communication    | RESTful APIs for Microservices                                                            |                       |
|                                | Feign Clients in Spring Cloud                                                             |                       |
|                                | Feign Advanced – Retry, Error Decoding                                                    |                       |
|                                | Asynchronous Messaging – RabbitMQ, Kafka                                                  |                       |
|                                | Event-Driven Architecture – Publish-Subscribe, Event Sourcing                             |                       |
|                                | gRPC & Protobuf Basics                                                                    |                       |
|                                | WebSockets in Microservices                                                               |                       |
| Data Management in Microservices | Database per Service Pattern                                                            |                       |
|                                | Shared Database Anti-Pattern                                                              |                       |
|                                | Distributed Transactions – SAGA Pattern, Two-Phase Commit                                |                       |
|                                | Saga – Choreography vs Orchestration (breakdown)                                          |                       |
|                                | Eventual Consistency                                                                      |                       |
|                                | CQRS Pattern (Command Query Responsibility Segregation)                                   |                       |
|                                | Caching Strategies – Redis, In-Memory Cache                                               |                       |
|                                | Database Migration Tools – Flyway / Liquibase                                             |                       |
|                                | Polyglot Persistence (SQL + NoSQL)                                                        |                       |
|                                | NoSQL Basics – MongoDB, Cassandra                                                         |                       |
|                                | Data Sharding & Partitioning Concepts                                                     |                       |
| Observability & Monitoring     | Logging – Structured Logging, Log Levels                                                  |                       |
|                                | Distributed Logging – Correlation IDs                                                     |                       |
|                                | Centralized Logging – ELK Stack (Elasticsearch, Logstash, Kibana)                         |                       |
|                                | Metrics & Monitoring – Prometheus, Grafana                                                |                       |
|                                | Spring Boot Micrometer – Metrics                                                          |                       |
|                                | Tracing Requests Across Services – Jaeger, Zipkin                                         |                       |
|                                | Alerts & Incident Management – PagerDuty, OpsGenie basics                                 |                       |
|                                | Error Tracking – Sentry / NewRelic                                                        |                       |
| Microservices Architecture     | Principles of Microservices                                                               |                       |
|                                | Monolith vs Microservices                                                                 |                       |
|                                | Service Decomposition Strategies                                                          |                       |
|                                | Inter-Service Communication – Synchronous vs Asynchronous                                |                       |
|                                | API Gateway Pattern                                                                       |                       |
|                                | Service Discovery & Registry – Eureka, Consul                                             |                       |
| Microservices Patterns         | Circuit Breaker, Retry, Bulkhead Patterns                                                 |                       |
|                                | Retry vs Fallback vs Timeout (breakdown)                                                  |                       |
|                                | Saga Pattern & Distributed Transactions                                                   |                       |
|                                | Idempotency & Event Sourcing                                                              |                       |
|                                | CQRS (Command Query Responsibility Segregation)                                           |                       |
|                                | Sidecar Pattern                                                                           |                       |
|                                | Backpressure & Flow Control                                                               |                       |
|                                | Observability Patterns for Microservices                                                  |                       |
