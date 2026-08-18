<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0D1117&height=180&section=header&text=VIGNESHWARAN%20SIVASUBRAMANIYAN&fontSize=38&fontColor=FFFFFF&fontAlignY=45&desc=CLOUD%20%7C%20DEVOPS%20%7C%20KUBERNETES%20%7C%20AI%20ENGINEERING&descAlignY=68&descSize=16"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3500&pause=1200&color=A78BFA&center=true&vCenter=true&width=800&lines=Cloud+Infrastructure+%7C+DevOps+%7C+Platform+Engineering;Kubernetes+%7C+OpenShift+%7C+Terraform+%7C+AWS;CI%2FCD+Automation+%7C+Observability+%7C+AI+Engineering" alt="Engineering Focus"/>

<br/><br/>

<a href="https://github.com/vigneshsivasubramaniyan">
<img src="https://img.shields.io/badge/GitHub-vigneshsivasubramaniyan-161B22?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://in.linkedin.com/in/vigneshwaran-sivasubramaniyan">
<img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://vignesh.madrasmic.in">
<img src="https://img.shields.io/badge/Portfolio-vignesh.madrasmic.in-6E40C9?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>

<a href="mailto:vigneshsivasubramaniyan@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

---

## About Me

I am a **Cloud & DevOps Engineer** focused on infrastructure automation, cloud platforms, container orchestration and AI-assisted engineering.

My engineering background spans **VMware infrastructure, Linux, Docker, Kubernetes, OpenShift, AWS, Terraform, Ansible and CI/CD**, with a current focus on building production-inspired cloud-native platforms.

I use hands-on projects and homelab environments to design, automate, observe and troubleshoot real-world infrastructure workflows.

---

## Technology Stack

### Cloud & Infrastructure

<p>
<img src="https://skillicons.dev/icons?i=aws,linux,terraform,ansible"/>
</p>

`AWS` `EC2` `VPC` `IAM` `S3` `Terraform` `Ansible` `Linux`

### Containers & Orchestration

<p>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,openshift"/>
</p>

`Docker` `Kubernetes` `OpenShift` `K3s` `Helm` `Container Platforms`

### CI/CD & Automation

<p>
<img src="https://skillicons.dev/icons?i=git,github,jenkins,python"/>
</p>

`Git` `GitHub` `Jenkins` `GitHub Actions` `Python` `CI/CD`

### Observability

<p>
<img src="https://skillicons.dev/icons?i=prometheus,grafana"/>
</p>

`Prometheus` `Grafana` `cAdvisor` `Node Exporter` `Metrics` `Monitoring`

### AI Engineering

`LangChain` `LangGraph` `RAG` `Qdrant` `Ollama` `LiteLLM` `Embeddings` `LLM Applications` `AI Agents`

### Virtualization & Networking

`VMware vSphere` `ESXi` `vCenter` `PowerCLI` `Cloudflare` `Nginx` `DNS` `TLS` `Reverse Proxy`

---

# Featured Engineering Projects

## 01 — Enterprise DevOps CI/CD Platform

A production-inspired deployment platform demonstrating multiple approaches to delivering the same application from source control to runtime.

### Deployment Architecture

```text
                           GitHub
                             │
                ┌────────────┴────────────┐
                │                         │
                ▼                         ▼
             Jenkins               GitHub Actions
                │                         │
                └────────────┬────────────┘
                             │
                             ▼
                           Docker
                             │
              ┌──────────────┴──────────────┐
              │                             │
              ▼                             ▼
       Docker Desktop                    AWS Cloud
                                            │
                                        Terraform
                                            │
                                           EC2
                                            │
                                         Docker
                                            │
                                        Application
```

### What it demonstrates

* Git-based development workflow
* Jenkins CI/CD
* GitHub Actions
* Docker image creation
* Automated deployments
* Terraform infrastructure provisioning
* AWS EC2 deployment
* Repeatable infrastructure
* Multiple deployment strategies

**Stack:** `GitHub` `Jenkins` `GitHub Actions` `Docker` `Terraform` `AWS EC2` `Linux`

---

## 02 — DevOps Homelab Platform

A self-hosted engineering environment used to build and operate production-inspired infrastructure, DevOps, networking, observability and AI workloads.

### Platform

```text
                         Internet
                            │
                            ▼
                       Cloudflare
                          Tunnel
                            │
                            ▼
                      Nginx Proxy
                          Manager
                            │
          ┌─────────────────┼─────────────────┐
          │                 │                 │
          ▼                 ▼                 ▼
       DevOps              AI             Services
          │                 │                 │
       Jenkins           Ollama          Nextcloud
       Docker            LiteLLM         Jellyfin
       GitHub             Qdrant             n8n
                          OpenWebUI
          │                 │
          └─────────────────┼─────────────────┘
                            │
                            ▼
                    Prometheus + Grafana
```

### What it demonstrates

* Containerized infrastructure
* Secure external access
* Reverse proxy and DNS
* Cloudflare Tunnel
* CI/CD automation
* Self-hosted AI infrastructure
* Vector database
* LLM gateway
* Workflow automation
* Infrastructure monitoring
* GPU monitoring

**Stack:** `Docker` `Linux` `Cloudflare` `Nginx` `Jenkins` `Prometheus` `Grafana` `Ollama` `Qdrant` `LiteLLM`

---

## 03 — AI DevOps Copilot

An AI engineering platform designed to combine operational data, engineering documentation and LLM reasoning to assist with DevOps troubleshooting.

### Architecture

```text
                  Engineer
                     │
                     ▼
              AI DevOps Copilot
                     │
              LangChain / LangGraph
                     │
       ┌─────────────┼─────────────┐
       │             │             │
       ▼             ▼             ▼
    Jenkins        GitHub      Kubernetes
       │             │             │
       └─────────────┼─────────────┘
                     │
                     ▼
                Prometheus
                     │
                     ▼
                RAG Retrieval
                     │
                     ▼
                  Qdrant
                     │
                     ▼
                    LLM
                     │
                     ▼
             Analysis / RCA
```

### What it demonstrates

* Jenkins log analysis
* Kubernetes troubleshooting
* GitHub change analysis
* Prometheus metric analysis
* Internal documentation retrieval
* RAG-based troubleshooting
* Incident summarization
* Root-cause analysis assistance
* AI-assisted DevOps workflows

**Stack:** `Python` `LangChain` `LangGraph` `Qdrant` `RAG` `Ollama` `LiteLLM` `Jenkins` `Kubernetes` `Prometheus`

---

## What I'm Working On

```text
AWS
 │
 ├── Infrastructure
 ├── Terraform
 └── Cloud Architecture
       │
       ▼
DevOps
 │
 ├── GitHub Actions
 ├── Jenkins
 └── CI/CD
       │
       ▼
Kubernetes
 │
 ├── Kubernetes
 ├── OpenShift
 └── Platform Engineering
       │
       ▼
Observability
 │
 ├── Prometheus
 └── Grafana
       │
       ▼
AI Engineering
 │
 ├── RAG
 ├── LangChain
 ├── LangGraph
 └── AI DevOps
```

---

## GitHub Activity

<div align="center">

<a href="https://github.com/vigneshsivasubramaniyan">
<img src="https://github-readme-stats.vercel.app/api?username=vigneshsivasubramaniyan&show_icons=true&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=A78BFA&text_color=C9D1D9&rank_icon=github" height="170"/>
</a>

<a href="https://github.com/vigneshsivasubramaniyan">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vigneshsivasubramaniyan&layout=compact&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9" height="170"/>
</a>

</div>

---

<div align="center">

### Building Infrastructure. Automating Operations. Engineering with AI.

<a href="https://github.com/vigneshsivasubramaniyan">
<img src="https://img.shields.io/badge/Explore%20My%20Repositories-161B22?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0D1117&height=80&section=footer"/>

</div>
