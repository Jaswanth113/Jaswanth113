<div align="center">

  <h1>👋 Hi, I'm Jaswanth Tikkireddy</h1>
  
  <h3>AI Engineer &nbsp;·&nbsp; Backend Engineer &nbsp;·&nbsp; RAG & Agentic Systems</h3>

  <p>
    <em>I design and build production AI systems from the ground up —</em><br/>
    <strong>Advanced RAG, retrieval systems, regulatory AI, agentic systems, and backend architecture.</strong>
  </p>

<p>
  <a href="https://github.com/Jaswanth113">
    <img
      src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=1200&color=58A6FF&center=true&vCenter=true&width=900&lines=Building+Production+AI+Systems;Advanced+RAG+%7C+Hybrid+Retrieval;Legal+RAG+%7C+Regulatory+AI+%7C+Compliance;Multi-Vector+Retrieval+%7C+Search+Systems;Agentic+RAG+%7C+Context+Engineering;Agentic+AI+%7C+MCP+%7C+Agent+Harnesses;Designing+Systems+for+Scale+%7C+Reliability+%7C+Cost;Python+%7C+FastAPI+%7C+Backend+Architecture"
      alt="Jaswanth — AI Engineer | Production AI Systems | Advanced RAG | Agentic RAG | Regulatory AI | Retrieval | Agentic AI | Backend Architecture"
    />
  </a>
</p>

  <p>
    <a href="https://www.linkedin.com/in/jaswanth-t-981214251/" target="_blank" rel="me" title="Jaswanth on LinkedIn">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Jaswanth LinkedIn" />
    </a>
    &nbsp;
    <a href="https://portfolio-jaswanth.vercel.app/" target="_blank" rel="me" title="Jaswanth Portfolio">
      <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Jaswanth Portfolio" />
    </a>
  </p>

</div>

---

## 📌 About Me

I build systems around the **actual use case first** — understanding the architecture, data flow, retrieval strategy, reliability, and cost before deciding how the LLM should be used.

Since October 2025, I've been part of the engineering team at [**Bettrlabs**](https://bettrlabs.com/), working across AI/RAG infrastructure, regulatory compliance, search, backend systems, and agentic workflows.

A significant part of my work has been **individually designed and implemented from scratch**, while also contributing to larger team systems.

I use AI tools as development assistance, while keeping the **architecture, system logic, debugging, and implementation decisions** grounded in the actual problem.

---

## 🏢 Experience — Bettrlabs

> **AI / Backend Engineering**  
> Working in a small engineering team building AI-driven regulatory, compliance, formulation, and agentic systems.

<br/>

### 🧬 Advanced RAG Architecture
*Independently designed and built from scratch*

Built a reusable advanced RAG architecture for **legal and regulatory document systems**, with the retrieval and context pipeline designed around **accuracy, cost, model constraints, and document evolution**.

#### Key Capabilities & Architecture:
* **Automated document pipeline** — parsing → context-enriched smart chunking → embedding → indexing → retrieval, without manual document processing
* **Multi-stage retrieval** — dense + lexical/hybrid retrieval → relevance filtering → reranking instead of relying on a single similarity search
* **Adaptive context selection** — selects relevant document content and pages according to the target model's available context window
* **Model-agnostic inference** — supports both local models and hosted LLM APIs
* **Version-aware knowledge layer** — stores cited RAG-generated summaries as reusable source-of-truth context and maintains newer document versions separately
* **Human-in-the-loop automation** — expensive or high-impact stages can pause for review while routine ingestion, processing, and version checks are automated

The FSSAI document ingestion and retrieval system is used by the team and has received feedback that it saves time and makes regulatory information easier to find and work with. The architecture is currently focused on legal and regulatory documents.

### Core idea

**_better retrieval → better context → fewer tokens → lower cost → higher reliability_**

🔗 Architecture used in → [**labs.new**](https://labs.new/)

---

### 🧾 Compliance Engine — PLM
*Independently built the core architecture and major implementation.*

Built an AI-assisted regulatory compliance workflow that evaluates **ingredients, claims, and nutrition data** against applicable regulations.

* Generates a **compliance report and product assessment**, helping determine how well a product satisfies the applicable requirements and where issues are present
* Combines **regulatory RAG, structured compliance validation, and an advanced LLM council** to compare analyses, validate findings, and produce more traceable results instead of relying on a single LLM response
* Built major backend and frontend components using **FastAPI, React, Next.js and Tailwind CSS**

The PLM capability is part of the production [**labs.new**](https://labs.new/) platform and has supported customer work, with customers purchasing and continuing to request capabilities built around this compliance workflow.

---

### 🔎 Formulation Search
*Independently built the retrieval and search architecture.*

Designed a formulation/product search system around **custom retrieval logic rather than a single-vector search approach**, with the architecture designed for scalable retrieval as the dataset grows.

* **11+ custom dense embeddings per node/chunk** with independent similarity signals, allowing different product attributes and semantic aspects to contribute separately to retrieval
* **Advanced hybrid retrieval** — database-first retrieval + dense/lexical search + custom retrieval rules + RRF score fusion + reranking
* **Query-dependent retrieval flow** — applies different retrieval logic based on the query, with deeper RAG/agentic fallback when direct retrieval is insufficient

The system is built to move beyond generic vector similarity by combining **structured data, multiple semantic representations, lexical signals, ranking logic, and retrieval rules** into one search pipeline.

🔗 Live at → [**bettrlabs.com**](https://bettrlabs.com/)

---

### 💳 Payment Infrastructure
*Independently built the Razorpay payment backend.*

Designed the payment system around **secure processing, transaction consistency, and failure recovery** for a production environment.

* **End-to-end payment flow** — verification, webhooks, reconciliation, idempotent settlement, and transaction state handling
* **Failure-safe architecture** — handles duplicate, delayed, incomplete, failed, and out-of-sync payment states without incorrectly granting or losing purchases
* Built the supporting **database protections, recovery logic, and background reconciliation** needed to keep payment state reliable in production

🔗 Live at → [**bettrlabs.com**](https://bettrlabs.com/)

---

### 🏗️ Core Backend Platform
*Built major parts of the core backend architecture supporting the AI platform.*

* Designed the **API, service, database, and LLM integration layers** using FastAPI, PostgreSQL/SQLite, Alembic and LiteLLM
* Built testing, structured logging, error tracing, and **LLM token-usage tracking** across the platform
* Focused on clean, maintainable backend flows with clear boundaries and only the abstractions required by the product

---

### 🤖 Agent Harness
*Contributed to building an agent harness.*

* Worked on the **agent execution flow, skill discovery/retrieval, tool usage, and context flow**
* Contributed design ideas around **how agents discover and select skills/tools**, with some of those ideas adopted into product development

---

## 🧠 Personal Project — Jarvis

### Jarvis — Personal Multi-Agent Assistant
*Independent project · actively evolving*

A personal AI system built from the ground up to explore **agent architecture, memory, skills, tools, MCP, computer control, and voice interaction**.

* **Memory & context** — persistent memory, task state, contextual recall, and structured agent context
* **Skills & tools** — MCP, custom tools, skill discovery, tool selection, and execution
* **Computer & voice control** — application control, filesystem interaction, voice activation, STT/TTS
* **Model orchestration** — local + hosted models, model routing, and agent execution loops
* **Full-stack implementation** — Python/FastAPI backend with a polished **Next.js frontend** designed around the agent workflow

**Tech Stack:** `Python` `FastAPI` `Next.js` `React` `TypeScript` `LLMs` `MCP` `Ollama` `SQLite` `STT` `TTS` `Docker`

*Built primarily to understand and implement the **agent loop, orchestration, memory, and tool execution** rather than relying entirely on an existing agent framework.*

---

## 🎯 Technical Focus Areas

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🧠 Advanced RAG & Retrieval</h4>
      <ul>
        <li><strong>Focus:</strong> Advanced RAG · Legal RAG · Regulatory RAG</li>
        <li><strong>Techniques:</strong> <code>Hybrid Retrieval</code> <code>Multi-Vector</code> <code>Dense & Lexical (BM25)</code> <code>Semantic Search</code> <code>RRF</code> <code>ANN</code> <code>Reranking</code></li>
        <li><strong>Context Engineering:</strong> <code>Query Formulation</code> <code>Citation-Aware Retrieval</code> <code>Version-Aware Retrieval</code></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🤖 Agentic AI & LLM Systems</h4>
      <ul>
        <li><strong>Core:</strong> Agentic AI · AI Agents · Agent Harnesses · Multi-Agent Systems</li>
        <li><strong>Capabilities:</strong> <code>MCP</code> <code>Tool Calling</code> <code>Skills</code> <code>Memory</code> <code>Model Routing</code> <code>Local LLMs</code></li>
        <li><strong>Optimization:</strong> <code>Context Engineering</code> <code>Token Optimization</code> <code>LLM Cost Tracking</code></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🔎 Vector & Knowledge Systems</h4>
      <ul>
        <li><strong>Architecture:</strong> Vector Search · Knowledge Graphs · Graph RAG</li>
        <li><strong>Databases:</strong> <code>Qdrant</code> <code>Pinecone</code> <code>Weaviate</code> <code>FAISS</code> <code>ChromaDB</code> <code>Neo4j</code></li>
        <li><strong>Embeddings & Search:</strong> <code>Dense Embeddings</code> <code>Multi-Vector Search</code> <code>Hybrid Search</code> <code>Graph Retrieval</code></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🏗️ Backend & AI Infrastructure</h4>
      <ul>
        <li><strong>Core Stack:</strong> <code>Python</code> <code>FastAPI</code> <code>PostgreSQL</code> <code>SQLite</code></li>
        <li><strong>Architecture:</strong> <code>REST APIs</code> <code>Async Processing</code> <code>Alembic</code> <code>LiteLLM</code> <code>Service Architecture</code></li>
        <li><strong>Quality & Ops:</strong> <code>Structured Logging</code> <code>Unit Testing</code> <code>API Testing</code> <code>E2E Testing</code> <code>LLM Observability</code> <code>Cost Tracking</code></li>
      </ul>
    </td>
  </tr>
</table>

---

## 🧠 Engineering Approach

> **Understand the use case → design the architecture → define the data flow → implement → test failure cases → inspect logs → optimize**

For AI systems:

> **retrieval quality → context quality → reliability → token usage → latency → cost**

I use AI tools as development assistance, while keeping the **architecture, system logic, and implementation decisions** grounded in the actual system.

---

## 📊 GitHub Analytics

<div align="center">
  <img
    height="170"
    src="https://github-readme-stats.vercel.app/api?username=Jaswanth113&show_icons=true&theme=github_dark&hide_border=true&count_private=true"
    alt="Jaswanth's GitHub Stats"
  />
  &nbsp;
  <img
    height="170"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jaswanth113&layout=compact&theme=github_dark&hide_border=true"
    alt="Top Languages"
  />
</div>

<br/>

<div align="center">
  <img
    src="https://streak-stats.demolab.com?user=Jaswanth113&theme=github-dark&hide_border=true"
    alt="Contribution Streak"
  />
</div>

<br/>

<div align="center">
  <img 
    src="https://github-readme-activity-graph.vercel.app/graph?username=Jaswanth113&theme=github-dark&hide_border=true" 
    alt="Activity Graph"
  />
</div>

---

<div align="center">

  <h3><em>Build from first principles. Build for scale.</em></h3>

  <a href="https://github.com/Jaswanth113">
    <img src="https://komarev.com/ghpvc/?username=Jaswanth113&style=for-the-badge&color=58A6FF" alt="Profile Views" />
  </a>

</div>