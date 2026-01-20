# Kubernetes Learning Path
## From Zero to Kubestronaut

> **Note:** The roadmap will help you get on the right track, but as always, practice is what makes perfect.

---

## Table of Contents
- [Common Fundamentals](#common-fundamentals)
- [Learning Levels](#learning-levels)
- [Certification Progression](#certification-progression)
- [Best Courses](#best-courses)
- [Official Resources](#official-resources)
- [Hands-On Practice](#hands-on-practice)

---

## Common Fundamentals

Before diving into Kubernetes, you need to build a solid foundation in these core areas:

### 1. **Linux Basics**
- Command line operations (navigation, file manipulation, permissions)
- Package management (apt, yum, dnf)
- Process management and systemd
- Basic shell scripting
- Networking fundamentals (TCP/IP, DNS, HTTP/HTTPS)

### 2. **Containerization**
- What are containers and why they exist
- Docker fundamentals (images, containers, volumes, networks)
- Container lifecycle management
- Writing Dockerfiles
- Docker Compose for multi-container applications
- Container registries (Docker Hub, ECR, GCR)

### 3. **Basic Networking**
- IP addressing and subnetting
- Load balancing concepts
- Reverse proxies
- DNS and service discovery
- TLS/SSL certificates

### 4. **Version Control**
- Git basics (clone, commit, push, pull, branch, merge)
- GitHub/GitLab workflows
- GitOps concepts

### 5. **YAML**
- YAML syntax and structure
- Writing and reading YAML files
- Common patterns in configuration files

### 6. **Basic Cloud Concepts** (Optional but recommended)
- Virtual machines vs containers
- Cloud provider basics (AWS, Azure, or GCP)
- Infrastructure as Code concepts

---

## Learning Levels

### 🌱 **Level 0: Absolute Beginner** 
**Prerequisites:** None  
**Goal:** Understand what Kubernetes is and why it exists

**What to Learn:**
- What problems does Kubernetes solve?
- Containers vs Virtual Machines
- Microservices architecture basics
- Overview of Kubernetes architecture
- Basic terminology (Pod, Node, Cluster, Deployment)

**Skills to Build:**
- Install Docker on your local machine
- Run basic Docker commands
- Create a simple Dockerfile
- Learn basic Linux commands

**Certification Target:** None yet

---

### 🌿 **Level 1: Foundation** 
**Prerequisites:** Linux basics, Docker fundamentals  
**Goal:** Understand Kubernetes core concepts and architecture

**What to Learn:**
- Kubernetes architecture (Control Plane, Worker Nodes)
- Core components (API Server, etcd, Scheduler, Controller Manager, Kubelet, kube-proxy)
- Pods, ReplicaSets, Deployments
- Services (ClusterIP, NodePort, LoadBalancer)
- Namespaces
- ConfigMaps and Secrets
- Basic kubectl commands
- Setting up local Kubernetes (minikube, kind, or Docker Desktop)

**Skills to Build:**
- Deploy your first application to Kubernetes
- Scale applications up and down
- Expose applications using Services
- Use ConfigMaps for configuration
- View logs and troubleshoot basic issues

**Certification Target:** **KCNA** (Kubernetes and Cloud Native Associate)

<img width="240" height="232" alt="image" src="https://github.com/user-attachments/assets/64b08053-c824-45a5-b734-d88ad321d0eb" />

---

### 🌳 **Level 2: Practitioner** 
**Prerequisites:** KCNA or equivalent knowledge  
**Goal:** Administer Kubernetes clusters and deploy production-ready applications

**What to Learn:**

**For Administrators (CKA Path):**
- Cluster installation and configuration
- Networking (CNI plugins, Network Policies)
- Storage (Persistent Volumes, Persistent Volume Claims, Storage Classes)
- Security (RBAC, Service Accounts, Security Contexts)
- Resource management (Requests, Limits, LimitRanges, ResourceQuotas)
- Cluster maintenance (backup/restore, upgrades)
- Troubleshooting (debugging pods, cluster issues)
- Logging and monitoring fundamentals

**For Developers (CKAD Path):**
- Multi-container Pod patterns (sidecar, adapter, ambassador)
- Deployments and rolling updates
- Jobs and CronJobs
- Health checks (Liveness, Readiness, Startup probes)
- Resource limits and requests
- Volumes and data persistence
- Application configuration (ConfigMaps, Secrets, environment variables)
- Service discovery and networking
- Helm basics (charts, releases, values)

**Skills to Build:**
- Set up a multi-node cluster from scratch
- Implement RBAC policies
- Configure persistent storage
- Deploy stateful applications
- Implement network policies
- Perform cluster backups and upgrades
- Debug and troubleshoot production issues

**Certification Targets:**
- **CKA** (Certified Kubernetes Administrator) - for infrastructure/ops focus
  
<img width="210" height="223" alt="image" src="https://github.com/user-attachments/assets/ea9efd60-0504-4e7e-b1ad-55c68791902d" />
  
- **CKAD** (Certified Kubernetes Application Developer) - for developer focus
  
<img width="235" height="232" alt="image" src="https://github.com/user-attachments/assets/95fcf05a-cffd-429d-8774-67781ae9c530" />

---

### 🌲 **Level 3: Advanced Practitioner** 
**Prerequisites:** CKA and/or CKAD  
**Goal:** Implement security best practices and advanced patterns

**What to Learn:**
- Advanced security (Pod Security Standards, OPA/Gatekeeper, Falco)
- Supply chain security (image scanning, signing, SBOM)
- Secrets management (Vault, External Secrets Operator)
- Advanced networking (Service Mesh - Istio/Linkerd, Ingress Controllers)
- GitOps (ArgoCD, Flux)
- Advanced observability (Prometheus, Grafana, Jaeger, ELK)
- Cluster hardening and compliance
- Runtime security and threat detection
- Disaster recovery strategies
- Multi-cluster management

**Skills to Build:**
- Implement Pod Security Standards
- Set up a service mesh
- Configure GitOps workflows
- Implement comprehensive monitoring
- Conduct security audits
- Implement zero-trust networking
- Set up multi-cluster deployments

**Certification Targets:**
- **KCSA** (Kubernetes and Cloud Security Associate) - security foundation

 <img width="227" height="250" alt="image" src="https://github.com/user-attachments/assets/758a166f-0494-40a8-8cdc-a7b77786f1e8" />

- **CKS** (Certified Kubernetes Security Specialist) - advanced security

<img width="219" height="265" alt="image" src="https://github.com/user-attachments/assets/7c127e5c-8ad4-44a3-86e3-17b23d5b8265" />

---

###  **Level 4: Kubestronauts **
**Prerequisites:** CKA, CKAD, CKS, KCNA, KCSA  
**Goal:**
will receive the title of Kubestronaut, as well as these additional benefits:

**Recognition:**

An exclusive Kubestronaut jacket to show off your elite status
A Credly badge to showcase your expertise
Access to the dedicated/private Kubestronaut Slack channel and mailing list
Five coupons for 50%-off certifications each year, for yourself or to share
20%-off three CNCF events (KubeCon or KubeDays) a year
**The Kubernaut Program:**

Individuals who have successfully passed every CNCF Kubernetes certification 

<img width="456" height="353" alt="image" src="https://github.com/user-attachments/assets/3d76ab3c-8867-47d9-9759-88734fc33c6d" />



###  **Level 5:  Golden Kubestronauts **

**Core Kubernetes Certifications (5):**
Individuals who have successfully passed every CNCF certification (currently CKA, CKAD, CKS, KCNA, KCSA, PCA, ICA, CCA, CAPA, CGOA, CBA, OTCA, KCA, CNPA) and LFCS, will receive the title of Golden Kubestronaut for life, as well as these additional benefits:

An exclusive backpack with the Golden Kubestronaut logo
A special Golden Kubestronaut beanie
ThriveOne subscription (as long as the Kubestronaut title is maintained)
One free ticket per year to any Kubernetes Community Days (KCD)
One 50%-off KubeCon registration per year
A 60% discount voucher for each new CNCF certification
A distinguished Golden representation on the Kubestronaut website
UPDATE : CNPE will be an additional requirement after March 1st to become a Golden Kubestronaut.

<img width="477" height="429" alt="image" src="https://github.com/user-attachments/assets/922941f1-8cb4-47b4-b4b0-7fcac2491a83" />


---

## Certification Progression

### Official CNCF/Linux Foundation Certifications

```
Entry Level:
┌─────────────────────────────────────┐
│  KCNA                               │
│  Kubernetes and Cloud Native        │
│  Associate                          │
│  • Entry point for beginners        │
│  • Multiple choice exam             │
│  • 90 minutes                       │
└─────────────────────────────────────┘
              ↓
Intermediate Level (Choose based on role):
┌─────────────────┐      ┌─────────────────┐
│  CKA            │  OR  │  CKAD           │
│  Administrator  │      │  Developer      │
│  • Performance  │      │  • Performance  │
│  • 2 hours      │      │  • 2 hours      │
└─────────────────┘      └─────────────────┘
       ↓                         ↓
       └──────────┬──────────────┘
                  ↓
Security Track:
┌─────────────────────────────────────┐
│  KCSA (Optional)                    │
│  Kubernetes and Cloud Security      │
│  Associate                          │
│  • Security fundamentals            │
│  • Multiple choice exam             │
└─────────────────────────────────────┘
              ↓
┌─────────────────────────────────────┐
│  CKS                                │
│  Kubernetes Security Specialist     │
│  • Requires valid CKA               │
│  • Performance based                │
│  • 2 hours                          │
└─────────────────────────────────────┘
              ↓
┌─────────────────────────────────────┐
│  🎖️ KUBERNAUT STATUS                 │
│  (5 CNCF Certifications)            │
│  • All 5 K8s certs OR               │
│  • Mix of K8s + other CNCF certs    │
└─────────────────────────────────────┘
              ↓
Continue with additional CNCF certifications:
┌──────────────┐  ┌──────────────┐  ┌──────────────┐
│  PCA         │  │  ISTCA       │  │  CGOA        │
│  Prometheus  │  │  Istio       │  │  GitOps      │
└──────────────┘  └──────────────┘  └──────────────┘
              ↓
┌─────────────────────────────────────┐
│  🏆 GOLDEN KUBERNAUT STATUS          │
│  (10 CNCF Certifications)           │
│  • The Ultimate Achievement         │
│  • Elite Cloud Native Professional  │
└─────────────────────────────────────┘
```

### Recommended Certification Order:

1. **KCNA** - Start here if you're completely new
2. **CKA** - If focusing on infrastructure/operations
3. **CKAD** - If focusing on application development (can be taken before or after CKA)
4. **KCSA** - Optional, provides security foundation
5. **CKS** - Final certification for security specialization
6. **🎖️ Kubernaut Status Achieved** (5 certifications)
7. **PCA** (Prometheus) - Monitoring and observability
8. **ISTCA** (Istio) - Service mesh expertise
9. **CGOA** (GitOps) - Modern deployment practices
10. **Additional CNCF cert of choice** (LFCA, FinOps, etc.)
11. **🏆 Golden Kubernaut Status Achieved** (10 certifications)

---

## Best Courses

### Free Resources

#### KCNA Preparation
- **KodeKloud - KCNA Course** 
  https://kodekloud.com/courses/kubernetes-and-cloud-native-associate-kcna/
- **CNCF Kubernetes and Cloud Native Essentials** 
  https://training.linuxfoundation.org/training/kubernetes-and-cloud-native-essentials-lfs250/

#### CKA Preparation
- **Killer Shell CKA**  
  https://killer.sh/
- **KodeKloud CKA Course**  
  https://kodekloud.com/courses/certified-kubernetes-administrator-cka/
- **Mumshad Mannambeth's CKA Course on Udemy**  
  https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/

#### CKAD Preparation
- **KodeKloud CKAD Course**  
  https://kodekloud.com/courses/certified-kubernetes-application-developer-ckad/
- **Mumshad Mannambeth's CKAD Course on Udemy**  
  https://www.udemy.com/course/certified-kubernetes-application-developer/

#### CKS Preparation
- **KodeKloud CKS Course**  
  https://kodekloud.com/courses/certified-kubernetes-security-specialist-cks/
- **Kim Wüstkamp's CKS Course on Udemy**  
  https://www.udemy.com/course/certified-kubernetes-security-specialist/

### Linux Foundation Official Courses 
- **LFS250** - Kubernetes and Cloud Native Essentials  
  https://training.linuxfoundation.org/training/kubernetes-and-cloud-native-essentials-lfs250/
- **LFS258** - Kubernetes Fundamentals  
  https://training.linuxfoundation.org/training/kubernetes-fundamentals/
- **LFS260** - Kubernetes Security Essentials  
  https://training.linuxfoundation.org/training/kubernetes-security-essentials-lfs260/
- **LFS261** - DevOps and SRE Fundamentals  
  https://training.linuxfoundation.org/training/devops-and-sre-fundamentals-implementing-continuous-delivery-lfs261/

### Additional Recommended Courses
- **A Cloud Guru** - Various Kubernetes courses  
  https://acloudguru.com/browse-training?type=course&topic=kubernetes
- **Pluralsight** - Kubernetes Learning Path  
  https://www.pluralsight.com/paths/kubernetes
- **Cloud Academy** - Kubernetes courses  
  https://cloudacademy.com/learning-paths/kubernetes-essentials-1-2350/

### YouTube Channels (Free)
- **TechWorld with Nana** - Kubernetes Tutorial for Beginners  
  https://www.youtube.com/c/TechWorldwithNana
- **KodeKloud** - Free Kubernetes tutorials  
  https://www.youtube.com/c/KodeKloud
- **Just me and Opensource**  
  https://www.youtube.com/c/wenkatn-justmeandopensource

---

## Official Resources

### Kubernetes Official
- **Official Documentation**  
  https://kubernetes.io/docs/
- **Kubernetes Blog**  
  https://kubernetes.io/blog/
- **Kubernetes GitHub**  
  https://github.com/kubernetes/kubernetes
- **Interactive Tutorial**  
  https://kubernetes.io/docs/tutorials/kubernetes-basics/

### CNCF (Cloud Native Computing Foundation)
- **CNCF Main Website**  
  https://www.cncf.io/
- **CNCF Landscape** - Overview of cloud-native projects  
  https://landscape.cncf.io/
- **CNCF Glossary**  
  https://glossary.cncf.io/

### Certification Information
- **Linux Foundation Training & Certification**  
  https://training.linuxfoundation.org/
- **CNCF Certification**  
  https://www.cncf.io/training/certification/
- **Exam Curriculum & Preparation**  
  https://training.linuxfoundation.org/certification/catalog/

#### Specific Certification Pages:
- **KCNA**  
  https://training.linuxfoundation.org/certification/kubernetes-cloud-native-associate/
- **CKA**  
  https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/
- **CKAD**  
  https://training.linuxfoundation.org/certification/certified-kubernetes-application-developer-ckad/
- **CKS**  
  https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/
- **KCSA**  
  https://training.linuxfoundation.org/certification/kubernetes-and-cloud-native-security-associate-kcsa/

#### Beyond Kubernetes - Additional CNCF Certifications:
- **PCA** - Prometheus Certified Associate  
  https://training.linuxfoundation.org/certification/prometheus-certified-associate/
- **ISTCA** - Istio Certified Associate  
  https://training.linuxfoundation.org/certification/istio-certified-associate-isca/
- **CGOA** - Certified GitOps Associate  
  https://training.linuxfoundation.org/certification/certified-gitops-associate-cgoa/
- **LFCA** - Linux Foundation Certified IT Associate  
  https://training.linuxfoundation.org/certification/linux-foundation-certified-it-associate/

### Kubernaut Program
- **Kubernaut Program Overview**  
  https://www.cncf.io/training/kubernaut/
- **Kubernaut Directory** (View current Kubernauts)  
  https://www.credly.com/organizations/the-linux-foundation/badges
- **CNCF Certification Catalog** (All available certifications)  
  https://training.linuxfoundation.org/certification/catalog/

### Community Resources
- **Kubernetes Slack**  
  https://slack.k8s.io/
- **Kubernetes Reddit**  
  https://www.reddit.com/r/kubernetes/
- **Kubernetes Forum**  
  https://discuss.kubernetes.io/
- **KubeCon + CloudNativeCon** (Official conferences)  
  https://www.cncf.io/kubecon-cloudnativecon-events/

---

## Hands-On Practice

### Local Kubernetes Environments
- **Minikube** - Local Kubernetes cluster  
  https://minikube.sigs.k8s.io/
- **Kind** (Kubernetes in Docker) - Lightweight local clusters  
  https://kind.sigs.k8s.io/
- **k3s** - Lightweight Kubernetes  
  https://k3s.io/
- **Docker Desktop** - Built-in Kubernetes  
  https://www.docker.com/products/docker-desktop/

### Practice Platforms
- **Killer.sh** - Exam simulator   
  https://killer.sh/
- **KodeKloud Playgrounds** - Free interactive labs  
  https://kodekloud.com/playgrounds/
- **Play with Kubernetes** - Free browser-based lab  
  https://labs.play-with-k8s.com/
- **Katacoda** (now O'Reilly) - Interactive scenarios  
  https://www.katacoda.com/

### Cloud Provider Managed Kubernetes (Free tiers available)
- **Google Kubernetes Engine (GKE)**  
  https://cloud.google.com/kubernetes-engine
- **Amazon Elastic Kubernetes Service (EKS)** 
  https://aws.amazon.com/eks/
- **Azure Kubernetes Service (AKS)**   
  https://azure.microsoft.com/en-us/products/kubernetes-service/

---

## Additional Tips for Success

### Study Strategy
1. **Follow the 70-20-10 rule**: 70% hands-on practice, 20% reading documentation, 10% watching videos
2. **Build real projects**: Deploy actual applications to reinforce concepts
3. **Join the community**: Participate in Kubernetes Slack, forums, and local meetups
4. **Practice time management**: Certification exams are performance-based and timed
5. **Use exam simulators**: Practice with Killer.sh before taking certifications
6. **Read error messages**: Understanding errors is crucial for troubleshooting
7. **Master kubectl**: Speed with kubectl commands is essential for exams

### Learning Timeline Estimate
- **Absolute beginner to KCNA**: 2-3 months (part-time study)
- **KCNA to CKA**: 3-4 months (part-time study)
- **CKA to CKS**: 2-3 months (with CKA knowledge)
- **Total journey to CKS**: 8-12 months of consistent study
- **CKS to Kubernaut (5 certs)**: Already achieved with all K8s certs!
- **Kubernaut to Golden Kubernaut**: 6-12 additional months (5 more certifications)
- **Total journey to Golden Kubernaut**: 18-24 months of dedicated study

### Certification Validity
- All CNCF certifications are valid for **2 years** from the date of completion
- Recertification is required to maintain the credential
- Kubernaut and Golden Kubernaut status requires maintaining valid certifications

---

