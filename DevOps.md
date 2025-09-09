# DevOps Learning Sheet

| Topic | Subtopic / Learning Item | Status (To Do / Done) |
|-------|---------------------------|------------------------|
| **DevOps Fundamentals** | What is DevOps & Its Importance | |
|  | DevOps Culture & Principles | |
|  | CI/CD Overview | |
|  | DevOps vs DevSecOps | |
|  | DevOps Maturity Model | |
|  | Agile vs DevOps | |
|  | DevOps vs Traditional SDLC | |
|  | Infrastructure as Code (IaC) Basics | |
|  | IaC Tools Overview – Terraform, Ansible, Pulumi | |
|  | Configuration Management vs IaC | |
|  | DevOps Metrics & KPIs (Deployment Frequency, MTTR, Lead Time) | |
|  | DORA Metrics Deep Dive | |
|  | DevOps Toolchain Overview | |
|  | DevOps Team Structure & Roles | |
| **Version Control & Collaboration** | Git Basics – clone, add, commit, push, pull | |
|  | Branching Strategies – Feature, Release, Hotfix, Microservices-specific branching | |
|  | Merge vs Rebase | |
|  | Conflict Resolution Strategies | |
|  | Git Tagging, Stashing, Reset & Revert | |
|  | Code Review Practices & Pull Request Management | |
|  | Git Hooks & Automation | |
|  | Git Workflows – GitFlow, GitHub Flow, Trunk-Based Development | |
|  | Git LFS (Large File Storage) | |
|  | Git Submodules & Monorepo vs Polyrepo | |
|  | Advanced Git Commands (Bisect, Reflog, Cherry-pick) | |
|  | Git Security & Signed Commits | |
| **Build & Automation Tools** | Maven Basics – Project Structure, Dependency Management | |
|  | Gradle Basics – Build Scripts, Tasks, Plugins | |
|  | Ant Build Tool Basics | |
|  | npm/yarn for Node.js Projects | |
|  | Build Lifecycle – Clean, Compile, Test, Package, Install | |
|  | Multi-module Project Builds | |
|  | Using Plugins – Surefire, Shade, Jacoco | |
|  | Artifact Repositories – Nexus, Artifactory | |
|  | JFrog Artifactory Deep Dive | |
|  | Sonatype Nexus Configuration | |
|  | Build Caching & Incremental Builds | |
|  | Build Optimization Strategies | |
|  | Dependency Vulnerability Scanning | |
| **Continuous Integration (CI)** | CI Concepts & Benefits | |
|  | CI Tools Overview – Jenkins, GitHub Actions, GitLab CI, CircleCI | |
|  | Jenkins Pipeline as Code (Jenkinsfile) | |
|  | GitHub Actions Workflows & Marketplace | |
|  | GitLab CI/CD Configuration (.gitlab-ci.yml) | |
|  | Azure DevOps Pipelines | |
|  | TeamCity CI Configuration | |
|  | Bamboo CI Setup | |
|  | Setting Up CI Pipelines – Jobs, Stages, Runners | |
|  | Pipeline Templates & Reusable Workflows | |
|  | Automated Build, Test & Linting | |
|  | Static Code Analysis (SonarQube, CodeClimate) | |
|  | Code Quality Gates | |
|  | Running Unit & Integration Tests in CI | |
|  | Parallel Test Execution | |
|  | Test Result Reporting & Coverage | |
|  | Notifications & Reporting | |
|  | Slack/Teams Integration for CI Notifications | |
|  | CI Pipeline Best Practices | |
|  | Branch Protection Rules | |
|  | CI Performance Optimization | |
| **Continuous Deployment / Delivery (CD)** | CD Concepts & Deployment Strategies | |
|  | Deployment Patterns – Rolling, Blue-Green, Canary | |
|  | A/B Testing in Deployment | |
|  | Zero-Downtime Deployment Strategies | |
|  | Dockerizing Applications for CD | |
|  | Deploying Microservices to Kubernetes / Cloud | |
|  | ArgoCD for GitOps | |
|  | Flux for GitOps | |
|  | Spinnaker for Multi-Cloud CD | |
|  | Rollback Strategies & Versioning | |
|  | Database Migration in CD Pipelines | |
|  | CD Pipeline Best Practices | |
|  | Feature Flags & Dark Launches | |
|  | Progressive Delivery Techniques | |
|  | Deployment Validation & Smoke Tests | |
| **Cloud Computing Fundamentals** | What is Cloud Computing & Its Benefits | |
|  | Cloud Service Models – IaaS, PaaS, SaaS, FaaS | |
|  | Deployment Models – Public, Private, Hybrid, Multi-Cloud | |
|  | Cloud Providers Overview – AWS, Azure, GCP | |
|  | AWS Core Services Overview | |
|  | Azure Core Services Overview | |
|  | GCP Core Services Overview | |
|  | Key Cloud Concepts – Regions, Availability Zones, Availability Sets | |
|  | Cloud Networking Basics (VPC, Subnets, Security Groups) | |
|  | Cloud Storage Types (Object, Block, File) | |
|  | Cloud Cost Management Basics | |
|  | Cloud Cost Optimization Strategies | |
|  | Reserved Instances vs Spot Instances | |
|  | Cloud Migration Strategies (6 R's) | |
|  | Cloud Compliance & Governance | |
| **Infrastructure as Code (IaC)** | Terraform Fundamentals | |
|  | Terraform State Management | |
|  | Terraform Modules & Best Practices | |
|  | Terraform Cloud & Enterprise | |
|  | Ansible Playbooks & Roles | |
|  | Ansible Inventory Management | |
|  | Ansible Vault for Secrets | |
|  | Pulumi Multi-Language IaC | |
|  | CloudFormation (AWS) | |
|  | ARM Templates (Azure) | |
|  | Cloud Deployment Manager (GCP) | |
|  | IaC Testing & Validation | |
|  | IaC Security Scanning | |
| **Configuration Management** | Chef Configuration Management | |
|  | Puppet Configuration Management | |
|  | Salt (SaltStack) Basics | |
|  | Configuration Drift Detection | |
|  | Immutable Infrastructure vs Mutable | |
| **Virtualization & Containers** | Virtual Machines vs Containers | |
|  | Docker Basics – Images, Containers, Volumes, Networks | |
|  | Docker Image Optimization | |
|  | Multi-stage Docker Builds | |
|  | Docker Security Best Practices | |
|  | Docker Networking Deep Dive | |
|  | Docker Storage & Volume Management | |
|  | Docker Compose for Multi-Container Applications | |
|  | Docker Swarm Orchestration | |
|  | Container Lifecycle & Commands | |
|  | Benefits of Containerization | |
|  | Container Networking & Storage | |
|  | Image Optimization & Best Practices | |
|  | Container Registry Management | |
|  | Container Scanning & Vulnerability Assessment | |
|  | Buildah & Podman Alternatives | |
| **Kubernetes Basics** | Kubernetes Architecture – Master, Nodes, API Server, Scheduler | |
|  | Kubernetes Components Deep Dive | |
|  | etcd Cluster Management | |
|  | Pods, ReplicaSets, Deployments, StatefulSets | |
|  | Pod Lifecycle & Init Containers | |
|  | Services – ClusterIP, NodePort, LoadBalancer | |
|  | Kubernetes Service Discovery | |
|  | ConfigMaps & Secrets Management | |
|  | External Secrets Operator | |
|  | Namespaces & Resource Quotas | |
|  | RBAC (Role-Based Access Control) | |
|  | Labels & Selectors | |
|  | Kubernetes Networking Model | |
|  | Helm Basics – Charts, Templates, Values | |
|  | Helm Chart Development | |
|  | Helm Repository Management | |
|  | Kubernetes CLI (kubectl) & Dashboard | |
|  | kubectl Advanced Commands | |
|  | Kubernetes Context & Configuration | |
| **Kubernetes Advanced Concepts** | Horizontal Pod Autoscaler & Scaling Policies | |
|  | Vertical Pod Autoscaler (VPA) | |
|  | Cluster Autoscaler | |
|  | StatefulSets vs Deployments | |
|  | DaemonSets & Jobs | |
|  | CronJobs in Kubernetes | |
|  | Persistent Volumes & Persistent Volume Claims | |
|  | Storage Classes & Dynamic Provisioning | |
|  | CSI (Container Storage Interface) | |
|  | Ingress Controllers & Load Balancing | |
|  | NGINX Ingress Controller | |
|  | Traefik Ingress Controller | |
|  | Network Policies & Service Mesh Basics (Istio/Linkerd) | |
|  | Istio Service Mesh Deep Dive | |
|  | Linkerd Service Mesh | |
|  | Envoy Proxy Configuration | |
|  | Kubernetes Operators | |
|  | Custom Resource Definitions (CRDs) | |
|  | Operator Development with Kubebuilder | |
|  | Pod Disruption Budgets & Affinity Rules | |
|  | Node Affinity & Anti-Affinity | |
|  | Taints and Tolerations | |
|  | Kubernetes Security Policies | |
|  | Pod Security Standards | |
|  | Admission Controllers | |
| **Kubernetes Management & Operations** | Kubernetes Cluster Setup (kubeadm) | |
|  | Managed Kubernetes Services (EKS, AKS, GKE) | |
|  | Kubernetes Backup & Restore (Velero) | |
|  | Kubernetes Troubleshooting | |
|  | Kubernetes Resource Management | |
|  | Kubernetes Upgrade Strategies | |
|  | Multi-Cluster Management | |
| **Serverless & FaaS** | What is Serverless Architecture | |
|  | AWS Lambda / Azure Functions / GCP Functions Basics | |
|  | AWS Lambda Deep Dive | |
|  | Azure Functions Configuration | |
|  | Google Cloud Functions Setup | |
|  | Event-Driven Serverless Applications | |
|  | Serverless Event Sources (S3, DynamoDB, EventBridge) | |
|  | API Gateway Integration | |
|  | AWS API Gateway Configuration | |
|  | Azure API Management | |
|  | Cold Start Problem & Optimizations | |
|  | Serverless Performance Optimization | |
|  | Monitoring Serverless Functions | |
|  | AWS CloudWatch for Lambda | |
|  | Azure Application Insights | |
|  | Serverless Frameworks & Best Practices | |
|  | Serverless Framework Deployment | |
|  | SAM (Serverless Application Model) | |
|  | Terraform for Serverless | |
| **Observability & Monitoring** | Distributed Logging & Correlation IDs | |
|  | Structured Logging Best Practices | |
|  | Log Aggregation Strategies | |
|  | Metrics Collection – Prometheus, Grafana | |
|  | Prometheus Configuration & Rules | |
|  | Grafana Dashboard Creation | |
|  | Custom Metrics & Exporters | |
|  | Distributed Tracing – Jaeger, Zipkin | |
|  | OpenTelemetry Integration | |
|  | Trace Analysis & Performance Bottlenecks | |
|  | Health Checks – Liveness & Readiness | |
|  | Kubernetes Health Probes | |
|  | Application Health Endpoints | |
|  | Alerting & Incident Management | |
|  | PagerDuty Integration | |
|  | Opsgenie Alerting | |
|  | Alert Fatigue Prevention | |
|  | Application Performance Monitoring (APM) Tools | |
|  | New Relic APM | |
|  | Datadog Monitoring | |
|  | AppDynamics Configuration | |
|  | Observability Best Practices | |
|  | SLI/SLO/SLA Definition | |
|  | Error Budget Management | |
| **Logging & Monitoring** | Importance of Observability | |
|  | Structured Logging & Log Levels | |
|  | Centralized Logging – ELK Stack (Elasticsearch, Logstash, Kibana) | |
|  | Elasticsearch Configuration & Optimization | |
|  | Logstash Pipeline Configuration | |
|  | Kibana Dashboard & Visualization | |
|  | ELK Stack Security | |
|  | Fluentd vs Logstash Comparison | |
|  | Fluent Bit for Edge Logging | |
|  | Metrics Collection – Prometheus | |
|  | Prometheus Federation | |
|  | Prometheus High Availability | |
|  | Visualization – Grafana Dashboards | |
|  | Grafana Alerting Rules | |
|  | Grafana Plugin Development | |
|  | Tracing Requests Across Services – Jaeger, Zipkin | |
|  | Jaeger Deployment & Configuration | |
|  | Zipkin Setup & Integration | |
|  | Alerts & Incident Response | |
|  | Incident Response Procedures | |
|  | Postmortem & Blameless Culture | |
|  | Logging Best Practices & Correlation Techniques | |
|  | Log Retention & Compliance | |
| **Security in Cloud & Microservices** | Authentication & Authorization – OAuth2, JWT, OpenID Connect | |
|  | OAuth2 Flow Types | |
|  | JWT Best Practices & Security | |
|  | OpenID Connect Implementation | |
|  | Securing API Gateway & Microservices | |
|  | API Security Best Practices | |
|  | Rate Limiting & DDoS Protection | |
|  | Secrets Management – Vault, Kubernetes Secrets | |
|  | HashiCorp Vault Configuration | |
|  | AWS Secrets Manager | |
|  | Azure Key Vault | |
|  | External Secrets Operator for K8s | |
|  | TLS/SSL & Secure Communication | |
|  | Certificate Management (cert-manager) | |
|  | mTLS (Mutual TLS) Implementation | |
|  | Network Segmentation & Firewalls | |
|  | Zero Trust Network Architecture | |
|  | Network Policies in Kubernetes | |
|  | Rate Limiting & Throttling | |
|  | API Rate Limiting Strategies | |
|  | Circuit Breaker Implementation | |
|  | Secure CI/CD Pipelines | |
|  | SAST (Static Application Security Testing) | |
|  | DAST (Dynamic Application Security Testing) | |
|  | Dependency Scanning in Pipelines | |
|  | Container Image Scanning | |
|  | Infrastructure Security Scanning | |
|  | Security Best Practices for Cloud & Microservices | |
|  | DevSecOps Integration | |
|  | Compliance as Code | |
|  | Security Policy Enforcement | |
| **Cloud-Native Best Practices** | 12-Factor App Principles | |
|  | Each 12-Factor Principle Breakdown → Codebase, Dependencies, Config | |
|  | → Backing Services, Build/Release/Run | |
|  | → Processes, Port Binding | |
|  | → Concurrency, Disposability | |
|  | → Dev/Prod Parity, Logs | |
|  | → Admin Processes | |
|  | Stateless vs Stateful Services | |
|  | Designing Stateless Applications | |
|  | Managing State in Microservices | |
|  | Externalized Configuration & Environment Variables | |
|  | Configuration Management Patterns | |
|  | Secret Configuration Injection | |
|  | CI/CD Pipelines for Cloud-Native Applications | |
|  | GitOps Workflow Implementation | |
|  | Multi-Environment Promotion | |
|  | Autoscaling & Resource Optimization | |
|  | Horizontal vs Vertical Scaling | |
|  | Cost Optimization in Cloud-Native Apps | |
|  | Observability & Monitoring Best Practices | |
|  | Three Pillars of Observability | |
|  | Observability-Driven Development | |
|  | Service Discovery & API Gateway | |
|  | Service Mesh vs API Gateway | |
|  | Service Registry Patterns | |
|  | Microservices Patterns – Circuit Breaker, Bulkhead, Retry | |
|  | Saga Pattern for Distributed Transactions | |
|  | Event Sourcing Pattern | |
|  | CQRS Pattern Implementation | |
|  | Scaling Strategies & Cloud Autoscaling | |
|  | Reactive Scaling Strategies | |
|  | Predictive Scaling | |
|  | Sidecar Pattern | |
|  | Sidecar vs Init Container | |
|  | Ambassador Pattern | |
|  | Backpressure & Flow Control | |
|  | Load Shedding Techniques | |
|  | Bulkhead Pattern Implementation | |
| **Testing & Quality Assurance in DevOps** | Automated Unit & Integration Testing | |
|  | Test Pyramid Strategy | |
|  | Mocking & Stubbing in Tests | |
|  | Code Coverage & Quality Metrics | |
|  | Code Quality Metrics (Cyclomatic Complexity, Tech Debt) | |
|  | Test Coverage Analysis | |
|  | Performance Testing & Load Testing | |
|  | JMeter Load Testing | |
|  | k6 Performance Testing | |
|  | Artillery.io Load Testing | |
|  | Performance Test Automation | |
|  | Chaos Engineering Basics | |
|  | Chaos Monkey Implementation | |
|  | Gremlin Chaos Engineering | |
|  | Litmus Chaos Engineering for K8s | |
|  | Chaos Testing Strategies | |
|  | Continuous Feedback Loops | |
|  | User Feedback Integration | |
|  | A/B Testing in Production | |
|  | CQRS (Command Query Responsibility Segregation) | |
|  | Event Sourcing with CQRS | |
|  | CQRS Implementation Patterns | |
|  | Contract Testing & API Testing | |
|  | Pact Contract Testing | |
|  | Postman API Testing | |
|  | REST Assured Testing | |
|  | GraphQL Testing Strategies | |
|  | Observability-driven Testing | |
|  | Testing in Production Strategies | |
|  | Canary Testing | |
|  | Feature Flag Testing | |
| **Site Reliability Engineering (SRE)** | SRE Principles & Practices | |
|  | SRE vs DevOps Comparison | |
|  | Error Budget & SLO Management | |
|  | Toil Reduction Strategies | |
|  | Incident Management & Postmortems | |
|  | On-call & Escalation Procedures | |
|  | Reliability Engineering Practices | |
| **Platform Engineering** | Platform as a Product Approach | |
|  | Developer Self-Service Platforms | |
|  | Internal Developer Platform (IDP) | |
|  | Platform Abstraction Layers | |
|  | Developer Experience (DX) Optimization | |
| **API Management** | API Design & Documentation | |
|  | API Versioning Strategies | |
|  | API Testing & Validation | |
|  | API Gateway Patterns | |
|  | GraphQL vs REST API Management | |
| **Data Management in DevOps** | Database DevOps (DatabaseOps) | |
|  | Database Migration Automation | |
|  | Database Testing Strategies | |
|  | Data Pipeline Automation | |
|  | Backup & Recovery Automation | |
