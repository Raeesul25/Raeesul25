<!-- HEADER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:0e75b6,100:6f42c1&text=Raeesul%20Islam&fontColor=ffffff&fontSize=46&fontAlignY=38&desc=Senior%20AI%20Engineer%20%7C%20AI%20Solution%20Architect%20%7C%20Agentic%20AI%20Specialist&descSize=16&descAlignY=60" alt="Raeesul Islam - Senior AI Engineer, AI Solution Architect, Agentic AI Specialist" />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&duration=3000&pause=1000&color=0E75B6&center=true&vCenter=true&width=760&lines=From+business+problem+to+production+AI+system;Solution+Architecture+%C2%B7+Agentic+AI+%C2%B7+MCP+%C2%B7+Advanced+RAG;Multimodal+Document+Intelligence+%C2%B7+Voice+AI;Enterprise+integrations+that+actually+ship)](https://github.com/Raeesul25)

**4+ years** building production AI · **EraBiz Solutions** · Colombo, Sri Lanka 🇱🇰

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raeesul-islam)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:raeesulislam25@gmail.com)
![Consulting](https://img.shields.io/badge/Consulting-AI%20Solutions%20%C2%B7%20AI%20Agents%20%C2%B7%20Agentic%20Systems-6f42c1?style=for-the-badge)

<img src="https://komarev.com/ghpvc/?username=raeesul25&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />

</div>

---

## 👋 About

I take an **AI business problem**, design the **solution architecture**, and deliver a **production-grade system end to end**—from technical discovery, deterministic guardrails, and enterprise integrations through deployment and cost optimisation. I also evaluate models and architectures, and mentor engineering teams along the way.

<div align="center">

<table>
  <tr>
    <td align="center">💼<br><b>Business problem</b></td>
    <td align="center">➜</td>
    <td align="center">🔍<br><b>Technical discovery</b></td>
    <td align="center">➜</td>
    <td align="center">🏗️<br><b>Solution architecture</b></td>
    <td align="center">➜</td>
    <td align="center">⚙️<br><b>Build &amp; integrate</b></td>
    <td align="center">➜</td>
    <td align="center">🚀<br><b>Deploy &amp; optimise</b></td>
  </tr>
</table>

</div>

---

## ⚡ Impact

<div align="center">

<table>
  <tr>
    <th align="center">&gt;99%</th>
    <th align="center">~$0.012</th>
    <th align="center">&lt;5s</th>
    <th align="center">4+</th>
  </tr>
  <tr>
    <td align="center">line-item capture accuracy<br>in production</td>
    <td align="center">unit processing cost<br>per document</td>
    <td align="center">grounded RAG &amp; omnichannel<br>agent response latency</td>
    <td align="center">engineers mentored<br>(interns to associates)</td>
  </tr>
</table>

</div>

<sub>Document accuracy and unit cost refer to the SinoraIQ multimodal pipeline in production; response latency refers to SocialMind AI and AccDoo RAG workflows.</sub>

---

## 🏗️ Flagship Systems

### 🏨 SinoraIQ - Enterprise AI Procurement, Multimodal Document Intelligence & Supply Chain Platform
**The problem:** Enterprise procurement runs on unpredictable supplier document layouts, where extraction errors corrupt accounting ledgers and every ingredient price shift ripples through multi-level recipes and POS menus.
**What I architected & built:**
- **Multi-tier multimodal LLM gateway:** Routes between **Gemini 3.5 Flash-Lite** and **Gemini 3.7 Flash** (with dynamic reasoning/thinking budgets), achieving **>99% line-item capture accuracy at ~$0.012/document**
- **Self-healing agentic configuration compiler:** Autonomous agent that inspects unseen supplier layouts, synthesizes Pydantic-validated extraction schemas, and self-corrects parsing rules via closed-loop validation feedback with zero manual code changes
- **Deterministic mathematical validation gate ("zero-hallucination guardrail"):** Programmatically reconciles extracted taxes, line amounts, and freight charges against published totals before ledger persistence
- **Multimodal layout-aware PDF segmentation:** Combines vision LLMs with C-level **PyMuPDF** rendering to detect document boundaries and split bundled multi-invoice PDFs into cryptographically verified child documents
- **Conversational email NLP & negotiation agents:** Processes inbound Mailgun webhooks to classify operational intents (delays, stockouts, ETAs) and negotiate multi-line price dispute counter-offers within contractual tolerance bands
- **Model Context Protocol (MCP) & Enterprise Connectors:** Built FastAPI & stdio PostgreSQL MCP servers for safe agentic SQL tool calling alongside Gmail Pub/Sub, Microsoft Graph, Google Drive, Shift8 POS, and Deputy integrations
- **Real-time BOM cost-cascade & 3-way reconciliation:** Semantic UOM/pack-size NLP parser (`"1K(6)"`, `"48X6"`), recursive Bill of Materials cost propagation, event-driven 3-way matching (Invoice ↔ PO ↔ GRN), dynamic GL rule engine, and an **11-step distributed ERP orchestrator** (Epicor & Xero) with tenant-aware token telemetry

`Python` `FastAPI` `Gemini 3.5 / 3.7` `MCP` `PyMuPDF` `PostgreSQL` `Next.js` `Keycloak` `Docker`

### 💬 SocialMind AI - Enterprise Multi-Tenant Customer Support & Messaging Automation Platform
**The problem:** Businesses drown in repetitive WhatsApp, Messenger, and Instagram inquiries, while generic chatbots hallucinate policies and lack human escalation controls.
**What I architected & built:**
- **Grounded multi-tenant RAG (<5s latency):** Combines **Google Gemini** and **Pinecone** namespaces with semantic retrieval, intent classification, evidence coverage, and grounding validation to eliminate unsupported answers
- **Under 5-minute automated business onboarding:** Single-instruction pipeline that extracts business profiles, product catalogs, operating hours, and FAQs to provision secure, tenant-isolated knowledge bases
- **Real-time human-in-the-loop (HITL) workflows:** Escalation tickets, owner notifications, and live agent takeover over bidirectional **WebSockets**, backed by asynchronous **FastAPI, Celery, Redis, and PostgreSQL** workers
- **Multilingual conversational intelligence:** Native support for **English, Sinhala, Tamil, Singlish, and Tanglish**, adapting dynamically to customer language and communication style
- **Growth & campaign engines:** Tracked WhatsApp links, QR attribution analytics, and outbound campaign management with Meta template synchronization and opt-out governance

`Python` `FastAPI` `Gemini` `Pinecone` `PostgreSQL` `Celery` `Redis` `WebSockets` `Meta APIs`

### 🤖 AccDoo Platform Advisor - AI-Powered ERP Sales Assistant
**The problem:** Enterprise prospects need accurate, citation-backed answers across complex ERP modules (Finance, Inventory, HRM, CRM, Projects) before committing to a live demo.
**What I architected & built (independently, end to end):**
- **Module-aware RAG (<5s grounded response times):** Built with **Google Gemini, Gemini Embeddings, Pinecone, and PostgreSQL** to deliver cited, hallucination-free product guidance
- **Multilingual sales intelligence:** Automatically detects and responds across **English, Sinhala, Tamil, Singlish, and Tanglish**
- **Dual-mode frontend experience:** Dedicated advisor workspace plus an embedded website assistant with contextual demo-booking lead capture
- **Automated knowledge pipeline:** Document ingestion, web crawling, differential vector updates, and PostgreSQL ↔ Pinecone synchronization verification

`Python` `FastAPI` `Gemini` `Pinecone` `PostgreSQL` `Next.js`

<details>
<summary><b>📂 Earlier Enterprise Experience (Arimac Digital, Surge Global, Dialog Axiata · 2022–2025)</b></summary>
<br>

- **Next Agent - Omnichannel Voice & Messaging AI Platform (Arimac Digital):** Engineered low-latency voice and text agent workflows integrating **Deepgram, AssemblyAI, and ElevenLabs** with multi-provider LLMs (**OpenAI, Gemini, Anthropic Claude, and Llama**) via FastAPI and WebSockets
- **Transaction Monitoring & CX Analytics (Arimac Digital):** Architected multimodal NLP analytics pipelines evaluating customer interaction transcripts, achieving **86% emotion classification** and **84% sentiment analysis** accuracy
- **Enterprise RAG Knowledge Assistants (Arimac Digital):** Built context-grounded Recruitment and Financial QA retrieval pipelines using **Pinecone, ChromaDB, and Astra DB**
- **HubSpot CRM AI Automation (Arimac Digital):** Built intelligent LLM data-extraction workflows and custom API integrations into HubSpot CRM
- **Cancellation Prediction & Enterprise BI Architecture (Surge Global):** Engineered a customer cancellation prediction pipeline (**PySpark, Databricks, AutoGluon Tabular**) and containerized **Apache Superset** analytics (**PostgreSQL, React.js, Docker, AWS**)
- **Enterprise Data Quality Strategy Framework (Dialog Axiata PLC):** Designed and implemented an automated telecom data quality and anomaly detection framework using **Python, SQL, and Apache Kafka**
- **MediTrack:** Secure cloud healthcare platform (microservices, AWS, CI/CD, Kubernetes auto-scaling) · [View on GitHub](https://github.com/Raeesul25)
</details>

---

## 🧠 What I Can Own End to End

| | |
|---|---|
| **🏗️ AI Solution Architecture** | Enterprise AI architecture, technical discovery, unit-cost & token optimization, deterministic guardrails, production deployment |
| **🤖 Agentic AI & Protocols** | Autonomous agents, self-healing workflows, Model Context Protocol (MCP) servers, multi-agent orchestration, tool calling, HITL systems |
| **🔎 RAG & Knowledge Systems** | Hybrid search, cross-encoder reranking, GraphRAG, Self-RAG, CRAG, HyDE, differential vector sync |
| **👁️ Multimodal & Voice AI** | Document intelligence, layout-aware PDF segmentation, PyMuPDF, OCR, STT/TTS pipelines, real-time voice agents |
| **🔌 Enterprise Integration** | ERP (Epicor, Xero), CRM (HubSpot), POS (Shift8), workforce (Deputy), email (Gmail Pub/Sub, MS Graph, Mailgun), Meta APIs |
| **⚙️ Backend & Platform** | Python, FastAPI, Celery, Redis, asyncpg, distributed transaction orchestrators, multi-tenant SaaS, LLM observability |
| **👥 Technical Leadership** | Model and architecture evaluation, engineering mentorship (4+ engineers), cross-functional delivery |

<details>
<summary><b>🛠️ Full technology stack</b></summary>
<br>

- **LLMs & Agentic Frameworks:** Google Gemini (3.5 / 3.7), OpenAI, Anthropic Claude, Llama, Mistral, Groq · Model Context Protocol (MCP), LangGraph, LangChain, LlamaIndex, Agno, AutoGen, CrewAI
- **ML & NLP:** PyTorch, TensorFlow, Scikit-learn, AutoGluon Tabular, Hugging Face, PEFT / LoRA / QLoRA, OpenCV, YOLO
- **Voice AI:** Whisper, Deepgram, ElevenLabs, AssemblyAI
- **Data, Vector & Streaming:** PostgreSQL, MySQL, MongoDB, Neo4j, Redis, Pinecone, ChromaDB, Astra DB, FAISS, Weaviate · Apache Spark (PySpark), Databricks, Apache Kafka
- **Cloud & DevOps:** AWS, Google Cloud, DigitalOcean, Docker, Kubernetes, GitHub Actions
- **Frontend & Security:** React, Next.js, TypeScript, Tailwind CSS · Keycloak, OAuth2, JWT, RBAC, Row-Level Security
- **Analytics & BI:** Apache Superset, Power BI, Tableau, QuickSight, Streamlit
</details>

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,pytorch,react,nextjs,ts,postgres,redis,docker,kubernetes,aws,gcp,git&perline=13" alt="Core technologies" />

</div>

---

## 🎓 Education & Credentials

- **MSc Big Data Analytics (Merit)**, Robert Gordon University, Scotland, UK · 2024–2025
- **BSc (Hons) IT, Data Science Specialization (Second Class Upper)**, SLIIT, Sri Lanka · 2019–2023
- **Certifications:** Microsoft Learn AI Skills Challenge (ML & MLOps) · Oracle Cloud Infrastructure AI Foundations (Certified Associate)
- **Research:** *An Interactive Application for University Students to Reduce the Industry-Academia Skill Gap in the Software Engineering Field* · *MSc Thesis: AI-Driven Sentiment & Emotion Intelligence for E-Commerce*

---

## 🤝 Work With Me

Have an AI problem that needs an architecture and a team that can ship it? I consult on **AI solutions, AI agents, and production agentic systems** - from technical discovery to deployment.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raeesul-islam)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:raeesulislam25@gmail.com)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:0e75b6,100:6f42c1&section=footer" alt="" />

</div>
