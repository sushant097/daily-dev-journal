## 📘 **Daily Dev Journal**

> *A living record of my technical growth — one commit, one experiment, one idea at a time.*

---

### 🧭 About

This repository is my **daily tech journal**, capturing what I *learn*, *build*, and *explore* — from infrastructure to AI experiments.
Each entry includes a **date**, **topic**, a short **summary**, and a **resource link** — making it easy to revisit concepts and trace progress like a developer’s time capsule.

---

### 📅 Daily Logs

| Date                 | Project / Topic                                                                                                                  | Summary                                                                                                                                                               | Tech / Resource                             |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| **Oct 7 2025**       | ☸️ [**Kubernetes Basics**](https://www.youtube.com/watch?v=d6WC5n9G_sM)                                                          | Explored Kubernetes architecture — Pods, Nodes, Deployments, and Services — to understand how clusters orchestrate containerized workloads.                           | 🧠 *Minikube · kubectl · Docker*            |
| **Oct 9 2025**       | 🖼️ [**MCP Server – Paint Automation**](https://github.com/sushant097/Custom-MCP-server-to-paint-in-Python/tree/master)          | Built a custom **MCP server** that automates macOS Preview (Paint) using `pyautogui`. Integrated LLM tool calls: `open_paint`, `draw_rectangle`, `add_text_in_paint`. | ⚙️ *Python · MCP · LLM Tool Calling*        |
| **Oct 10 2025**      | 📧 [**MCP Server – Gmail Automation**](https://github.com/sushant097/Custom-MCP-server-to-paint-in-Python/tree/master/gmail-mcp) | Developed a Gmail automation agent using **Gemini Flash 2.0** that sends emails autonomously via Gmail API with logging + auto-report generation.                     | 🔗 *Gmail API · Gemini Flash 2.0 · MCP*     |
| **Oct 11 – 14 2025** | 🧠 [**Prompt Engineering & Multi-City Route Agent**](https://github.com/sushant097/EAGV2-Session5-Assignment.git)                      | Implemented an **LLM agent** to plan and optimize a multi-city roundtrip using dynamic tool execution through MCP responses.                                          | 🚀 *Prompt Chaining · Agentic AI · MCP*     |
| **Oct 15 – 16 2025** | 🌟 [**Celebrity Detection + QA Agent**](https://github.com/sushant097/CELEBRITY-Detector-And-QA)                                 | Created a vision agent that detects celebrities and answers questions about them. CI/CD via **CircleCI** and deployed on **GCP Kubernetes Engine**.                   | 🤖 *LangChain · Vision AI · GKE · CircleCI* |
| **Oct 17 – 20 2025** | 🤖 [**Multi AI Agent LLMOps**](https://github.com/sushant097/Multi-AI-Agent-LLMOPS/tree/master)                                  | Designed a multi-agent system with autonomous search capabilities, integrated **LangChain**, **LangGraph**, and **Jenkins**, deployed to **AWS Fargate**.             | 🧩 *LangGraph  · Langchain · Jenkins · Sonarqube · AWS ECS Fargate*  |
| **Oct 21 – 22 2025** | 📈 [**AI Stock Advisor**](https://github.com/sushant097/ai-stock-advisor)                                                        | Built an AI-powered investment app using **Streamlit** and **yfinance**, integrated **Gemini (via agno)** for personalized stock insights, and added Plotly-based performance charts. | 🧠 *Streamlit · yfinance · Gemini API · agno · Plotly · Python*                   |
| **Oct 23 – 24 2025** | 🎵 [**AI Music Composer**](https://github.com/sushant097/AI-Music-Composer)                                       | Developed an AI-powered system to generate melodies using **LangChain + Groq LLM**, built an interactive **Streamlit** interface, containerized with **Docker**, and deployed on **GKE (Kubernetes)**. | 🎼 *LangChain · Groq LLM · Streamlit · Music21 · Docker · Kubernetes (GKE)*     |
| **Oct 25 – 28 2025** | 🧩 [**TabGist — Chrome AI Summarizer**](https://github.com/sushant097/tabgist-chrome)                                  | Created a Chrome Extension that summarizes any web or YouTube tab using a **FastAPI backend**. Integrated **Gemini** for AI summaries and translations, with a **local fallback** for offline summarization. | 🧠 *Chrome MV3 · FastAPI · Python · Gemini API · YouTube Transcript API · Local AI Summarizer* |
| **Oct 29 – 31 2025** | 🧠 [**Agentic Ticker Research — Multi-Step AI Stock Analyst**](https://github.com/sushant097/Agentic-Architecture-EAG-Session6-Assignment) | Built a reasoning-driven backend that **analyzes stock price trends**, **fetches financial news**, and **links market movement with real-world events** through iterative LLM planning. The system acts as an **autonomous analyst**, running a full **Perception → Memory → Decision → Action** loop to generate final investment insights. | 🧩 *Python · FastAPI · Gemini LLM · yfinance · MCP Tools · Agentic Planning Loop · Chrome Extension Bridge* |
| **Nov 1 – 9 2025**  | 🧠 [**RAG Memory — Context-Aware Web Memory Agent**](https://github.com/sushant097/RAG-Memory-Context-Aware-AI-Agent) | Developed a **persistent semantic memory system** that learns from web pages we read and later **recalls the exact snippet + source** when asked. Uses **hybrid temporal-semantic retrieval** and works with both **Gemini** and **local embeddings (Ollama)**, integrated with a Chrome extension for **highlight-on-recall**. | 🧠 *FastAPI · Gemini 2.0 Flash · FAISS Vector Store · MCP Tools · MarkItDown · Chrome MV3 Extension · Local/Cloud Embeddings (Google & Ollama)* |
| **Nov 10 – 22 2025** | 🤖 [**LLM Agents — External APIs & RAG**](https://github.com/sushant097/LLM-Agents-External-APIs) | A **Cortex-style agentic framework** bridging LLMs to the real world. Orchestrates a **Perceive → Plan → Act → Remember** loop using **MCP** to manipulate **Google Sheets, Gmail, and Web Search**. Features a **Telegram gateway** for mobile triggers and end-to-end automation pipelines (e.g., "Scrape F1 stats → Create Sheet → Email User"). | ⚙️ *Python · Gemini 2.0 Flash · MCP (Stdio/SSE) · Google OAuth 2.0 · FAISS · Trafilatura & PyMuPDF4LLM · MarkItDown · Telegram Bot API*  |
| Nov 29 – Dec 05 2025 | 🧩 [**Cognitive-Reflex-Agent**](https://github.com/sushant097/Cognitive-Reflex-Agent) | A Dual-Process (System 1 vs System 2) agent architecture. Features a sub-millisecond Semantic Cache (Jaccard) for recurring queries and a Secure Python Sandbox for reasoning. Fuses Multi-MCP tools with self-correcting dynamic plans to ensure reliability and cost-efficiency. | ⚙️ Python 3.11+ (AsyncIO) · Gemini 2.0 Flash · System 1/2 Architecture · Multi-MCP Dispatcher · Jaccard Similarity (Cache) · AST Sandboxing (types.ModuleType) · Dynamic Code Gen |

---



<!-- Other projects:
- https://github.com/sushant097/Flipcart-recommender-llmops
- https://github.com/sushant097/ANIME-Recommender-LLMOPS
- https://github.com/sushant097/AI-Travel-Planner
- https://github.com/sushant097/Study-Buddy-AI 
- https://github.com/sushant097/medical-rag-chatbot
-->

---

### 🧩 Learning Focus

| Area                        | Description                                                     |
| --------------------------- | --------------------------------------------------------------- |
| ☁️ **Cloud & DevOps**       | AWS, Docker, Kubernetes, CI/CD pipelines                        |
| 🧠 **AI & ML**              | Building intelligent agents, LLM integrations, generative AI    |
| 💻 **Software Engineering** | Clean architecture, scalable system design, Python & TypeScript |
| 🧰 **MLOps & Automation**   | Bridging ML pipelines with infrastructure automation            |
| ⚙️ **Personal Projects**    | Real-world experiments that mix creativity with engineering     |

---

### 🗂 Folder Structure

```
📦 daily-dev-journal
 ┣ 📘 README.md         → Main learning log (you’re here)
 ┣ 📁 logs/             → Extended write-ups or daily summaries
 ┗ 📁 resources/        → References, cheat sheets, and supporting materials
```

---


### 🧠 Highlights

* 🧩 **Built modular MCP servers** for automation (Paint & Gmail)
* 🔗 **Integrated Gemini Flash 2.0** with MCP for intelligent tool use
* 📨 **Enabled LLM-driven Gmail automation** — the agent can email logs autonomously
* 💡 **Learned Kubernetes internals** and hands-on container orchestration

---

### 💬 Reflection

> “Small, consistent progress compounds into mastery.”
> This journal keeps me accountable — every line of code, every video watched, every concept explored adds to a broader journey of becoming a more thoughtful engineer.



