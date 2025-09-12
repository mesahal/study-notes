# What is DevOps & Its Importance

## Definition
DevOps = Development + Operations + Culture + Automation
- Cultural movement bridging Dev and Ops teams
- Enables faster, more reliable software delivery
- Focus on collaboration, automation, and continuous feedback

## Key Principles
1. **Collaboration** - Break down silos between teams
2. **Automation** - Automate repetitive tasks
3. **CI/CD** - Continuous integration and deployment
4. **Monitoring** - Continuous monitoring and feedback
5. **Shared Responsibility** - Everyone owns the pipeline

## Why Important?
- **Speed**: Deploy in hours/days vs weeks/months
- **Quality**: 67% improvement in application quality
- **Cost**: 50-60% reduction in operational costs
- **Reliability**: Automated rollbacks and monitoring
- **Innovation**: More time for features vs firefighting

## DevOps Lifecycle
Code → Build → Test → Deploy → Monitor → Feedback

## Key Tools
- **Version Control**: Git, GitHub
- **CI/CD**: Jenkins, GitHub Actions
- **Infrastructure**: Terraform, Ansible
- **Containers**: Docker, Kubernetes
- **Monitoring**: Prometheus, Grafana

# DevOps Culture & Principles

## Culture Definition
DevOps culture = Mindset + Practices + Tools
- **Collaborative mindset** between Dev and Ops teams
- **Shared ownership** of entire software lifecycle
- **Continuous learning** and improvement culture

## Core Principles
1. **Collaboration** - Break down silos, work together
2. **Shared Responsibility** - Everyone owns the pipeline
3. **Continuous Learning** - Learn from failures, improve
4. **Automation First** - Automate repetitive tasks
5. **Customer Focus** - Deliver value continuously

## Key Practices
- **Blameless Postmortems** - Focus on "what/why", not "who"
- **Cross-Functional Teams** - Dev and Ops work together
- **Fail Fast, Learn Fast** - Small changes, quick feedback
- **Transparency** - Open communication and visibility

## Success Metrics
- **Deployment Frequency** - How often you deploy
- **Lead Time** - Time from code to production
- **MTTR** - Mean Time to Recovery
- **Change Failure Rate** - Percentage of failed changes

# CI/CD Overview

## Definition
**CI (Continuous Integration)** = Frequent code integration and automated testing
**CD (Continuous Deployment/Delivery)** = Automated deployment to production

## CI Process
1. **Code Commit** - Developer pushes code to repository
2. **Build** - Compile and package the application
3. **Test** - Run automated tests (unit, integration, etc.)
4. **Quality Gates** - Check code quality and security
5. **Artifact** - Create deployable package

## CD Process
1. **Deploy to Staging** - Test in production-like environment
2. **Integration Tests** - Run end-to-end tests
3. **Deploy to Production** - Automated deployment
4. **Monitor** - Track application health and performance

## Key Benefits
- **Faster Releases** - Deploy multiple times per day
- **Higher Quality** - Catch bugs early with automated testing
- **Reduced Risk** - Small, frequent changes are safer
- **Faster Feedback** - Quick identification of issues
- **Automation** - Less manual work, fewer human errors

## CI/CD Pipeline Stages
```
Code → Build → Test → Package → Deploy → Monitor
  ↑                                    ↓
  ←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←←
```

## Popular CI/CD Tools
- **Jenkins** - Open source, highly customizable
- **GitHub Actions** - Native GitHub integration
- **GitLab CI** - Built into GitLab platform
- **Azure DevOps** - Microsoft's solution
- **CircleCI** - Cloud-based CI/CD
- **TeamCity** - JetBrains CI/CD tool

## Best Practices
- **Automate Everything** - Build, test, deploy automatically
- **Fast Feedback** - Keep pipeline execution time short
- **Quality Gates** - Don't deploy if tests fail
- **Version Control** - Store pipeline code in Git
- **Monitor & Alert** - Track pipeline health and failures

# DevOps vs DevSecOps

## Definition
**DevOps** = Development + Operations (focus on speed and collaboration)
**DevSecOps** = Development + Security + Operations (integrates security throughout)

## Key Differences

| Aspect | DevOps | DevSecOps |
|--------|--------|-----------|
| **Focus** | Speed, collaboration, automation | Security + speed + collaboration |
| **Security** | Added later in pipeline | Built-in from the start |
| **Approach** | "Shift left" for speed | "Shift left" for security |
| **Tools** | CI/CD, monitoring, automation | Security scanning, compliance, threat detection |
| **Culture** | Dev + Ops collaboration | Dev + Sec + Ops collaboration |

## DevSecOps Benefits
- **Security by Design** - Security built into every stage
- **Early Detection** - Catch security issues early
- **Compliance** - Meet regulatory requirements
- **Risk Reduction** - Lower security risks
- **Cost Effective** - Fix issues early vs. late

## Security Integration Points
1. **Code** - Static security analysis (SAST)
2. **Dependencies** - Vulnerability scanning
3. **Build** - Security testing in CI/CD
4. **Deploy** - Runtime security monitoring
5. **Operate** - Continuous security monitoring

## DevSecOps Practices
- **Security as Code** - Define security policies in code
- **Automated Security Testing** - Run security tests in CI/CD
- **Threat Modeling** - Identify security threats early
- **Security Training** - Educate teams on security
- **Compliance Automation** - Automate compliance checks

## Common DevSecOps Tools
- **SAST** - SonarQube, Checkmarx, Veracode
- **DAST** - OWASP ZAP, Burp Suite
- **Dependency Scanning** - Snyk, WhiteSource
- **Container Security** - Twistlock, Aqua Security
- **Secrets Management** - HashiCorp Vault, AWS Secrets Manager

---

# Virtual Machines vs. Containers: Key Differences and Benefits

## Traditional Virtual Machines (VMs)

### Before Cloud Computing:
- Organizations bought their own hardware and installed an operating system (OS) to create a server.
- Web applications were deployed via web/app servers with a public IP assigned.
- The domain name was mapped to the public IP for accessibility.

### Cloud Computing & Virtual Machines:
- Instead of physical servers, organizations now use virtual machines (VMs) from cloud providers like AWS, Azure, or GCP.
- Cloud providers use hypervisors to divide physical servers into multiple VMs (e.g., VM1, VM2, VM3).
- Each VM gets its own guest OS, which can be different (Windows, Linux, Mac, etc.).

### Challenges with Virtual Machines in Microservices:
- Each microservice (e.g., AccountService, LoanService, CardService) needs separate dependencies installed manually.
- If there are 100 microservices, creating 100 VMs is costly and complex.
- Deploying multiple services on one VM causes compatibility issues (e.g., different Java versions for different microservices).
- Restarting a VM brings down all hosted microservices.
- Scaling issues: Creating new VMs, installing OS, and setting up dependencies takes 15+ minutes—too slow for real-time scalability.

## Containers (Docker) - The Better Alternative

### How Containers Work:
- Uses container engine (Docker) instead of hypervisors.
- No need for a guest OS—containers share the host OS, making them lightweight.
- Containers can be created, restarted, or destroyed in seconds.

### Key Benefits of Containers over VMs:
- **Efficiency**: No separate OS means reduced resource usage.
- **Faster Deployment**: Containers package all dependencies, avoiding manual setup in new environments.
- **Portability**: The same container can run on any system without reconfiguration.
- **Isolation**: Each container has its own virtual environment and network (Java 8 in one, Java 17 in another).
- **Scalability**: Scaling up/down microservices is instantaneous, unlike VMs which take minutes.

### Overall Takeaway:
- VMs are resource-heavy, slow, and complex for microservices deployment.
- Containers (Docker) are lightweight, fast, portable, and efficient.
- **Conclusion**: Say NO to VMs and YES to containerization for microservices.

# Containers and Docker - Key Notes

## Why Learn Containers and Docker?
- Essential for microservice developers.
- Common interview questions revolve around containers, Docker, and Kubernetes.
- Helps in deploying microservices efficiently.

## What is a Container?
- A loosely isolated environment within a server, virtual machine, or local system.
- Used to deploy microservices with all dependencies included.
- Ensures quick and reliable execution across different environments.
- Avoids manual dependency installation—everything is inside the container.

## Where do containers live?
- **Container Repository**
  - Private Repository
  - Public repository for Docker - DockerHub

## Container Image vs. Container
- **Container Image** → Blueprint (like a Java class).
- **Container** → Running instance (like an object in Java).
- Multiple containers can be created from a single image.

## What is Software Containerization?
- A method of OS-level virtualization to run multiple containers on the same machine.
- Containers feel like they have their own OS, but share the host OS kernel.

### Difference from Virtual Machines (VMs):
- VMs virtualize hardware (each has its own OS).
- Containers virtualize the OS (share the same OS kernel).

## What is Docker?
- An open-source platform that implements containerization.
- A tool to package applications with all their dependencies and configuration into a single, portable artifact called a container.
- Containers are isolated environments, making them portable and easy to share between teams (dev and ops).
- Converts application code into Docker images and runs them as containers.
- Enables automation of deployment, scaling, and management of applications.

# Container Repository (Registry)

A storage for container images.

- **Docker Hub** is the public repository with over 100k official and community images (e.g., nginx, redis, postgres).
- Companies use private repositories (e.g., AWS ECR, Nexus) to store their own images securely.

## Benefits: Development
- **Before Containers**: Developers had to manually install and configure each service (e.g., PostgreSQL, Redis) directly on their OS. This was error-prone, OS-dependent, and tedious for complex apps with many services.
- **With Containers**: Developers simply run `docker run` commands to download and start pre-configured services. The process is identical across all operating systems and avoids conflicts between versions.

## Benefits: Deployment
- **Before Containers**: Devs handed artifacts and instructions to Ops, who manually configured servers. This often led to miscommunication and "it works on my machine" problems.
- **With Containers**: Devs and Ops collaborate to package everything into a container. Deployment is simplified to running a `docker run` command on a server with Docker installed. The environment is consistent and defined by the image.

## Container vs. Image (Technical)
- **Image**: The immutable artifact or package (e.g., postgres:9.6). It's a stack of read-only layers (base OS, application, config).
- **Container**: A runtime instance of an image. When you `docker run` an image, it becomes a running container with its own isolated filesystem, environment, and processes.

## Docker vs. Virtual Machine (VM)

### Virtualization Layer:
- **VM**: Virtualizes the entire OS (kernel + apps). Needs its own OS kernel, leading to large sizes (GBs) and slower startup.
- **Docker**: Virtualizes only the application layer. It shares the host OS kernel, leading to small sizes (MBs) and fast startup.

### Compatibility:
- VMs can run any OS on any host.
- Docker requires the host kernel to be compatible with the container's base image (e.g., Linux containers can't run natively on older Windows/Mac without a Linux VM layer via Docker Toolbox).

# How Containers Work Internally?

- Containers share the same OS kernel, unlike VMs.

## Key Linux Features for Isolation:
- **Namespaces**:
  - Provide isolated environments for processes, networks, and storage.
  - Ensures containers cannot interfere with each other.
- **cGroups (Control Groups)**:
  - Manage and limit resource allocation (CPU, memory, network).
  - Prevents one container from monopolizing system resources.

## How Does Docker Work on Windows & macOS?
- Docker runs natively on Linux.
- On Windows/macOS:
  - Docker Client runs on the OS (e.g., Windows, macOS).
  - Docker Server runs inside a lightweight Linux VM.
  - This ensures uniform behavior across all operating systems.
- You can check the difference using `docker version` command.

# Docker Architecture and Key Components

Docker consists of three key components:

## Docker Client
The Docker client interacts with the Docker server to containerize applications.

There are two ways to issue commands to the Docker server:
- **Docker CLI** (most commonly used) – Commands are issued through the command line.
- **Docker Remote API** – Commands are issued programmatically via API requests.

This course will focus on the Docker CLI approach.

## Docker Server (Docker Host)
Runs the Docker daemon, which continuously listens for client commands.

Processes commands such as:
- Building a Docker Image from an application (Spring Boot, Maven, Microservices, etc.).
- Running a Docker Container from a Docker image.

- **Docker Image**: A packaged version of the application with all dependencies and configurations.
- **Docker Container**: A running instance of a Docker image, hosting the application or microservice.
- Containers expose APIs and business logic, accessible via an endpoint (port + API path).
- All images and containers are stored inside the Docker server.

## Docker Registry
Stores and distributes Docker images remotely.

- **Docker Hub**: The official public registry by Docker.
- Other private registries include GitHub, AWS, GCP, and Azure.
- Organizations typically use private registries for secure image storage and deployment.
- Docker images can be pushed from local storage to remote repositories for further deployment.

# Docker Workflow

1. The Docker client sends an instruction (e.g., "Run a container from an image") to the Docker server.
2. The Docker server checks if the required Docker image is available locally.
3. If the image is not available, it is pulled from a remote registry (e.g., Docker Hub).
4. The Docker server then creates a container from the image, launching the application.
5. Once the container is running, the application is accessible.

## Benefits of Using Docker

- Simplifies installation and setup for applications like MySQL.
- Instead of manually installing software, users can pull a Docker image and run a container instantly.
- Makes development, testing, and deployment faster and more efficient.

# Docker Image Generating Ways

Converting a microservice into a Docker image makes it lightweight, portable, and scalable for deployment. There are three common approaches to containerizing a Spring Boot application:

## 1. Dockerfile Approach (Traditional & Basic)
- Requires writing a Dockerfile containing instructions for building the Docker image.
- The Docker server follows these instructions to generate an image.
- It has a learning curve as it involves understanding Docker syntax and best practices.
- **Example Usage**: Generating a Docker image for the Accounts Microservice.

## 2. Buildpacks Approach (Simplified)
- No need to write a Dockerfile or manually provide build instructions.
- A single Maven command generates the Docker image using Buildpacks.
- Buildpacks was developed by Heroku & Pivotal, leveraging best practices for containerization.
- **Example Usage**: Generating a Docker image for the Loans Microservice.

## 3. Google Jib Approach (Automated)
- A Google-developed open-source tool that uses a Maven plugin to generate a Docker image.
- No need to write a Dockerfile, making it an easy and efficient alternative.
- **Example Usage**: Generating a Docker image for the Cards Microservice.

Each approach has its advantages and disadvantages.

---
