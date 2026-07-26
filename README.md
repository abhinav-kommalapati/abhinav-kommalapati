[![MasterHead](https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif)](https://github.com/abhinav-kommalapati)
 
<h1 align="center">Hi 👋, I'm Abhinav Kommalapati</h1>
<h3 align="center">CS (Honors) @ UMass Amherst | Software Engineer | AI/ML & Multi-Agent Systems</h3>
 
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&center=true&vCenter=true&width=550&lines=Building+multi-agent+AI+systems;Java+%2B+Spring+Boot+%2B+AWS;LangChain%2C+RAG%2C+GPT-4%2C+Claude+Code;4.0+GPA+%C2%B7+UMass+Amherst+%2728" alt="Typing SVG" />
</p>
<p align="center">
  <a href="https://linkedin.com/in/abhinav-kommalapati"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" /></a>
  <a href="mailto:akommalapati@umass.edu"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/GPA-4.0%2F4.0-success" />
  <img src="https://img.shields.io/badge/Chancellor's%20Merit%20Scholarship-%2464K-gold" />
</p>
---
 
## 💫 About Me
 
- 🎓 **B.S. Computer Science (Honors), UMass Amherst** — Expected May 2028
- 📈 **GPA:** 4.0 / 4.0 · 4× Dean's List
- 🏆 $64,000 Chancellor's Merit Scholarship
- 🧑‍💼 VP – Theta Tau Professional Engineering Fraternity · VP of Software – AI Research Community
- 💻 Building multi-agent AI systems, RESTful microservices, and RAG-backed tools
- 🛠️ Currently: incoming SWE Intern at **New Leader Manufacturing** (Summer 2026)
- 🌍 Based in Amherst, MA · originally from Bangalore, India
---
 
## 🏗️ Professional Experience
 
<details open>
<summary><b>🔹 Incoming Software Engineering Intern — New Leader Manufacturing</b></summary>
<br>
📍 Cedar Rapids, Iowa · May 2026 – Aug 2026
 
- Engineering Python-based Apex REST API integrations for automated lead scoring and follow-up workflows using GitHub Copilot and Claude Code.
- Implementing Lightning Web Components backed by Python microservices for an internal case management tool.
- Automating CRM data synchronization across enterprise accounts via Salesforce Bulk/Streaming APIs.
</details>
<details>
<summary><b>🔹 Software Engineering Co-op — DynaPrice</b></summary>
<br>
📍 New Jersey, USA · Oct 2025 – Apr 2026
 
- Integrated GitHub Copilot and Claude Code into the full dev lifecycle, cutting feature development cycles by 40%.
- Designed and deployed Java Spring Boot microservices on AWS Lambda, cutting API latency by 30% at peak load.
- Built AWS CloudWatch dashboards with custom KPI alerting, slashing MTTR by 45%.
- Architected normalized PostgreSQL schemas powering 10,000+ monthly transactions.
</details>
<details>
<summary><b>🔹 AI & Software Engineering Intern — Vitamap Software Solutions</b></summary>
<br>
📍 Bangalore, India · Jun 2025 – Aug 2025
 
- Built Selenium WebDriver automation pipelines in CI/CD, achieving a 100% test pass rate and cutting manual QA time by 75%.
- Built an OpenAI GPT-3 recommendation engine to auto-configure 1,000+ widgets, saving $10K+ annually.
- Designed React dashboard components adopted by 200+ daily active users.
</details>
<details>
<summary><b>🔹 AI Research Intern — Incognito Blueprints</b> (advised by Prof. Timothy Richards, UMass Amherst)</summary>
<br>
📍 New York, USA · May 2024 – Jul 2024
 
- Built a Python/SQL research backend supporting 300+ test users studying online student engagement.
- Fine-tuned a local Ollama LLM on engagement data to power an adaptive AI tutor, improving dropout prediction accuracy by 20%+.
- Co-authored a 13-page published research paper on predictive AI in education.
</details>
---
 
## 🚀 Systems I've Architected
 
<div align="center">
*Each project below is treated as a real production system — not a toy script.*
 
</div>
<br>
<table width="100%">
<tr>
<td width="100%">
### 🤖 AgentForce Clone
**Autonomous multi-agent sales orchestration platform**
 
<img src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/GPT--4-412991?logo=openai&logoColor=white"/> <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?logo=awslambda&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black"/>
 
```
┌─────────────┐    tool-calling     ┌──────────────────┐
│  LangChain  │ ──────────────────▶ │  CRM Lookup Agent │
│ Orchestrator│                     └──────────────────┘
│  (GPT-4)    │ ──────────────────▶ ┌──────────────────┐
└─────────────┘                     │ Lead-Scoring Agent│
      │                             └──────────────────┘
      ▼                             ┌──────────────────┐
┌─────────────┐ ──────────────────▶ │ Email-Draft Agent │
│  Validation │                     └──────────────────┘
│  Pipeline   │
└─────────────┘
```
 
| What it does | How |
|---|---|
| Autonomous lead scoring, CRM lookup & email drafting | Multi-agent orchestration in Java/Spring Boot via LangChain tool-calling |
| Auto-scaling agent execution | Deployed on AWS Lambda + API Gateway, S3 log persistence |
| Sub-10ms shared memory | Redis (ElastiCache) caching layer |
| 97%+ factual accuracy | Multi-layer LLM validation: strict JSON schemas + hallucination detection + few-shot refinement |
| Real-time UI | React frontend streaming GPT-4 responses live, sub-50ms PostgreSQL lookups across 100K+ records |
 
**Scale tested:** 500+ simulated sales interactions · fully Dockerized, one-command deploy
 
</td>
</tr>
<tr>
<td width="100%">
### 🔄 OrgBridge
**Event-driven Salesforce multi-org data sync engine**
 
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/Salesforce-00A1E0?logo=salesforce&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?logo=awslambda&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black"/>
 
```
 Org A ──┐
         │  Change Data Capture / Streaming API
 Org B ──┼──────────────▶ Spring Boot Job Orchestrator
         │                (Bulk API 2.0 batched upserts)
 Org C ──┘                        │
                                   ▼
                    Conflict Resolution Layer
              (timestamp last-write-wins + dead-letter queue)
                                   │
                                   ▼
                     PostgreSQL  +  React live dashboard
```
 
| What it does | How |
|---|---|
| Cross-org record sync at scale | Salesforce Change Data Capture + Streaming API, 50,000+ events/day, <5s replication lag |
| 80% fewer API calls than REST | Bulk API 2.0 batched upserts, 10,000+ records/batch, zero governor-limit violations |
| 99.97% sync reliability | Timestamp-based conflict resolution + PostgreSQL dead-letter queue + automated retry |
| Live observability | React dashboard surfacing sync lag, throughput, and error rate in real time |
 
**Scale tested:** 100K+ monthly transactions monitored via AWS CloudWatch
 
</td>
</tr>
<tr>
<td width="100%">
### 🌳 Agent Version Control
**"Git for AI agents" — versioning system for agent definitions**
 
<img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/AWS_S3-569A31?logo=amazons3&logoColor=white"/> <img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white"/> <img src="https://img.shields.io/badge/React_Flow-FF0072?logo=react&logoColor=white"/>
 
A concept system to snapshot, diff, rollback, and branch entire agent definitions — system prompt, model, tools, memory, retrieval config — as versioned artifacts, with React Flow rendering the agent's full lineage graph like a commit tree.
 
</td>
</tr>
<tr>
<td width="100%">
### 🧠 ML Mini Projects Collection
**Curated end-to-end machine learning problem set — classification, regression & clustering**
 
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white"/> <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/NLP-4B8BBE?logo=python&logoColor=white"/>
 
Every project follows the same pipeline discipline — raw data → preprocessing → model training → evaluation — applied across three ML problem families:
 
```
             ┌────────────────────┐
  Clustering │ Customer Segmentation (K-Means)
             └────────────────────┘
             ┌────────────────────┐
             │ Diabetes Prediction
Classifi-    │ Heart Disease Prediction
cation       │ Rock vs Mine (sonar signals)
             │ Spam Mail Detection (NLP)
             │ Loan Approval Prediction
             └────────────────────┘
             ┌────────────────────┐
  Regression │ Sales Forecasting
             └────────────────────┘
```
 
| Project | Problem | ML Type |
|---|---|---|
| 💳 Customer Segmentation | Group customers by purchasing behavior | Clustering (K-Means) |
| 🩺 Diabetes Prediction | Predict diabetes from health metrics | Classification |
| ❤️ Heart Disease Prediction | Predict presence of heart disease from patient data | Classification |
| 🎧 Rock vs Mine Prediction | Classify sonar signals as rock or mine | Classification |
| 📈 Sales Prediction | Forecast future sales from historical data | Regression |
| ✉️ Spam Mail Prediction | Detect spam emails using NLP | Classification |
| 🏦 Loan Prediction | Predict loan approval from applicant info | Classification |
 
</td>
</tr>
<tr>
<td width="100%">
### ✅ Data Validation Web Application
**Glass-morphism validation engine with real-time feedback**
 
<img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white"/> <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/Animate.css-FF6B6B?logo=css3&logoColor=white"/>
 
A Flask backend paired with a Tailwind + glass-morphism frontend that validates six data types in real time — no page reloads, no waiting for a submit button.
 
```
  Input ──▶ Flask Validation Engine ──▶ Live UI Feedback
              │
              ├─ Name / Email / Mobile
              ├─ Password  ──▶ strength meter
              ├─ IP Address / Date
              └─ File Upload (.xlsx .csv .txt .log)
```
 
| Feature | Detail |
|---|---|
| Real-time validation | Instant feedback per field as the user types, no full-page submit cycle |
| Password strength meter | Live-updating strength indicator with visual progress bar |
| File upload validation | Accepts and validates `.xlsx`, `.csv`, `.txt`, `.log` |
| UI polish | Glass-morphism cards, gradient effects, animated transitions, interactive tooltips |
 
</td>
</tr>
<tr>
<td width="100%">
### 📲 Automated SMS Notification System
**Twilio-powered bulk messaging service**
 
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Twilio-F22F46?logo=twilio&logoColor=white"/>
 
A Python service that sends templated SMS notifications to multiple recipients through Twilio's API, with credentials kept entirely out of source control via environment-based configuration.
 
```
.env (Twilio SID / Auth Token) ──▶ Twilio Client ──▶ Recipient List
                                                        (fan-out send)
```
 
| Feature | Detail |
|---|---|
| Multi-recipient send | One call, multiple phone numbers, customizable message templates |
| Secure config | Credentials and phone numbers loaded from `.env`, never hardcoded |
| Simple entry points | `sendSms.py` for one-off sends, `useTwilio.py` for reusable Twilio functions |
 
</td>
</tr>
</table>
---
 
## 💻 Tech Stack
 
**Languages**
 
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" height="40"/>
</p>
**Frontend & Backend**
 
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/graphql/graphql-plain.svg" width="40" height="40"/>
</p>
**Cloud, DB & DevOps**
 
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="40" height="40"/>
</p>
**AI/ML & LLM Tools**
 
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="40" height="40"/>
</p>
<p align="left">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI%20GPT--4-412991?logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-RetrievalAugmentedGen-blueviolet" />
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Cursor-000000?logo=cursor&logoColor=white" />
</p>
---
 
<details>
<summary><b>🔥 Currently Learning & Building</b></summary>
<br>
- 🤖 Deeper multi-agent orchestration patterns (LangChain, tool-calling, RAG pipelines)
- 🧠 Fine-tuning and evaluating local LLMs (Ollama)
- 🏗️ Expanding OrgBridge and AgentForce Clone with new agent capabilities
- 🏆 Sharpening DS&A fundamentals on LeetCode
</details>
<details>
<summary><b>📜 Certifications</b></summary>
<br>
- SWE: Data Structures & Algorithms Deep Dive Using Java (Udemy, 2025)
- Python OOP (Udemy, 2025)
- Postman & API Testing (Udemy, 2025)
- OpenAI GPT-3 for Developers (Infosys, 2025)
- Generative Models for Developers (Infosys, 2025)
- Principles of Generative AI (Infosys, 2025)
- Complete ML & Data Science with Python (Udemy, 2025)
- Deep Learning for Developers (Infosys, 2025)
</details>
---
 
## 🌐 Connect with Me
 
<p>
  <a href="https://linkedin.com/in/abhinav-kommalapati">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:akommalapati@umass.edu">
    <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>
<p align="center">
  <img src="https://media.giphy.com/media/jpVnC65DmYeyRL4LHS/giphy.gif" width="80"/>
</p>
