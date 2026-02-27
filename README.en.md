<div align="center">
  <h1>Hi 👋, I'm Orange (ChengZi)</h1>
  <span><a href="./README.md">Chinese</a> | English</span>
  <h3 align="center">DevOps & SRE Engineer focused on cloud-native, automation, and full-stack practices</h3>
</div>

---

### Clear Boundaries, Orderly Operations
- **Clear Boundaries**: Operations work should be clear and unambiguous, with distinct responsibility boundaries, avoiding gray areas
- **Orderly Operations**: Establish a standardized and process-driven operations system, ensuring operations work is traceable and rule-based

---

🔭 **Current Core Project**: I'm fully committed to open-sourcing the **Zebra Ops Platform** ([ZebraOps](https://github.com/ZebraOps)) — a modern management platform dedicated to enhancing operations efficiency and system stability.

🌱 **Continuous Exploration**: Deep diving into cutting-edge practices in eBPF, OTel, Service Mesh observability, and AIOps.

👯 **Looking to Collaborate**: Seeking partners with the same passion for operations tools, cloud-native middleware, or DevOps integrated platforms.

📫 **How to Reach Me**: iamnumachen@gmail.com

⚡ **Personal Philosophy**: I believe "laziness" is an engineer's virtue, so I'm passionate about using automation and intelligent systems to eliminate all repetitive work.

## 🛠️ Tech Stack

### Frontend Technologies
- Frameworks: Vue2 / Vue3 + Element UI / Ant Design Vue
- State Management: Pinia / Vuex
- Build Tools: Vite / Webpack

### Backend Technologies
- Languages: Go, Python, TypeScript
- Frameworks: Go-zero, Gin, FastAPI, Django, Flask
- Databases: PostgreSQL, MySQL, Redis
- ORM: GORM, SQLAlchemy

### Cloud-Native & Infrastructure
- Containerization: Docker, Kubernetes
- Service Mesh: Istio, Linkerd
- Configuration Center: Nacos, Apollo
- Monitoring & Alerting: Prometheus, Grafana, Alertmanager
- Distributed Tracing: OpenTelemetry, Jaeger

### Automation & CI/CD
- Pipelines: GitLab CI/CD, Jenkins, ArgoCD
- Orchestration: Ansible, Temporal
- Scripting Languages: Python, Shell

### AI & Intelligence
- LLM Integration: LangChain, LangGraph
- AIOps: Anomaly Detection, Root Cause Analysis

## System Architecture

![Zebra Architecture Diagram](arch.png)

### Architecture Overview
The Zebra Ops Platform adopts a microservices architecture with core components including:

- **Application Gateways**: Unified entry gateway, responsible for request routing, authentication, rate limiting, and circuit breaking
- **Z-RBAC**: Permission management service, providing Role-Based Access Control (RBAC) functionality
- **Z-CICD**: Continuous integration and continuous deployment service, supporting automated build, test, and deployment processes
- **Z-KB**: Knowledge base service, storing operations knowledge and incident response solutions
- **Nacos**: Service registration and configuration center, implementing service discovery and dynamic configuration management
- **Otel**: OpenTelemetry distributed tracing, providing end-to-end monitoring capabilities
- **Data Storage**: PostgreSQL (relational data), Redis (caching), Elasticsearch (log search)

### Architecture Highlights
- **High Availability**: Multi-node deployment with load balancing
- **Scalability**: Modular design supporting horizontal scaling
- **Maintainability**: Unified monitoring and alerting for quick issue identification
- **Security & Reliability**: Comprehensive permission control and audit mechanisms

## 🎯 Project Goals
Building a modern, intelligent operations management platform to achieve:
- Automation of operations work, reducing manual intervention
- Visualization of system status, improving observability
- Intelligent incident response, reducing MTTR
- Granular permission management, ensuring system security

## 🌟 Core Features
- 📊 Real-time Monitoring Dashboard: Multi-dimensional metrics display
- 🤖 Intelligent Alerting: AI-based anomaly detection
- 🔄 Automated Operations: Batch execution, scheduled tasks, self-healing
- 📚 Knowledge Repository: Incident case database, best practices
- 🚀 Quick Deployment: One-click deployment for Kubernetes and Docker Compose

## Open Source Projects
1. [ZebraUI](https://github.com/ZebraOps/ZebraUI) - Enterprise-grade operations management platform
2. [ZebraRBAC](https://github.com/ZebraOps/ZebraRBAC) - RBAC-based permission management module
3. [ZebraCICD](https://github.com/ZebraOps/ZebraCICD) - Microservice for continuous integration and continuous deployment (CI/CD) developed in Go

## 🤝 Contributing Guide
- Submit Issues to report problems or request features
- Submit Pull Requests to contribute code
- Participate in documentation writing and translation
- Share usage experiences and best practices

## 📞 Contact Information
- Email: iamnumachen@gmail.com
- GitHub: [ZebraOps](https://github.com/ZebraOps)
