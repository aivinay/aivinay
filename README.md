<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:1a8a9d,50:326CE5,100:844FBA&height=150)

# Vinay Gupta

### AI Infrastructure · Distributed Systems · Serverless Platforms

**`Senior Member of Technical Staff @ Oracle — OCI Functions`**

***12+ years** building hyperscale cloud infrastructure · prev. **Microsoft Azure** & **Bloomberg** · IEEE Senior Member*

[![Website](https://img.shields.io/badge/vinaygupta.com-1a8a9d?style=for-the-badge&logo=safari&logoColor=white)](https://vinaygupta.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aivinay/)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0000-0749-6609)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ai.vinaygupta@gmail.com)

</div>

## 🛰 What I do

I build and operate hyperscale cloud platforms. Currently I define technical strategy and architecture for **OCI Functions** — Oracle's Kubernetes-based serverless platform — including its multi-architecture (x86 + ARM) runtime migration. Daily tools: **Go, Python, Java, Kubernetes, Terraform, and gRPC**.

Previously: **Microsoft Azure** (real-time Kafka ingestion pipelines; security infrastructure for Azure Networking), **Bloomberg** (0→1 cloud-native alerting platform — Go, Python, AWS Lambda, PostgreSQL, OpenTelemetry, Kubernetes), and **OCI Telemetry** (Kafka-based routing for Oracle's observability data plane).

On the side, I build open-source **AI-infrastructure tooling** — model routing, agent observability, cluster guardrails, and reproducible ML data pipelines — each shipped with a citable preprint (below).

```text
AI infrastructure · LLM inference & agents · Kubernetes · serverless · platform engineering · distributed systems · Kafka / streaming · observability
```

## 🚀 Projects — code ⇄ papers

*Each project pairs working code with a citable preprint — design decisions and claims written down where they can be checked.*

| Project | What it is | Paper |
|---|---|---|
| [**switchboard**](https://github.com/aivinay/switchboard) | Privacy-aware, local-first router for CLI coding agents (Codex, Claude Code) and local LLM inference — keeps sensitive prompts on-device. Benchmarked in the preprint: **62% fewer premium-agent calls** at 4.1/5 vs 4.6/5 always-premium quality, with **zero privacy leaks** | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20836918-blue)](https://doi.org/10.5281/zenodo.20836918) |
| [**agent-tracebench**](https://github.com/aivinay/agent-tracebench) | Reproducible observability, replay, and regression checks for LLM agents | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.21194993-blue)](https://doi.org/10.5281/zenodo.21194993) |
| [**kube-clusterguard**](https://github.com/aivinay/kube-clusterguard) | Static guardrails for Kubernetes AI/ML compute clusters | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.21196097-blue)](https://doi.org/10.5281/zenodo.21196097) |
| [**shardflow-ml**](https://github.com/aivinay/shardflow-ml) | Deterministic manifest, planning, and checkpoint layer for reproducible ML data pipelines | [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.21195040-blue)](https://doi.org/10.5281/zenodo.21195040) |

Also: [**ai-spend-cap-tracker**](https://github.com/aivinay/ai-spend-cap-tracker) — a sourced, public tracker of organizations capping or cutting employee AI-coding spend; the cost pressure switchboard is built for.

## 🔧 Open source

- **[OpenTelemetry](https://github.com/open-telemetry)** — [merged: `opentelemetry-instrumentation-pika` duplicate consumer-span fix](https://github.com/open-telemetry/opentelemetry-python-contrib/pull/4740)
- **[HeadRoom](https://github.com/headroomlabs-ai/headroom)** — LLM context-compression proxy; fixes across its proxy, router, and compression paths → [my merged PRs](https://github.com/headroomlabs-ai/headroom/pulls?q=is%3Apr+is%3Amerged+author%3Aaivinay)

## 🎤 Talks, publications & service

- **gRPConf North America 2026** (The Linux Foundation / CNCF) — *“gRPC Lessons From Serverless Infrastructure”* · Mountain View, CA · Sep 3, 2026 · [session](https://grpconf-north-america-2026.sessionize.com/speaker/c81cae3c-05f6-4953-bbe1-6beb209003a6)
- *Asynchronous Data Stream Ingestion in Distributed Cloud Infrastructure* — IJCTT, 2024 · [DOI](https://doi.org/10.14445/22312803/ijctt-v72i1p102)
- **IEEE Senior Member** · Panelist, IEEE Senior Member Application Review Panel
- Peer Reviewer, [IEEE Transactions on Cloud Computing](https://www.computer.org/csdl/journal/cc) · [ACM Computing Surveys](https://dl.acm.org/journal/csur) · [Journal of Open Source Software](https://joss.theoj.org/)
- Professional Member, [British Computer Society](https://www.bcs.org/) (MBCS)

## ⚙️ Stack

<div align="center">

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-C74634?style=flat-square&logo=oracle&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

**📫 Reach me:** [ai.vinaygupta@gmail.com](mailto:ai.vinaygupta@gmail.com) · [linkedin.com/in/aivinay](https://www.linkedin.com/in/aivinay/)

</div>
