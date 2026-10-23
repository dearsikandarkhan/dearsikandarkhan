<!-- 👋 Reading the source? Same person, fewer emojis. Say hi on LinkedIn. -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&pause=1400&color=14B8A6&center=true&vCenter=true&width=720&lines=%24+whoami;sikandar+%E2%80%94+engineer%2C+still+shipping+daily.;%24+git+log+--since%3D2014+%7C+wc+-l;13%2B+years+of+commits+and+counting.;%24+deploy+--agent+--env%3Dprod;%E2%9C%93+agentic+AI%2C+running+in+production." alt="$ whoami — sikandar, engineer, still shipping daily" />

<a href="https://linkedin.com/in/dearsikandarkhan"><img src="https://img.shields.io/badge/linkedin-dearsikandarkhan-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://dearsikandarkhan.medium.com/"><img src="https://img.shields.io/badge/medium-writing-12100E?style=flat-square&logo=medium&logoColor=white" alt="Medium"/></a>
<a href="https://ibcswithsikandar.netlify.app/"><img src="https://img.shields.io/badge/teaching-IB_Computer_Science-F59E0B?style=flat-square&logo=bookstack&logoColor=white" alt="IB Computer Science"/></a>
<a href="https://dearsikandarkhan.github.io/"><img src="https://img.shields.io/badge/portfolio-github.io-0F172A?style=flat-square&logo=github&logoColor=white" alt="Portfolio"/></a>
<img src="https://komarev.com/ghpvc/?username=dearsikandarkhan&style=flat-square&color=14B8A6&label=views" alt="Profile views"/>

</div>

```yaml
# sikandar.yaml  ·  kubectl apply -f sikandar.yaml
apiVersion: humans/v1
kind: Engineer
metadata:
  name: sikandar-khan
  region: ap-south-2            # Hyderabad, India
  labels:
    role: technical-program-manager
    focus: agentic-ai
    mode: hands-on               # never left the codebase
spec:
  compiledAt: IIIT-Basar         # B.Tech CSE, class of 2014
  current:
    org: AiFA Labs
    building: production AI agents (GraphRAG · LangGraph · Bedrock AgentCore)
  runtimes: [python, node, typescript, java, dart]
  sideProcesses:
    - ai-readiness-lint          # OSS
    - pi-voice-agent             # Raspberry Pi
    - ib-cs-mentoring            # since 2017
  restartPolicy: Always
```

## `$ top` — what's running

```text
  PID  PROCESS                 STATE      STACK
  001  prod-agent@aifa         ● running   LangGraph · Neo4j GraphRAG · Langfuse · Bedrock AgentCore
  002  ai-readiness-lint       ● running   Node.js CLI · CI gate · SVG badge
  003  pi-voice-agent          ◐ building  Raspberry Pi · speech in → agent → speech out
  004  ib-cs-mentoring         ⏱ cron      Python · Java · IA · EE      (weekly, since 2017)
```

## `$ cat ARCHITECTURE.md` — the agent I'm shipping

```mermaid
flowchart LR
    subgraph IN[" input "]
      CR([SAP change request])
    end
    subgraph CORE[" AWS Bedrock AgentCore "]
      direction TB
      G[LangGraph<br/>state machine]
      KG[(Neo4j<br/>knowledge graph)]
      V[(OpenAI<br/>embeddings)]
      G <-->|GraphRAG| KG
      G <-->|semantic recall| V
    end
    subgraph SAFE[" production gates "]
      direction TB
      E{evals +<br/>guardrails}
      H[/human review/]
    end
    CR --> G --> E
    E -->|confident| OUT([CR / CO drafted])
    E -->|uncertain| H --> OUT
    G -.traces · cost · latency.-> LF[[Langfuse]]
```

> **Result:** SAP Solution Manager CR/CO processing went from **~10 h → ~3 h** per request. It's the organisation's first production AI agent.

## `$ ls ~/oss`

```text
ai-readiness-lint/   static linter for AI-agent repos
│                    repo ──▶ 8 governance checks ──▶ score 0–100 ──▶ CI gate + badge
│                    evals · guardrails · HITL · observability · cost limits · …
npm-packages/        CSRF prevention · dependency analysis
resume-platform/     open-source resume builder
```

👉 [**ai-readiness-lint**](https://github.com/dearsikandarkhan/ai-readiness-lint): because "is this agent ready for prod?" deserves an answer you can run in CI.

## `$ git log --graph --oneline career`

```mermaid
gitGraph
    commit id: "B.Tech CSE · IIIT Basar" tag: "2014"
    commit id: "11+ yrs shipping software"
    branch teaching
    checkout teaching
    commit id: "IB CS mentoring" tag: "2017"
    checkout main
    commit id: "DocOnline Health" tag: "2022"
    commit id: "35+ feature health app"
    commit id: "SonarCloud · VAPT · ISO 27001"
    checkout teaching
    commit id: "Smart India Hackathon mentor"
    checkout main
    commit id: "AiFA Labs" tag: "2026"
    commit id: "first prod AI agent" type: HIGHLIGHT
    merge teaching tag: "HEAD"
```

## `$ cat /proc/toolchain`

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,fastapi,nodejs,ts,java,flutter,aws,gcp,docker,kubernetes,nginx,linux,raspberrypi,githubactions&perline=14" alt="Tech stack icons" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" alt="Neo4j"/>
  <img src="https://img.shields.io/badge/Bedrock_AgentCore-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="Bedrock AgentCore"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude"/>
  <img src="https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square" alt="Langfuse"/>
  <img src="https://img.shields.io/badge/SonarCloud-F3702A?style=flat-square&logo=sonarcloud&logoColor=white" alt="SonarCloud"/>
</p>

## `$ git shortlog -s --since=today` — daily commits

<div align="center">

<img src="./profile-3d-contrib/profile-night-rainbow.svg" alt="3D contribution calendar" width="100%"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=dearsikandarkhan&theme=dark&hide_border=true&background=0D1117&ring=14B8A6&fire=F59E0B&currStreakLabel=14B8A6">
  <img src="https://streak-stats.demolab.com?user=dearsikandarkhan&theme=default&hide_border=true&ring=14B8A6&fire=F59E0B&currStreakLabel=0F766E" alt="GitHub streak" />
</picture>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=dearsikandarkhan&bg_color=0D1117&color=E6EDF3&line=14B8A6&point=F59E0B&area=true&area_color=14B8A6&hide_border=true&custom_title=commits%20%C2%B7%20last%2031%20days" alt="Contribution activity graph" width="100%"/>

<img src="https://github-readme-stats.vercel.app/api?username=dearsikandarkhan&show_icons=true&hide_border=true&theme=transparent&title_color=14B8A6&icon_color=14B8A6&include_all_commits=true&count_private=true" alt="GitHub stats" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dearsikandarkhan&layout=compact&hide_border=true&theme=transparent&title_color=14B8A6&langs_count=8" alt="Top languages" height="165"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dearsikandarkhan/dearsikandarkhan/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dearsikandarkhan/dearsikandarkhan/output/github-contribution-grid-snake.svg">
  <img src="https://raw.githubusercontent.com/dearsikandarkhan/dearsikandarkhan/output/github-contribution-grid-snake.svg" alt="Snake eating my contribution graph" />
</picture>

</div>

## `$ man ibcs` — teaching

```python
class IBComputerScience(Mentor):
    """Turning abstract CS into things students can explain, build and defend."""

    since     = 2017
    levels    = ("HL", "SL")
    languages = ("Python", "Java")
    covers    = ["core theory", "Internal Assessment", "Extended Essay", "exam prep"]
    edge      = "11+ years of production code: students see what good code looks like in practice"
    invariant = "the IA and EE are always the student's own work"
```

📚 **[ibcswithsikandar.netlify.app](https://ibcswithsikandar.netlify.app/)**: syllabus map, IA survival kit, key definitions and study materials.

## `$ tail -f medium.log`

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

## `$ cat achievements.log`

```diff
+ [2018] 1st prize · Smart Health IoT · Asia-Pacific Hackathon, New Zealand
+ [----] Capgemini Innovative Startup Award
+ [2024] Google Cloud Architect · Kubernetes Engine Specialization
+ [2024] CSM · CSPO · Scrum Alliance
+ [2024] Executive education, Product Management · ISB
```

<div align="center">

```console
$ exit 0   # see you in the commit history
```

</div>
