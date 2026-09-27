<p align="center">
  <img src="assets/banner.svg" alt="Ömer Aydemir — Machine Learning Engineer, LLM / RAG Systems" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/omeraydemir"><img src="https://img.shields.io/badge/LinkedIn-omeraydemir-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://omeraydmr.github.io"><img src="https://img.shields.io/badge/Portfolio-omeraydmr.github.io-111827?style=flat-square&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:omer.aydemir078@gmail.com"><img src="https://img.shields.io/badge/Email-omer.aydemir078-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="#-indie-ios-apps"><img src="https://img.shields.io/badge/App_Store-2_apps_live-0D96F6?style=flat-square&logo=appstore&logoColor=white" alt="App Store"></a>
</p>

I build LLM systems that run in production, not just in notebooks. I'm a **Machine Learning Engineer at Garanti BBVA Teknoloji**, applying AI/ML to core banking workflows. Before that I spent two and a half years at **Mercedes-Benz Otomotiv**, first as a backend engineer and then as an AI engineer, shipping conversational agents and RAG platforms that handled **10,000+ transactions a month**.

Outside work I design, build and ship **native iOS apps on my own**, using AI coding agents to move fast without cutting corners on tests.

<!-- Uncomment when you want this public:
🌍 Open to ML / AI Engineer roles in Europe (EU Blue Card–eligible).
-->

## 🧠 AI systems I've shipped

| | What it is | Stack |
|---|---|---|
| **SWT AI Chatbot**<br><sub>Mercedes-Benz USA</sub> | Agentic assistant for SAP operations in Microsoft Teams: MSRP queries, purchase-order actions, consignment reversals. Circuit breakers, Redis session cache, MongoDB persistence. | LangGraph · GPT-4 · FastAPI · Azure Bot Service · Kubernetes |
| **Insight Generator**<br><sub>Mercedes-Benz</sub> | RAG platform for natural-language Q&A over Excel, PowerPoint and PDF files, with MMR multi-turn retrieval, KPI detection and Azure Data Lake integration. | Docling OCR · ChromaDB · GPT-5 · Python |
| **Ontll**<br><sub>Mercedes-Benz</sub> | Production RAG chatbot over PDF knowledge bases; modernized a legacy system for speed. | LangChain · Azure OpenAI |
| **Centralized Configuration Service**<br><sub>Mercedes-Benz</sub> | Global environment-configuration platform with versioning for complex data blocks, delivered with GitOps. | Java · Spring Boot · Kafka · ArgoCD · GitHub Actions |

<sub>Company code is private. Happy to walk through the architecture and trade-offs in a conversation.</sub>

## 📱 Indie iOS apps

<table>
<tr>
<td width="96" valign="top"><img src="assets/patizi-icon.png" width="80" alt="Patizi icon"></td>
<td valign="top">
<b>Patizi</b> · Vaccine reminders and health records for your pets<br>
<a href="https://apps.apple.com/tr/app/patizi/id6794602007"><img src="https://img.shields.io/badge/Download_on_the-App_Store-000000?style=flat-square&logo=apple&logoColor=white" alt="Download Patizi on the App Store"></a><br>
<sub>Region-aware vaccine schedules (TR / DE), a notification planner that never drops reminders, GPS walk tracking, widgets. Local-first: no account, no server, no analytics. Localized in 4 languages.<br>
<b>SwiftUI · SwiftData · WidgetKit · CoreLocation · StoreKit 2</b> · logic in a modular Swift package with DST- and leap-day-safe recurrence tests.</sub>
</td>
</tr>
</table>

<img src="assets/patizi-showcase.jpg" alt="Patizi screenshots: today view, pet detail, walk route" width="100%">

<table>
<tr>
<td width="96" valign="top"><img src="assets/subscker-icon.png" width="80" alt="Subscker icon"></td>
<td valign="top">
<b>Subscker</b> · A private subscription tracker<br>
<a href="https://apps.apple.com/tr/app/subscker-subscription-tracker/id6794820865"><img src="https://img.shields.io/badge/Download_on_the-App_Store-000000?style=flat-square&logo=apple&logoColor=white" alt="Download Subscker on the App Store"></a><br>
<sub>Track renewals and spending, run a “subscription checkup”, keep payment history. No bank linking, no cloud, no tracking. Lifetime Pro via in-app purchase. Localized in 4 languages.<br>
<b>SwiftUI · SwiftData · StoreKit 2 · Swift Charts · App Intents</b></sub>
</td>
</tr>
</table>

<img src="assets/subscker-showcase.jpg" alt="Subscker screenshots: home, checkup, payments" width="100%">

<table>
<tr>
<td width="96" valign="top"><img src="assets/akcem-icon.png" width="80" alt="Akçem icon"></td>
<td valign="top">
<b>Akçem</b> · Personal finance, in one place <sub>(coming soon)</sub><br>
<a href="https://omeraydmr.github.io/akcem-legal/"><img src="https://img.shields.io/badge/Status-Coming_soon_to_the_App_Store-6B7280?style=flat-square&logo=apple&logoColor=white" alt="Coming soon"></a><br>
<sub>Accounts, transactions, budgets, payment plans, portfolio and credit-card statement import (PDF). Private iCloud sync, no ads, no third-party tracking.<br>
<b>SwiftUI · SwiftData · WidgetKit · App Intents · PDFKit · Swift Charts</b> · 330+ Swift files, ~100 test files.</sub>
</td>
</tr>
</table>

<img src="assets/akcem-showcase.jpg" alt="Akçem App Store screenshots" width="100%">

## 🛰️ Open-source project: STRATYON

A strategic-intelligence platform for the Turkish market: geographic intelligence (GEOINT) heatmaps, AI-generated marketing strategies, competitor keyword-gap analysis and Turkish NLP.

| Repo | Part | Stack |
|---|---|---|
| [geoint-backend](https://github.com/omeraydmr/geoint-backend) | v1 API and intelligence engine | FastAPI · PostgreSQL + PostGIS · Redis · LangChain · OpenAI / Anthropic · GitHub Actions → AWS ECR |
| [geoint-frontend](https://github.com/omeraydmr/geoint-frontend) | v1 dashboards and maps | Next.js 15 · React 19 · TypeScript · Mapbox GL |
| [stratyonv2-backend](https://github.com/omeraydmr/stratyonv2-backend) | v2 report-analysis API | Java 21 · Spring Boot 3 · PostgreSQL · Flyway · S3 · JWT |
| [stratyonv2-frontend](https://github.com/omeraydmr/stratyonv2-frontend) | v2 web app | Next.js 16 · React 19 · TanStack Query · Zod · Tailwind |

## 🧰 Toolbox

**AI / ML**&nbsp; ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white) ![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Backend & data**&nbsp; ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Cloud & DevOps**&nbsp; ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Apps & web**&nbsp; ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) ![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=flat-square&logo=swift&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

---

<p align="center"><sub>BSc Information Systems & Technologies, Yeditepe University (honors, full scholarship) · Turkish (native), English · Istanbul</sub></p>
