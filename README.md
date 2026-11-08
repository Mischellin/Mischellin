<div align="center">

# Mikhail Sidorkin

### **Senior Technical Product Owner · Solution Architect · Staff Platform & Backend Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sidorkinmv/)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/michael_sdkn)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sidorkin.mikhail.v@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Mischellin-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mischellin)

**📍 Belarus · 🌐 Open to Worldwide Remote (B2B Contractor / HTP IT Company)**

---

</div>

## 👨‍💻 Executive Summary

Technical Product Owner & Solution Architect with **6+ years** of building and operating high-load production platforms across ed-tech, fintech, and IoT. 

I bridge the gap between product strategy and deep hands-on systems engineering: I own the product roadmap, design resilient distributed architectures, and ship production code alongside infrastructure. Pioneer of **AI-augmented engineering workflows**, leveraging multi-agent pipelines with automated peer-reviews by models of different families. Founder & CTO at **SDKN Digital**.

---

## ⚡ Highlights & Key Production Impact

* **🔥 Disaster Recovery at National Scale (7.7M users, 5 days):**  
  Led the emergency recovery program of a national educational platform when its cloud data centre burned down (Oct 2026). Rebuilt 25+ services into K2 Cloud with 100% GitOps (Flux), restored a 7.66M SSO database with zero loss, migrated 403 ClickHouse tables (2.17B rows) with 0 mismatches, and coordinated 436 merge requests to get the site back online in **5 days**.
* **🚀 Extreme High-Load Architecture:**  
  Scaled production infrastructure for **60,000 concurrent live-stream viewers** (≥2,500 RPS, p99 < 250ms). Designed a 14-VM staging environment mirroring production capable of sustaining **5,200 RPS** with zero auth errors across 481k requests.
* **🔐 Enterprise Identity & SSO (Keycloak):**  
  Architected migration from legacy Django auth to Keycloak SSO (7.66M accounts) with phone-first OTP (SMS, voice, messenger) and Kafka event sync. Eliminated a recurring login error (7–9k daily failures → 0) and repaired ~150k account link anomalies.
* **🤖 AI-Augmented Engineering & Tooling:**  
  Created `dev-harness` (developer workstation running coding agents in isolated worktrees with cross-model automated reviews) and `OpsBrain` (safe MCP server for infrastructure management with strict plan/apply verification).

---

## 🛠️ Technology Stack & Architecture Arsenal

<table>
  <tr>
    <td width="20%"><b>Core & Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
      <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white" alt="Bash" />
    </td>
  </tr>
  <tr>
    <td><b>Platform & Cloud</b></td>
    <td>
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
      <img src="https://img.shields.io/badge/k3s-FFC61C?style=flat-square&logo=rancher&logoColor=black" alt="k3s" />
      <img src="https://img.shields.io/badge/Flux_CD-4265FD?style=flat-square&logo=flux&logoColor=white" alt="Flux" />
      <img src="https://img.shields.io/badge/Argo_CD-EF6B48?style=flat-square&logo=argo&logoColor=white" alt="ArgoCD" />
      <img src="https://img.shields.io/badge/Cilium_CNI-F05A24?style=flat-square&logo=cilium&logoColor=white" alt="Cilium" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/Proxmox_HA-E57000?style=flat-square&logo=proxmox&logoColor=white" alt="Proxmox" />
    </td>
  </tr>
  <tr>
    <td><b>Data & Streaming</b></td>
    <td>
      <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white" alt="Kafka" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black" alt="ClickHouse" />
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
      <img src="https://img.shields.io/badge/Debezium_CDC-009B8E?style=flat-square&logo=apache&logoColor=white" alt="Debezium" />
      <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" alt="Elasticsearch" />
    </td>
  </tr>
  <tr>
    <td><b>Security & Observability</b></td>
    <td>
      <img src="https://img.shields.io/badge/Keycloak-008B8B?style=flat-square&logo=redhat&logoColor=white" alt="Keycloak" />
      <img src="https://img.shields.io/badge/HashiCorp_Vault-000000?style=flat-square&logo=vault&logoColor=white" alt="Vault" />
      <img src="https://img.shields.io/badge/Kyverno-2C5E8A?style=flat-square&logo=linux-foundation&logoColor=white" alt="Kyverno" />
      <img src="https://img.shields.io/badge/VictoriaMetrics-6B3FA0?style=flat-square&logo=prometheus&logoColor=white" alt="VictoriaMetrics" />
      <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
      <img src="https://img.shields.io/badge/Loki_%26_Tempo-E5A00D?style=flat-square&logo=grafana&logoColor=white" alt="Loki Tempo" />
    </td>
  </tr>
  <tr>
    <td><b>AI & Agentic Systems</b></td>
    <td>
      <img src="https://img.shields.io/badge/Model_Context_Protocol_(MCP)-8A2BE2?style=flat-square&logo=anthropic&logoColor=white" alt="MCP" />
      <img src="https://img.shields.io/badge/Multi--Agent_Pipelines-00C49F?style=flat-square&logo=openai&logoColor=white" alt="Agents" />
      <img src="https://img.shields.io/badge/GitOps_Automation-2088FF?style=flat-square&logo=github&logoColor=white" alt="GitOps" />
    </td>
  </tr>
</table>

---

## 🚀 Featured Projects & Innovations

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 dev-harness</h3>
      <p><b>Developer workstation for AI-augmented software engineering.</b> Runs autonomous coding agents (Claude Code, Codex, Copilot, OpenCode) in isolated Git worktrees via ACP, enforcing mandatory peer reviews by an automated reviewer from a different LLM family.</p>
      <p><code>Architecture</code> · <code>Multi-Agent</code> · <code>ACP</code> · <code>Git Worktrees</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ OpsBrain</h3>
      <p><b>Safe MCP server for infrastructure control by AI agents.</b> Replaces raw shell execution with audited command templates across OpenTofu, Ansible, Kubernetes, and Prometheus. Enforces strict two-phase (plan → apply bound to hash) workflows.</p>
      <p><code>MCP</code> · <code>Kubernetes</code> · <code>OpenTofu</code> · <code>Zero-Trust</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💬 veche</h3>
      <p><b>Slack-like Matrix client for teams</b> built with Flutter. Integrates decentralized channel messaging, video meetings via Jitsi, and CalDAV calendaring into a single unified client.</p>
      <p><code>Flutter</code> · <code>Matrix Protocol</code> · <code>Jitsi</code> · <code>CalDAV</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>📑 OkyDoky</h3>
      <p><b>Intelligent document processing for accountants via Telegram.</b> Handles document intake, OCR extraction (Apple Vision), automated AI classification, and direct export to 1C accounting platforms.</p>
      <p><code>Python</code> · <code>OCR</code> · <code>Telegram API</code> · <code>1C Integration</code></p>
    </td>
  </tr>
</table>

---

## 📊 Engineering Cadence & Production Scale

<table width="100%">
  <tr>
    <td width="25%" align="center">
      <h3>7.66M+</h3>
      <p><b>Enterprise SSO Accounts</b><br/>Zero data loss in disaster recovery</p>
    </td>
    <td width="25%" align="center">
      <h3>5,200+ RPS</h3>
      <p><b>Load Ceiling Tested</b><br/>Auth & streaming production scale</p>
    </td>
    <td width="25%" align="center">
      <h3>100% GitOps</h3>
      <p><b>Flux CD & Kyverno</b><br/>Zero-downtime multi-AZ clusters</p>
    </td>
    <td width="25%" align="center">
      <h3>1,300+ PRs</h3>
      <p><b>AI-Augmented Delivery</b><br/>Multi-agent delivery with cross-model peer review</p>
    </td>
  </tr>
</table>

---

## 🤝 Let's Connect & Build

I am open to discussions regarding:
* **Staff / Lead Platform Engineer** and **Cloud Solution Architect** roles.
* **Senior Technical Product Owner** positions for core/infrastructure teams.
* **Consulting & B2B contracting** for high-load platforms, disaster recovery audits, and AI agentic delivery workflows.

📫 **Reach out directly:**
* 💬 **Telegram:** [@michael_sdkn](https://t.me/michael_sdkn)
* 💼 **LinkedIn:** [/in/sidorkinmv](https://www.linkedin.com/in/sidorkinmv/)
* 📧 **Email:** [sidorkin.mikhail.v@gmail.com](mailto:sidorkin.mikhail.v@gmail.com)
