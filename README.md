<div align="center">

# Hey, I'm Sikandar 👋

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=14B8A6&center=true&vCenter=true&width=680&lines=Engineer+first.+13%2B+years+shipping+software.;Building+agentic+AI+that+runs+in+production.;GraphRAG+%C2%B7+LangGraph+%C2%B7+Bedrock+AgentCore;Teaching+IB+Computer+Science+since+2017." alt="Engineer first. Building agentic AI that runs in production." />

**AI Delivery Lead @ AiFA Labs** · IIIT Basar CSE grad · IB CS mentor · Hyderabad 🇮🇳

I started as an engineer and never stopped being one. These days I lead teams building AI agents,<br>
but I still code most days, because that's how I understand what we're shipping.

<a href="https://linkedin.com/in/dearsikandarkhan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://dearsikandarkhan.medium.com/"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
<a href="https://ibcswithsikandar.netlify.app/"><img src="https://img.shields.io/badge/Teaching-IB_Computer_Science-F59E0B?style=for-the-badge&logo=bookstack&logoColor=white" alt="IB Computer Science teaching"/></a>
<a href="https://dearsikandarkhan.github.io/"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
<img src="https://komarev.com/ghpvc/?username=dearsikandarkhan&style=for-the-badge&color=14B8A6&label=Profile+views" alt="Profile views"/>

</div>

---

## ⚡ Daily activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=dearsikandarkhan&theme=dark&hide_border=true&background=0D1117&ring=14B8A6&fire=F59E0B&currStreakLabel=14B8A6">
  <img src="https://streak-stats.demolab.com?user=dearsikandarkhan&theme=default&hide_border=true&ring=14B8A6&fire=F59E0B&currStreakLabel=0F766E" alt="GitHub streak" />
</picture>

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=dearsikandarkhan&bg_color=0D1117&color=E6EDF3&line=14B8A6&point=F59E0B&area=true&area_color=14B8A6&hide_border=true&custom_title=Contributions%20over%20the%20last%2031%20days" alt="Contribution activity graph" width="100%"/>

<br>

<img src="https://github-readme-stats.vercel.app/api?username=dearsikandarkhan&show_icons=true&hide_border=true&theme=transparent&title_color=14B8A6&icon_color=14B8A6&include_all_commits=true" alt="GitHub stats" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dearsikandarkhan&layout=compact&hide_border=true&theme=transparent&title_color=14B8A6&langs_count=8" alt="Top languages" height="165"/>

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dearsikandarkhan/dearsikandarkhan/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dearsikandarkhan/dearsikandarkhan/output/github-contribution-grid-snake.svg">
  <img src="https://raw.githubusercontent.com/dearsikandarkhan/dearsikandarkhan/output/github-contribution-grid-snake.svg" alt="Snake eating my contribution graph" />
</picture>

</div>

## 🛠️ What I'm building right now

The organisation's first production AI agent. This is roughly how it's put together:

```mermaid
flowchart LR
    A[Change request] --> B[LangGraph agent]
    B -->|retrieve| C[(GraphRAG<br/>Neo4j + OpenAI embeddings)]
    B -->|act| D[SAP Solution Manager]
    B --> E{Evals & guardrails}
    E -->|pass| F[Output]
    E -->|uncertain| G[Human review]
    B -.traces.-> H[Langfuse]
```

<sub>Runs on AWS Bedrock AgentCore. It automates SAP Change Request / Change Order processing, cutting each request from about 10 hours to about 3.</sub>

**On my own time:**

- 🔍 **[ai-readiness-lint](https://github.com/dearsikandarkhan/ai-readiness-lint)** is a Node.js CLI that statically checks an AI agent repo for production readiness: evals, guardrails, HITL, observability, cost limits and more. It scores 0–100, runs in CI, and emits a badge.
- 🎙️ **Voice agents on a Raspberry Pi**: real-time speech in, agent reply out, on hardware that fits in a palm.
- 📦 **NPM packages** for CSRF prevention and dependency analysis, plus an open-source resume platform.

## 🧭 Recent work

| Years | Role | What I built |
|---|---|---|
| 2026 – now | AI Delivery Lead · **AiFA Labs** | Production agentic AI: GraphRAG, LangGraph, Langfuse, Bedrock AgentCore |
| 2022 – 26 | Technical Manager · **DocOnline Health** | Mental-health app (35+ features), Stepathon for 20K+ users, SonarCloud + VAPT + ISO 27001-aligned security |

## 🧰 Toolbox

**AI / Agents** &nbsp;
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Bedrock](https://img.shields.io/badge/Bedrock_AgentCore-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square)

**Code** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

**Infra** &nbsp;
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)

## 🎓 Teaching

<table>
<tr>
<td width="65%" valign="top">

I've mentored **IB Computer Science** students since 2017, across both HL and SL.

- Core theory and programming in **Python & Java**
- **Internal Assessment**: picking a real client, then designing, building and testing the project
- **Extended Essay**: research questions, methodology, structure

Eleven years of building real software is what I bring to the classroom. Students see what good code looks like in practice, not just in the textbook. The IA and EE always remain the student's own work.

I also mentor student teams at **Smart India Hackathon**.

</td>
<td width="35%" align="center" valign="middle">

<a href="https://ibcswithsikandar.netlify.app/">
  <img src="https://img.shields.io/badge/ibcswithsikandar-Visit_site-F59E0B?style=for-the-badge&logo=netlify&logoColor=white" alt="Teaching site"/>
</a>

<sub>Syllabus map · IA kit · key definitions · study materials</sub>

</td>
</tr>
</table>

## ✍️ Latest on Medium

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

## 🏅 Bits & badges

- 🥇 1st Prize, Smart Health IoT track, **Asia-Pacific Hackathon 2018** (New Zealand)
- 🏆 **Capgemini Innovative Startup Award**
- ☁️ Google Cloud Architect, Kubernetes Engine Specialization · 🧩 CSM · CSPO
- 🎓 **B.Tech, Computer Science & Engineering — IIIT Basar (RGUKT)**, graduated 2014
- 📘 Executive education in Product Management, **ISB** (2024)

<div align="center">
<sub>Usually found somewhere between a LangGraph trace and a Raspberry Pi.</sub>
</div>
