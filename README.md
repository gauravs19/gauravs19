# Gaurav Sharma

**Solutions Architect & Engineering Leader.** I turn complex business problems into resilient, cost-optimized platforms — and I build the tools that make good architecture repeatable.

Eighteen-plus years across financial services, payments, data platforms, and industrial IoT. I design cloud-native, event-driven systems that hold up at real scale — 100K+ connected devices, 300K+ managed assets, millions of events an hour — and take them end to end, from CXO discovery workshops to production SLAs, with delivery across the US, UK, and Japan.

### How I work

- **Architecture should execute, not just advise.** A model that can't become requirements, code, and a review gate is an opinion, not a design.
- **Cost is a quality attribute.** Build-vs-buy, FinOps, and TCO belong in the architecture, not the invoice.
- **The non-functionals *are* the design.** Scalability, availability, fault tolerance, and observability decide whether a system survives production.
- **Domain before framework.** Clear bounded contexts age better than clever technology.

### Currently exploring

Agentic AI for architecture and delivery, LLM/RAG pipelines, and applied ML for predictive maintenance — and making enterprise-architecture practice more open, concrete, and tool-assisted.

**[Portfolio & case studies](https://gauravs19.github.io/portfolio/)**　·　**[CV](https://gauravs19.github.io/portfolio/Gaurav_Sharma_CV.pdf)**　·　**[LinkedIn](https://www.linkedin.com/in/gauravs19/)**

---

## Tools & field guides for enterprise architects

Most architecture guidance stops at the slide. I tend to build the opposite — small, open tools and concrete guides that turn principles into something you can run, score, and ship. Each one came out of a real gap in enterprise delivery: discovery, requirements, non-functionals, governance, observability, and presales.

<table>
  <tr align="center">
    <td width="25%"><a href="https://gauravs19.github.io/archpilot/"><img src="./assets/archpilot.png" alt="Archpilot"/><br/><b>Archpilot</b></a><br/><sub>Requirement → HLD/LLD → scored review</sub></td>
    <td width="25%"><a href="https://gauravs19.github.io/nfr-advisor/"><img src="./assets/nfr-advisor.png" alt="NFR Advisor"/><br/><b>NFR Advisor</b></a><br/><sub>Quality attributes, trade-offs & scenarios</sub></td>
    <td width="25%"><a href="https://gauravs19.github.io/enterprise-architecture-skill/"><img src="./assets/ea-skill.png" alt="EA Skill"/><br/><b>EA Skill</b></a><br/><sub>C4 · ArchiMate · TOGAF · arc42, as code</sub></td>
    <td width="25%"><a href="https://gauravs19.github.io/iiot-reference-architecture/"><img src="./assets/iiot-ref-arch.png" alt="IIoT Reference Architecture"/><br/><b>IIoT Reference Arch.</b></a><br/><sub>Edge-to-cloud industrial blueprint</sub></td>
  </tr>
  <tr align="center">
    <td width="25%"><a href="https://gauravs19.github.io/cadex/"><img src="./assets/cadex.png" alt="CADEX"/><br/><b>CADEX</b></a><br/><sub>Presales risk & deal qualification</sub></td>
    <td width="25%"><a href="https://gauravs19.github.io/presales-playbook/"><img src="./assets/presales.png" alt="Presales Playbook"/><br/><b>Presales Playbook</b></a><br/><sub>Translating architecture into value</sub></td>
    <td width="25%"><a href="https://pgvitals.github.io/"><img src="./assets/pgvitals.png" alt="pgvitals"/><br/><b>pgvitals</b></a><br/><sub>PostgreSQL performance diagnostics</sub></td>
    <td width="25%"></td>
  </tr>
</table>

---

## Selected work, by theme

<details open>
<summary><b>Architecture-as-code & governance</b></summary>

<br/>

| Project | What it is | |
|---|---|---|
| **[archpilot](https://github.com/gauravs19/archpilot)** ⭐8 | An agentic pipeline that takes a single requirement and produces deep discovery, EARS-compliant requirements, an HLD, an LLD per service, and a scored guardrail review — all enforced by 36 enterprise rule files. | [demo](https://gauravs19.github.io/archpilot/) |
| **[archpilot-reviewer](https://github.com/gauravs19/archpilot-reviewer)** ⭐2 | A GitHub Action that runs architecture governance on every pull request, flagging drift from your standards before it reaches `main`. | — |
| **[archpilot-cli](https://github.com/gauravs19/archpilot-cli)** | A command-line scaffolder that generates enterprise-architecture documents from the Archpilot standards library so teams start consistent. | — |
| **[enterprise-architecture-skill](https://github.com/gauravs19/enterprise-architecture-skill)** ⭐1 | A Claude Code skill that produces C4 + Structurizr, ArchiMate, TOGAF ADM, and arc42 artifacts — diagrams and decision records authored as code. | [demo](https://gauravs19.github.io/enterprise-architecture-skill/) |
| **[nfr-advisor](https://github.com/gauravs19/nfr-advisor)** | Takes a system's context, ranks the non-functional requirements that apply, surfaces the trade-offs between them, generates testable scenarios, and exports the result as code. | [demo](https://gauravs19.github.io/nfr-advisor/) |
| **[cadex](https://github.com/gauravs19/cadex)** | An eight-axis risk model for presales: qualify a deal, match an engagement strategy, and pass a 42-point quality gate before committing. | [demo](https://gauravs19.github.io/cadex/) |

</details>

<details>
<summary><b>Applied AI & machine learning</b></summary>

<br/>

| Project | What it is |
|---|---|
| **[iiot-predictive-maintenance](https://github.com/gauravs19/iiot-predictive-maintenance)** | Notebook-based predictive maintenance on real datasets (AI4I 2020, NASA C-MAPSS): remaining-useful-life prediction, failure classification, and autoencoder anomaly detection in PyTorch. |
| **[iiot-ai-rag](https://github.com/gauravs19/iiot-ai-rag)** | Two retrieval patterns built from scratch — document RAG over manuals and FMEA, and case-based RAG over sensor signatures — the GenAI companion to the predictive-maintenance work. |

</details>

<details>
<summary><b>Reference architectures & blueprints</b></summary>

<br/>

| Project | What it is | |
|---|---|---|
| **[iiot-reference-architecture](https://github.com/gauravs19/iiot-reference-architecture)** | An end-to-end reference architecture for industrial and enterprise IoT — edge to cloud, OT–IT data contracts, ingestion, storage, and analytics — drawn from delivering platforms at 100K-device scale. | [demo](https://gauravs19.github.io/iiot-reference-architecture/) |
| **[cloud-native-observability](https://github.com/gauravs19/cloud-native-observability)** | A vendor-neutral catalog of what to measure and alert on across every layer, with SLO guidance and an operating methodology you can adopt as-is. | — |

</details>

<details>
<summary><b>Writing & playbooks</b></summary>

<br/>

| Resource | What it is |
|---|---|
| **[presales-playbook](https://github.com/gauravs19/presales-playbook)** | The missing manual for technical sellers — turning system architecture into commercial value through discovery, deal orchestration, and architecture defense. ([read](https://gauravs19.github.io/presales-playbook/)) |
| **[cloud-native-observability](https://github.com/gauravs19/cloud-native-observability)** | A reference catalog meant to be read end-to-end before you instrument a single service. |

</details>

<details>
<summary><b>Developer tools & utilities</b></summary>

<br/>

| Project | What it is |
|---|---|
| **[viewer2pdf](https://github.com/gauravs19/viewer2pdf)** | A Node + Playwright CLI that captures canvas- and image-based document viewers — the kind that block download and print — into a clean PDF. |
| **[gs-theme](https://github.com/gauravs19/gs-theme)** | A zero-dependency, zero-build GitHub Pages landing template: dark hero, sticky nav, five accent presets. |

</details>

<details>
<summary><b>Built for family & learning</b></summary>

<br/>

| Project | What it is |
|---|---|
| **[Little Players](https://littleplayers.github.io/)** | A hub of 23 free, colorful learning games for kids across eight categories — built with my own kids as the QA team. ([org](https://github.com/LittlePlayers)) |

</details>

---

## Tech I work with

<p>
  <img src="https://img.shields.io/badge/Azure-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2CA5E0?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apache-spark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white"/>
  <img src="https://img.shields.io/badge/Delta_Lake-00ADD4?style=flat-square&logo=databricks&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
</p>

---

<sub>Working on platform scaling, an enterprise AI rollout, or industrial IoT? &nbsp;<a href="https://www.linkedin.com/in/gauravs19/">Let's talk →</a></sub>
