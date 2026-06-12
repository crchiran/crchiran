# 👋 Hi, I'm Chandan Richard Chiran

<p align="center">
  <b>Senior DevOps Engineer • Platform Engineer • Cloud Infrastructure Specialist</b><br>
  Building production-grade platforms using Kubernetes, GitOps, Cloud, Security, and Observability.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Experience-12%2B%20Years-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Kubernetes-Platform%20Engineering-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/GitOps-ArgoCD%20%7C%20FluxCD-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Cloud-Multi--Cloud-blue?style=for-the-badge" />
</p>

---

## ☸️ Platform Engineer Manifest

```yaml
apiVersion: career.chandan.dev/v1
kind: PlatformEngineer
metadata:
  name: chandan-richard-chiran
  namespace: production-infrastructure
  location: dhaka-bangladesh
  labels:
    role: senior-devops-engineer
    profile: platform-engineer
    experience: 12-plus-years
    industry: financial-services
    focus: kubernetes-gitops-cloud-security
  annotations:
    summary: >
      Senior Infrastructure and DevOps Engineer with strong hands-on experience
      in Linux, Kubernetes, cloud infrastructure, GitOps, CI/CD automation,
      infrastructure security, and observability.

spec:
  mission:
    - build-secure-platforms
    - automate-infrastructure
    - improve-reliability
    - reduce-production-risk
    - operate-mission-critical-systems

  currentRole:
    company: TMSS ICT LTD
    position: Senior Server Administrator Engineer / DevOps Engineer
    domain:
      - microfinance-infrastructure
      - centralized-account-systems
      - kubernetes-platforms
      - financial-services

  expertise:
    platformEngineering:
      - Kubernetes
      - Helm
      - Kustomize
      - Istio
      - Docker
      - Podman
      - NGINX
      - HAProxy

    cloudInfrastructure:
      - AWS
      - Azure
      - GCP
      - DigitalOcean
      - Linode
      - On-Premises Data Centers

    gitOpsAndCICD:
      - ArgoCD
      - FluxCD
      - GitHub Actions
      - Jenkins
      - Bitbucket Pipelines

    infrastructureAsCode:
      - Terraform
      - Ansible
      - CloudFormation

    observability:
      - Prometheus
      - Grafana
      - ELK
      - EFK
      - Loki
      - AlertManager
      - Wazuh

    security:
      - RBAC
      - NetworkPolicies
      - Pod Security Standards
      - WAF
      - Falco
      - Kyverno
      - Linux Hardening

    databases:
      - MySQL
      - MariaDB
      - MongoDB
      - Redis

    operatingSystems:
      - RHEL
      - CentOS
      - Ubuntu
      - Rocky Linux
      - AlmaLinux

status:
  availability: production-ready
  operatingMode: reliability-first
  automation: enabled
  securityPosture: hardened
  observability: enabled
  certifications:
    - RHCE
    - MCP
```

---

## 🧩 Service Definition

```yaml
apiVersion: v1
kind: Service
metadata:
  name: chandan-platform-engineering-service
  labels:
    app: platform-engineering
    engineer: chandan-richard-chiran
spec:
  type: ClusterIP
  ports:
    - name: kubernetes
      port: 6443
      targetPort: platform-engineering
    - name: gitops
      port: 443
      targetPort: automation
    - name: observability
      port: 9090
      targetPort: reliability
    - name: security
      port: 9443
      targetPort: hardening
  selector:
    role: senior-devops-engineer
    focus: production-infrastructure
```

---

## 🚀 Deployment Strategy

```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: production-platform-engineer
  labels:
    app: infrastructure
    tier: platform
spec:
  replicas: 1
  strategy:
    type: RollingUpdate
  selector:
    matchLabels:
      engineer: chandan-richard-chiran
  template:
    metadata:
      labels:
        engineer: chandan-richard-chiran
        role: senior-platform-engineer
    spec:
      containers:
        - name: platform-engineering
          image: chandan/platform-engineer:production
          imagePullPolicy: Always
          ports:
            - containerPort: 6443
              name: kubernetes
            - containerPort: 443
              name: gitops
            - containerPort: 9090
              name: observability
          env:
            - name: EXPERIENCE
              value: "12+ years"
            - name: PRIMARY_FOCUS
              value: "Kubernetes Platform Engineering"
            - name: CLOUD_MODE
              value: "Multi-Cloud"
            - name: SECURITY_MODE
              value: "DevSecOps"
            - name: RELIABILITY_MODE
              value: "Production First"
          readinessProbe:
            exec:
              command:
                - /bin/sh
                - -c
                - "kubectl-ready && gitops-ready && monitoring-ready"
          livenessProbe:
            exec:
              command:
                - /bin/sh
                - -c
                - "linux-stable && automation-enabled && alerts-green"
```

---

## 🛠️ ConfigMap: Technology Stack

```yaml
apiVersion: v1
kind: ConfigMap
metadata:
  name: technology-stack
data:
  cloud: |
    AWS
    Azure
    GCP
    DigitalOcean
    Linode

  kubernetes-platform: |
    Kubernetes
    Helm
    Kustomize
    Istio
    Docker
    Podman

  gitops: |
    ArgoCD
    FluxCD
    GitHub Actions
    Jenkins
    Bitbucket Pipelines

  infrastructure-as-code: |
    Terraform
    Ansible
    CloudFormation

  monitoring-logging: |
    Prometheus
    Grafana
    ELK / EFK
    Loki
    Wazuh
    AlertManager

  security: |
    RBAC
    Network Policies
    Pod Security Standards
    Falco
    Kyverno
    WAF
    Linux Hardening

  databases: |
    MySQL
    MariaDB
    MongoDB
    Redis
```

---

## 🔐 Secret: Certifications

```yaml
apiVersion: v1
kind: Secret
metadata:
  name: professional-certifications
type: Opaque
stringData:
  rhce: "Red Hat Certified Engineer"
  mcp: "Microsoft Certified Professional"
```

---

## 🏗️ Infrastructure Projects

```yaml
apiVersion: portfolio.chandan.dev/v1
kind: ProjectList
metadata:
  name: featured-infrastructure-projects
spec:
  projects:
    - name: Production Kubernetes Platform
      description: >
        Designed and operated production-grade Kubernetes environments
        across cloud and on-premises infrastructure.
      stack:
        - Kubernetes
        - ArgoCD
        - FluxCD
        - Istio
        - Prometheus
        - Grafana

    - name: Financial Services Infrastructure
      description: >
        Built and secured infrastructure for microfinance applications,
        centralized account systems, and mission-critical financial services.
      stack:
        - Kubernetes
        - Helm
        - Kustomize
        - ELK
        - Linux

    - name: Object Storage Platform
      description: >
        Implemented S3-compatible MinIO object storage with high availability,
        backup automation, and secure application integration.
      stack:
        - MinIO
        - Terraform
        - Ansible
        - Linux

    - name: Database High Availability
      description: >
        Designed MySQL and MariaDB high availability architecture with
        replication, clustering, automated failover, and backup strategies.
      stack:
        - MySQL
        - MariaDB
        - HAProxy
        - Backup Automation

    - name: Observability Platform
      description: >
        Implemented centralized monitoring, logging, alerting, and security
        visibility for production systems.
      stack:
        - Prometheus
        - Grafana
        - Loki
        - ELK
        - Wazuh
```

---

## 📈 Career Timeline

```yaml
apiVersion: career.chandan.dev/v1
kind: Timeline
metadata:
  name: engineering-journey
spec:
  milestones:
    - year: 2011
      phase: IT Operations
      focus:
        - technical-support
        - system-maintenance

    - year: 2013
      phase: Linux Infrastructure
      focus:
        - linux-administration
        - networking
        - server-operations

    - year: 2015
      phase: Enterprise System Administration
      focus:
        - production-linux
        - web-servers
        - databases
        - virtualization

    - year: 2021
      phase: DevOps and Cloud Engineering
      focus:
        - kubernetes
        - cloud-platforms
        - ci-cd
        - automation

    - year: 2024
      phase: Senior Platform Engineering
      focus:
        - financial-infrastructure
        - kubernetes-platforms
        - gitops
        - devsecops
```

---

## 🧠 Engineering Principles

```yaml
apiVersion: principles.chandan.dev/v1
kind: EngineeringPrinciples
metadata:
  name: reliability-first-engineering
spec:
  principles:
    - automate-repetitive-work
    - secure-by-default
    - observe-everything
    - document-critical-systems
    - design-for-failure
    - keep-platforms-simple
    - improve-continuously
```

---

## 📫 Contact

```yaml
apiVersion: v1
kind: Contact
metadata:
  name: chandan-richard-chiran
spec:
  email: crchiran@gmail.com
  github: https://github.com/crchiran
  linkedin: https://linkedin.com/in/chandan-richard-chiran-85a12585
  location: Dhaka, Bangladesh
```

---

<p align="center">
  <b>Building Platforms, Not Just Servers ☸️</b>
</p>
