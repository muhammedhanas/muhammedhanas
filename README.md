<div align="center">

<img src="./hanas-profile.svg" alt="Muhammed Hanas — DevOps / Infrastructure Engineer" width="100%"/>

<a href="https://github.com/muhammedhanas">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=22D3EE&center=true&vCenter=true&width=720&lines=DevOps+%2F+Infrastructure+Engineer;AWS+%E2%80%A2+Terraform+%E2%80%A2+Kubernetes+%E2%80%A2+GitOps;5+years+running+real+infrastructure;Now+automating+it+end-to-end" alt="Typing SVG"/>
</a>

<br/>

![Profile views](https://komarev.com/ghpvc/?username=muhammedhanas&label=Profile%20views&color=7C3AED&style=flat-square)
![AWS](https://img.shields.io/badge/AWS-Solutions%20Architect%20Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Location](https://img.shields.io/badge/Based%20in-UAE-10B981?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Cloud%20%7C%20DevOps%20%7C%20Platform-22D3EE?style=flat-square)

</div>

---

## 👋 About me

I'm an infrastructure engineer with **5 years of hands-on IT operations experience** (2021–2026) running servers, networks and hosting for a live business, now moving that foundation into **cloud-native DevOps**: infrastructure as code, CI/CD, containers, GitOps and observability.

My route in is unusual: a **civil engineering** degree (2016), then infrastructure. I treat systems the way I was trained to treat structures: design for load, document the assumptions, and test before you rely on it.

- 🏗️ **Run in production:** Linux/Ubuntu servers, MySQL, web hosting, networking, a **Traccar GPS platform serving ~1,000 devices**, remote equipment monitoring
- 🛠️ **Building hands-on projects:** Terraform on AWS, Kubernetes (Kind), a Jenkins → SonarQube → Trivy → Nexus pipeline, ArgoCD, Prometheus + Grafana
- 🎓 **Studied and practiced hands-on:** infrastructure as code, Kubernetes, CI/CD, GitOps, observability and DevSecOps, each documented in my repos
- 🎯 **Looking for:** DevOps / Cloud / Platform / Infrastructure engineering roles in the UAE

> **How to read this profile:** 🟢 **Production** = run in a live environment. 🛠️ **Hands-on projects** = studied, built and tested in my own environment, documented on GitHub.

---

## 🛠️ Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,terraform,kubernetes,docker,jenkins,prometheus,grafana,python,bash,linux,ubuntu,git,github,mysql,postgres,maven,wordpress&perline=9" alt="Tech stack icons"/>

<br/>

![ArgoCD](https://img.shields.io/badge/ArgoCD-GitOps-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-Code%20Quality-4E9BCD?style=for-the-badge&logo=sonarqubeserver&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-Security%20Scanning-1904DA?style=for-the-badge&logo=aqua&logoColor=white)
![Nexus](https://img.shields.io/badge/Nexus-Artifact%20Repo-1B1C30?style=for-the-badge&logo=sonatype&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-Packaging-0F1689?style=for-the-badge&logo=helm&logoColor=white)

</div>

| Area | Tools | Level of evidence |
|---|---|---|
| **Systems & hosting** | Linux/Ubuntu, Windows troubleshooting, MySQL, WordPress, CyberPanel, domains & DNS | 🟢 Production (5 yrs) |
| **Networking & monitoring** | Routers, access points, remote equipment monitoring | 🟢 Production |
| **Platform** | Traccar GPS tracking (~1,000 devices) | 🟢 Production |
| **Cloud** | AWS EC2, architecture design (Solutions Architect – Associate certified) | 🟢 Basic EC2 in production · 🛠️ Hands-on projects for the rest |
| **Infrastructure as Code** | Terraform on AWS | 🛠️ Hands-on projects |
| **Containers** | Docker, Docker Compose, Kubernetes (Kind) | 🛠️ Hands-on projects |
| **CI/CD** | Jenkins, Maven, SonarQube | 🛠️ Hands-on projects |
| **GitOps** | ArgoCD, Git workflows | 🛠️ Hands-on projects |
| **Observability** | Prometheus, Grafana, alerting | 🛠️ Hands-on projects |
| **DevSecOps** | Trivy image scanning, SonarQube quality gates | 🛠️ Hands-on projects |
| **Artifacts** | Nexus Repository, Amazon ECR | 🛠️ Hands-on projects |
| **Scripting** | Python, Bash | 🛠️ Hands-on projects |

<!-- Update the "Level of evidence" column whenever a skill is proven in a live environment. -->

---

## 🔁 DevOps pipeline project

The end-to-end flow I'm building and documenting on GitHub:

```mermaid
flowchart LR
    A[GitHub<br/>source] --> B[Jenkins<br/>CI]
    B --> C[Maven<br/>build + test]
    C --> D[SonarQube<br/>quality gate]
    D --> E[Trivy<br/>image scan]
    E --> F[Nexus / Registry<br/>artifacts]
    F --> G[ArgoCD<br/>GitOps sync]
    G --> H[Kubernetes<br/>cluster]
    H --> I[Prometheus + Grafana<br/>monitoring]
    T[Terraform] -.provisions.-> H
    T -.provisions.-> AWS[(AWS)]

    classDef lab fill:#0B1120,stroke:#22D3EE,color:#E5E7EB;
    class A,B,C,D,E,F,G,H,I,T,AWS lab;
```

> 🛠️ This is a **portfolio project**. Each stage is documented with evidence (logs, screenshots, run output) as it is verified.

---

## 🚀 Featured work

### 🟢 Traccar GPS tracking platform: production case study
Designed and ran a self-hosted **Traccar** platform supporting **~1,000 tracked devices**, including the server, database and remote monitoring around it.
**Status:** architecture write-up in progress (design, hardening, monitoring, lessons learned).

### 🛠️ DevOps pipeline: Kind + Jenkins + SonarQube + Nexus + Trivy + monitoring
Ubuntu 24.04 environment running a Kubernetes (Kind) cluster with a full CI/CD toolchain and monitoring.

<a href="https://github.com/muhammedhanas/demo-devops-app">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=muhammedhanas&repo=demo-devops-app&theme=tokyonight&hide_border=true&bg_color=0B1120" alt="demo-devops-app"/>
</a>

### 🛠️ Terraform on AWS
Infrastructure-as-code projects on AWS (modules, remote state, secure defaults).

### 🛠️ Side project: AI-assisted DevOps assistant (in design)
A read-only assistant for AWS and Kubernetes health checks and Terraform plan review, designed around **least privilege and human approval**.

---

## 🏭 Production experience

| Period | Role | What I did |
|---|---|---|
| **2021 – 2026** | IT Administrator / Infrastructure (independent, small company) | Ran Linux and Windows systems, networking, local servers, hosting and control panels, MySQL and WordPress, and remote monitoring. Implemented the Traccar platform. Connected industrial control panels and machines to servers. |
| **2016 – ~2017** | Civil engineer | About 1.5 years in civil engineering before moving to IT. |

---

## 🎓 Certifications

| | Status |
|---|---|
| ✅ AWS Certified Solutions Architect – Associate | Passed |

---

## 📊 GitHub stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=muhammedhanas&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0B1120&title_color=22D3EE&icon_color=7C3AED" alt="GitHub stats"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammedhanas&layout=compact&theme=tokyonight&hide_border=true&bg_color=0B1120&title_color=22D3EE" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=muhammedhanas&theme=tokyonight&hide_border=true&background=0B1120&ring=7C3AED&fire=22D3EE&currStreakLabel=10B981" alt="GitHub streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=muhammedhanas&theme=tokyo-night&hide_border=true&bg_color=0B1120&color=22D3EE&line=7C3AED&point=10B981" alt="Contribution activity graph" width="100%"/>

<img src="https://github-profile-trophy.vercel.app/?username=muhammedhanas&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8" alt="GitHub trophies"/>

</div>

---

## 🐍 Contribution snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/muhammedhanas/muhammedhanas/output/github-snake-dark.svg"/>
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/muhammedhanas/muhammedhanas/output/github-snake.svg"/>
  </picture>
</div>

---

## 📐 How I document every project

Every portfolio repo aims to include: **README · architecture diagram · setup steps · security notes · troubleshooting log · evidence of a successful run · known limitations · cleanup instructions.**

---

## 🤝 Let's connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-muhammedhanas-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/muhammedhanas)
<!-- Add your own links, then remove the comment markers:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-HANDLE)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR-EMAIL)
-->

<sub>Open to DevOps · Cloud · Platform · Infrastructure roles in the UAE</sub>

</div>
