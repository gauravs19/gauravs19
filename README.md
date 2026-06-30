# Gaurav Sharma

### Solution Architect & Engineering Leader
**I turn complex business problems into resilient, cost-optimized platforms — and build the tools that make good architecture repeatable.**

A versatile, mature engineer with eighteen-plus years spanning financial services, payments, data platforms, and industrial IoT — equally at home in a CXO discovery workshop, a whiteboard design session, and a production incident. I design cloud-native, event-driven systems that hold up at real scale and take them end to end, with delivery across the US, UK, and Japan.

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

<table width="100%">
  <tr align="center">
    <td width="33%"><a href="https://gauravs19.github.io/archpilot/"><img src="./assets/archpilot.png" width="100%" alt="Archpilot"/></a><br/><b>Archpilot</b><br/><sub>Requirement-to-design pipeline</sub></td>
    <td width="33%"><a href="https://gauravs19.github.io/nfr-advisor/"><img src="./assets/nfr-advisor.png" width="100%" alt="NFR Advisor"/></a><br/><b>NFR Advisor</b><br/><sub>Quality-attribute advisor</sub></td>
    <td width="33%"><a href="https://gauravs19.github.io/enterprise-architecture-skill/"><img src="./assets/ea-skill.png" width="100%" alt="EA Skill"/></a><br/><b>EA Skill</b><br/><sub>Architecture diagrams as code</sub></td>
  </tr>
</table>
<table width="100%">
  <tr align="center">
    <td width="33%"><a href="https://gauravs19.github.io/cadex/"><img src="./assets/cadex.png" width="100%" alt="CADEX"/></a><br/><b>CADEX</b><br/><sub>Presales deal qualification</sub></td>
    <td width="33%"><a href="https://gauravs19.github.io/presales-playbook/"><img src="./assets/presales.png" width="100%" alt="Presales Playbook"/></a><br/><b>Presales Playbook</b><br/><sub>Technical-selling field manual</sub></td>
    <td width="33%"><a href="https://pgvitals.github.io/"><img src="./assets/pgvitals.png" width="100%" alt="pgvitals"/></a><br/><b>pgvitals</b><br/><sub>PostgreSQL diagnostics toolkit</sub></td>
  </tr>
</table>

---

## Selected work, by theme

<details open>
<summary><b>Architecture-as-code & governance</b></summary>
<br/>
<table>
  <tr><th width="200" align="left">Project</th><th align="left">What it is</th><th width="70"></th></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/archpilot">archpilot</a></b> ⭐8</td><td valign="top">An agentic pipeline that takes a single requirement and produces deep discovery, EARS-compliant requirements, an HLD, an LLD per service, and a scored guardrail review — all enforced by 36 enterprise rule files.</td><td valign="top"><a href="https://gauravs19.github.io/archpilot/">demo</a></td></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/archpilot-reviewer">archpilot-reviewer</a></b> ⭐2</td><td valign="top">A GitHub Action that runs architecture governance on every pull request, flagging drift from your standards before it reaches <code>main</code>.</td><td valign="top">—</td></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/archpilot-cli">archpilot-cli</a></b></td><td valign="top">A command-line scaffolder that generates enterprise-architecture documents from the Archpilot standards library so teams start consistent.</td><td valign="top">—</td></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/enterprise-architecture-skill">enterprise-architecture-skill</a></b> ⭐1</td><td valign="top">A Claude Code skill that produces C4 + Structurizr, ArchiMate, TOGAF ADM, and arc42 artifacts — diagrams and decision records authored as code.</td><td valign="top"><a href="https://gauravs19.github.io/enterprise-architecture-skill/">demo</a></td></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/nfr-advisor">nfr-advisor</a></b></td><td valign="top">Takes a system's context, ranks the non-functional requirements that apply, surfaces the trade-offs between them, generates testable scenarios, and exports the result as code.</td><td valign="top"><a href="https://gauravs19.github.io/nfr-advisor/">demo</a></td></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/cadex">cadex</a></b></td><td valign="top">An eight-axis risk model for presales: qualify a deal, match an engagement strategy, and pass a 42-point quality gate before committing.</td><td valign="top"><a href="https://gauravs19.github.io/cadex/">demo</a></td></tr>
</table>
</details>

<details>
<summary><b>Applied AI & machine learning</b></summary>
<br/>
<table>
  <tr><th width="200" align="left">Project</th><th align="left">What it is</th><th width="70"></th></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/iiot-predictive-maintenance">iiot-predictive-maintenance</a></b></td><td valign="top">Notebook-based predictive maintenance on real datasets (AI4I 2020, NASA C-MAPSS): remaining-useful-life prediction, failure classification, and autoencoder anomaly detection in PyTorch.</td><td valign="top">—</td></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/iiot-ai-rag">iiot-ai-rag</a></b></td><td valign="top">Two retrieval patterns built from scratch — document RAG over manuals and FMEA, and case-based RAG over sensor signatures — the GenAI companion to the predictive-maintenance work.</td><td valign="top">—</td></tr>
</table>
</details>

<details>
<summary><b>Reference architectures & blueprints</b></summary>
<br/>
<table>
  <tr><th width="200" align="left">Project</th><th align="left">What it is</th><th width="70"></th></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/iiot-reference-architecture">iiot-reference-architecture</a></b></td><td valign="top">An end-to-end reference architecture for industrial and enterprise IoT — edge to cloud, OT–IT data contracts, ingestion, storage, and analytics — drawn from delivering platforms at 100K-device scale.</td><td valign="top"><a href="https://gauravs19.github.io/iiot-reference-architecture/">demo</a></td></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/cloud-native-observability">cloud-native-observability</a></b></td><td valign="top">A vendor-neutral catalog of what to measure and alert on across every layer, with SLO guidance and an operating methodology you can adopt as-is.</td><td valign="top">—</td></tr>
</table>
</details>

<details>
<summary><b>Writing & playbooks</b></summary>
<br/>
<table>
  <tr><th width="200" align="left">Project</th><th align="left">What it is</th><th width="70"></th></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/presales-playbook">presales-playbook</a></b></td><td valign="top">The missing manual for technical sellers — turning system architecture into commercial value through discovery, deal orchestration, and architecture defense.</td><td valign="top"><a href="https://gauravs19.github.io/presales-playbook/">read</a></td></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/cloud-native-observability">cloud-native-observability</a></b></td><td valign="top">A reference catalog meant to be read end-to-end before you instrument a single service.</td><td valign="top">—</td></tr>
</table>
</details>

<details>
<summary><b>Developer tools & utilities</b></summary>
<br/>
<table>
  <tr><th width="200" align="left">Project</th><th align="left">What it is</th><th width="70"></th></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/viewer2pdf">viewer2pdf</a></b></td><td valign="top">A Node + Playwright CLI that captures canvas- and image-based document viewers — the kind that block download and print — into a clean PDF.</td><td valign="top">—</td></tr>
  <tr><td valign="top"><b><a href="https://github.com/gauravs19/gs-theme">gs-theme</a></b></td><td valign="top">A zero-dependency, zero-build GitHub Pages landing template: dark hero, sticky nav, five accent presets.</td><td valign="top">—</td></tr>
</table>
</details>

<details>
<summary><b>Built for family & learning</b></summary>
<br/>
<table>
  <tr><th width="200" align="left">Project</th><th align="left">What it is</th><th width="70"></th></tr>
  <tr><td valign="top"><b><a href="https://github.com/LittlePlayers">Little Players</a></b></td><td valign="top">A hub of 23 free, colorful STEM-based learning games for kids across eight categories — simple, hands-on, and free to play.</td><td valign="top"><a href="https://littleplayers.github.io/">open</a></td></tr>
  <tr><td valign="top"><b><a href="https://github.com/chiranjeevis-eternal/chiranjeevis-eternal.github.io">Chiranjeevis Eternal</a></b></td><td valign="top">An interactive-fiction game set in Hindu mythology — the immortal Chiranjeevis stir as the Kali Yuga wanes. Built on the Ink narrative engine with a custom cinematic VFX layer.</td><td valign="top"><a href="https://chiranjeevis-eternal.github.io/">open</a></td></tr>
  <tr><td valign="top"><b><a href="https://github.com/kya-banaon/kya-banaon.github.io">Kya Banaon</a></b></td><td valign="top">A Hindu vegetarian family meal planner — breakfast, lunch, and dinner ideas with sattvic, kids-friendly, and seasonal filters.</td><td valign="top"><a href="https://kya-banaon.github.io/">open</a></td></tr>
</table>
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
