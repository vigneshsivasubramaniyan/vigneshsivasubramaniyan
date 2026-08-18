<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=230&section=header&text=VIGNESHWARAN%20SIVASUBRAMANIYAN&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Cloud%20%7C%20DevOps%20%7C%20Kubernetes%20%7C%20Platform%20Engineering%20%7C%20AI&descAlignY=58&descSize=17"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1800&color=A78BFA&center=true&vCenter=true&width=900&lines=Designing+Cloud-Native+Infrastructure;Automating+Infrastructure+with+Terraform+%26+Ansible;Building+Reliable+CI%2FCD+with+Jenkins+%26+GitHub+Actions;Operating+Docker%2C+Kubernetes+%26+OpenShift+Platforms;Engineering+AI-Powered+DevOps+Workflows" alt="Typing SVG"/>

<br/><br/>

<a href="https://github.com/vigneshsivasubramaniyan">
<img src="https://img.shields.io/badge/GitHub-vigneshsivasubramaniyan-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://in.linkedin.com/in/vigneshwaran-sivasubramaniyan">
<img src="https://img.shields.io/badge/LinkedIn-Professional%20Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://vignesh.madrasmic.in">
<img src="https://img.shields.io/badge/Portfolio-vignesh.madrasmic.in-6D28D9?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>

</div>

---

# Cloud & DevOps Engineer

I design, automate and operate infrastructure across **enterprise virtualization, cloud, containers and Kubernetes platforms**, with a growing focus on **AI-powered engineering automation**.

My work focuses on building systems that are reproducible, observable and automated rather than manually operated.

```yaml
profile:
  role: Senior Cloud & DevOps Engineer

  engineering_domains:
    - Cloud Infrastructure
    - DevOps & CI/CD
    - Kubernetes & OpenShift
    - Infrastructure as Code
    - Platform Engineering
    - Observability
    - AI Engineering

  infrastructure:
    - VMware vSphere
    - Linux
    - Docker
    - Kubernetes
    - OpenShift
    - AWS

  automation:
    - Terraform
    - Ansible
    - Jenkins
    - GitHub Actions
    - Python
    - Git

  ai_engineering:
    - RAG
    - LangChain
    - LangGraph
    - Qdrant
    - Ollama
    - LiteLLM
    - LLM Applications

  engineering_principle:
    Design → Automate → Observe → Improve
```

---

# Engineering Stack

### Cloud

<p>
<img src="https://skillicons.dev/icons?i=aws"/>
</p>

`AWS` `EC2` `VPC` `IAM` `S3` `EBS` `Cloud Infrastructure`

### Containers & Platforms

<p>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,openshift"/>
</p>

`Docker` `Kubernetes` `OpenShift` `K3s` `Containerization` `Helm`

### Infrastructure as Code & Automation

<p>
<img src="https://skillicons.dev/icons?i=terraform,ansible,python"/>
</p>

`Terraform` `Ansible` `Python` `PowerCLI` `Infrastructure Automation`

### CI/CD

<p>
<img src="https://skillicons.dev/icons?i=git,github,jenkins"/>
</p>

`Git` `GitHub` `Jenkins` `GitHub Actions` `CI/CD` `Webhooks` `Automated Deployment`

### Observability

<p>
<img src="https://skillicons.dev/icons?i=prometheus,grafana"/>
</p>

`Prometheus` `Grafana` `cAdvisor` `Node Exporter` `Metrics` `Alerting` `GPU Monitoring`

### AI Engineering

`Python` `LangChain` `LangGraph` `RAG` `Qdrant` `Ollama` `LiteLLM` `Embeddings` `LLM Applications` `AI Agents`

### Infrastructure & Networking

`Linux` `VMware vSphere` `ESXi` `vCenter` `Cloudflare` `DNS` `TLS` `Reverse Proxy` `Nginx` `RBAC`

---

# Engineering Journey

```text
Enterprise Infrastructure
        │
        ▼
VMware / Virtualization
        │
        ▼
Linux & Infrastructure Automation
        │
        ▼
Docker & CI/CD
        │
        ▼
AWS Cloud
        │
        ▼
Terraform / Ansible
        │
        ▼
Kubernetes / OpenShift
        │
        ▼
Observability & Platform Engineering
        │
        ▼
AI Engineering
        │
        ▼
AI-Powered Cloud & DevOps Automation
```

The objective is not simply to learn individual technologies.

The objective is to understand how they work together to build and operate reliable engineering platforms.

---

# Featured Engineering Projects

## 01 — Enterprise DevOps Delivery Platform

**Production-inspired application delivery platform demonstrating automated software delivery from source control to containerized runtime.**

### Architecture

```text
                    ┌─────────────────┐
                    │     GitHub      │
                    │ Source Control  │
                    └────────┬────────┘
                             │
                             │ Webhook
                             ▼
                    ┌─────────────────┐
                    │     Jenkins     │
                    │     CI/CD       │
                    └────────┬────────┘
                             │
                    ┌────────▼────────┐
                    │ Build / Test    │
                    │ Docker Build    │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │ Docker Image    │
                    └────────┬────────┘
                             │
              ┌──────────────┴──────────────┐
              │                             │
              ▼                             ▼
       Docker Desktop                    AWS Cloud
              │                             │
              ▼                             ▼
         Container              Terraform → EC2 → Docker
```

### Implementation

* GitHub-based source control
* Jenkins pipeline automation
* Docker image creation
* Automated container deployment
* GitHub Actions implementation
* Infrastructure provisioning using Terraform
* AWS EC2 deployment
* Deployment validation
* Repeatable infrastructure

### Technology

`GitHub` `Jenkins` `GitHub Actions` `Docker` `Terraform` `AWS EC2` `Linux`

### Engineering Objective

> Demonstrate the same application moving through multiple deployment strategies while maintaining an automated and reproducible delivery process.

---

# 02 — DevOps Homelab & Private Cloud Platform

A self-hosted engineering environment used to reproduce real-world infrastructure, networking, observability, DevOps and AI workloads.

### Platform Architecture

```text
                         Internet
                            │
                            ▼
                     ┌─────────────┐
                     │  Cloudflare │
                     │    Tunnel   │
                     └──────┬──────┘
                            │
                            ▼
                    ┌───────────────┐
                    │ Reverse Proxy │
                    │     Nginx     │
                    └───────┬───────┘
                            │
        ┌───────────────────┼───────────────────┐
        │                   │                   │
        ▼                   ▼                   ▼
     DevOps               AI Platform        Applications
        │                   │                   │
   ┌────┴────┐       ┌──────┴──────┐      ┌─────┴─────┐
   │ Jenkins │       │   Ollama    │      │ Nextcloud │
   │ Docker  │       │ Open WebUI  │      │ Jellyfin  │
   │ GitHub  │       │   Qdrant    │      │   n8n     │
   └─────────┘       │   LiteLLM   │      └───────────┘
                     └─────────────┘
                            │
                            ▼
                    ┌────────────────┐
                    │ Observability  │
                    │ Prometheus     │
                    │ Grafana        │
                    └────────────────┘
```

### Engineering Areas

* Containerized infrastructure
* Secure external access
* Reverse proxy architecture
* DNS and TLS
* CI/CD
* Self-hosted AI infrastructure
* Vector database
* LLM gateway
* Workflow automation
* Infrastructure monitoring
* GPU monitoring
* Resource utilization analysis

### Technology

`Docker` `Linux` `Cloudflare` `Nginx` `Jenkins` `Prometheus` `Grafana` `Ollama` `Qdrant` `LiteLLM` `n8n`

---

# 03 — AI DevOps Copilot

**An AI-assisted operations platform designed to combine DevOps telemetry, engineering documentation and LLM reasoning into a single troubleshooting workflow.**

### Problem

Modern DevOps environments generate information across multiple systems:

```text
Jenkins
GitHub
Kubernetes
Prometheus
Application Logs
Infrastructure Documentation
```

The challenge is correlating these signals quickly during incidents.

### Architecture

```text
                         Engineer
                            │
                            ▼
                  ┌──────────────────┐
                  │ AI DevOps Copilot│
                  └─────────┬────────┘
                            │
                     LangChain /
                     LangGraph
                            │
             ┌──────────────┼──────────────┐
             │              │              │
             ▼              ▼              ▼
          Jenkins         GitHub      Kubernetes
             │              │              │
             └──────────────┼──────────────┘
                            │
                            ▼
                     Prometheus
                            │
                            ▼
                    Context Retrieval
                            │
                            ▼
                       Qdrant RAG
                            │
                            ▼
                         LLM
                            │
                            ▼
                   RCA / Explanation
                   / Recommendation
```

### Capabilities

* Jenkins failure analysis
* Kubernetes troubleshooting
* Git change analysis
* Prometheus metric interpretation
* Documentation retrieval
* RAG-based troubleshooting
* Incident summarization
* Root-cause analysis assistance
* Engineering recommendations

### Technology

`Python` `LangChain` `LangGraph` `Qdrant` `RAG` `Ollama` `LiteLLM` `Jenkins` `Kubernetes` `Prometheus`

---

# 04 — Local LLM & RAG Engineering Platform

A self-hosted AI environment for experimenting with local language models, embeddings, semantic search and retrieval-augmented generation.

### RAG Pipeline

```text
Documents
    │
    ▼
Document Processing
    │
    ▼
Chunking
    │
    ▼
Embedding Model
    │
    ▼
Qdrant
Vector Database
    │
    ▼
Semantic Retrieval
    │
    ▼
Relevant Context
    │
    ▼
LLM
    │
    ▼
Grounded Response
```

### Components

* Ollama
* Open WebUI
* Qdrant
* LiteLLM
* Embedding models
* Local LLMs
* RAG pipelines
* Prompt engineering
* AI observability experiments

---

# 05 — Kubernetes & OpenShift Platform Engineering

Hands-on platform engineering focused on the operational lifecycle of container orchestration platforms.

### Areas

```text
Cluster Operations
      │
      ├── Control Plane
      ├── Worker Nodes
      ├── Scheduling
      ├── Networking
      ├── Storage
      ├── RBAC
      ├── Security
      ├── Monitoring
      ├── Backup
      ├── Upgrades
      └── Troubleshooting
```

### Operational Focus

* Kubernetes administration
* OpenShift administration
* Cluster lifecycle management
* Node management
* RBAC
* Application deployment
* Resource troubleshooting
* Monitoring
* Backup and recovery concepts
* Certificate management
* Upgrade planning

---

# Infrastructure as Code

My infrastructure automation approach is based on treating infrastructure as software.

```text
Requirement
     │
     ▼
Terraform
     │
     ▼
Infrastructure Plan
     │
     ▼
Review
     │
     ▼
Apply
     │
     ▼
AWS Resources
     │
     ▼
Ansible
     │
     ▼
Configuration
     │
     ▼
Application Runtime
```

### Principles

* Reproducibility
* Version control
* Idempotency
* Automation
* Reviewability
* Environment consistency

---

# CI/CD Engineering

```text
Developer
   │
   ▼
Git Commit
   │
   ▼
GitHub
   │
   ├──────────────┐
   ▼              ▼
Jenkins      GitHub Actions
   │              │
   └───────┬──────┘
           ▼
      Build / Test
           │
           ▼
      Docker Image
           │
           ▼
       Deployment
           │
           ▼
      Health Check
           │
           ▼
       Monitoring
```

The same application is intentionally deployed through multiple automation paths to demonstrate the differences between traditional CI/CD and modern GitHub-native workflows.

---

# Observability

Infrastructure that cannot be measured cannot be reliably operated.

```text
Applications
     │
     ▼
Containers
     │
     ▼
Metrics
     │
     ├── CPU
     ├── Memory
     ├── Disk
     ├── Network
     ├── Container Health
     └── GPU
     │
     ▼
Prometheus
     │
     ▼
Grafana
     │
     ▼
Operational Visibility
```

### Monitoring Stack

`Prometheus` `Grafana` `cAdvisor` `Node Exporter` `GPU Exporter`

---

# Current Engineering Focus

```yaml
cloud:
  - AWS
  - EC2
  - VPC
  - IAM
  - Cloud Architecture

devops:
  - Jenkins
  - GitHub Actions
  - Docker
  - CI/CD
  - Release Automation

infrastructure:
  - Terraform
  - Ansible
  - Linux
  - Infrastructure as Code

platform:
  - Kubernetes
  - OpenShift
  - K3s
  - Container Platforms

observability:
  - Prometheus
  - Grafana
  - Metrics
  - Resource Monitoring

ai:
  - RAG
  - LangChain
  - LangGraph
  - Qdrant
  - Ollama
  - LiteLLM
  - AI Agents

next:
  - GitOps
  - Advanced AWS
  - Platform Engineering
  - AI-assisted Operations
```

---

# Engineering Philosophy

```text
                    BUILD
                      │
                      ▼
                 AUTOMATE
                      │
                      ▼
                  OBSERVE
                      │
                      ▼
                 ANALYZE
                      │
                      ▼
                 IMPROVE
                      │
                      └──────────► BUILD
```

> **Don't just deploy applications. Build systems that can deploy, observe, troubleshoot and improve themselves.**

---

# Professional Direction

```text
Cloud Engineering
       +
DevOps
       +
Kubernetes
       +
Infrastructure as Code
       +
Observability
       +
AI Engineering
       │
       ▼
Cloud-Native Platform Engineering
       │
       ▼
AI-Augmented Infrastructure & Operations
```

My long-term engineering direction is to combine **cloud-native infrastructure, platform engineering and AI** to build systems that are automated, observable, scalable and easier to operate.

---

# GitHub

<div align="center">

<a href="https://github.com/vigneshsivasubramaniyan">
<img src="https://img.shields.io/badge/GitHub-Explore%20My%20Engineering%20Work-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/Cloud-Automation-6D28D9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/DevOps-CI%2FCD-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Kubernetes-Platform-9333EA?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AI-Engineering-A855F7?style=for-the-badge"/>

</div>

---

# Connect

<div align="center">

<a href="https://in.linkedin.com/in/vigneshwaran-sivasubramaniyan">
<img src="https://img.shields.io/badge/LinkedIn-Professional%20Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:vigneshsivasubramaniyan@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://vignesh.madrasmic.in">
<img src="https://img.shields.io/badge/Portfolio-Engineering%20Portfolio-6D28D9?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=130&section=footer"/>

</div>
