# Hi there, I'm Zhen Wang (王振)
### Full-Stack Software Engineer & Agentic AI Architect

<p align="center">
  <img src="./professional_avatar.png" width="150" style="border-radius: 50%; margin: 10px;" alt="Zhen Wang Portrait"/>
</p>

<p align="center">
  <a href="https://linkedin.com"><img src="https://img.shields.io/badge/LinkedIn-Zhen_Wang-blue?style=flat-square&logo=linkedin" alt="LinkedIn"></a>
  <a href="mailto:zhenwang.deutschland@gmail.com"><img src="https://img.shields.io/badge/Email-zhenwang.deutschland-red?style=flat-square&logo=gmail" alt="Email"></a>
  <img src="https://img.shields.io/badge/Location-Germany-emerald?style=flat-square&logo=googlemaps" alt="Location">
</p>

---

## Professional Profile

I am an **AI Builder** and **Full-Stack Software Engineer** dedicated to architecting autonomous agent systems and high-performance applications. Leveraging a strong foundation in **CAE crash safety simulation**, I apply first-principles thinking to solve complex computational and software engineering challenges. My development philosophy is rooted in clean architectural design, robust performance, and obsessive attention to UI/UX.

I specialize in orchestrating **Multi-Agent Systems**, designing **Model Context Protocol (MCP)** integrations, and building optimized full-stack apps from Web to Mobile. Whether deploying low-latency APIs at the network edge with Cloudflare Workers or implementing sandboxed agent runtimes with OCI container isolation, I love solving hard engineering problems, integrating complex legacy domain pipelines, and pushing the boundaries of what AI can build.

---

## Technology Stack & Skills

### Agentic AI & LLM Orchestration
* **Multi-Agent Frameworks:** Microsoft AutoGen, custom multi-agent team routers
* **Inter-Agent Protocols:** Model Context Protocol (MCP - Client & Server development), FastMCP
* **LLM Engineering:** Google Gemini API (Flash/Pro), OpenAI API (GPT-4o), local llama.cpp hosting, structured output validation, context engineering (CSV/Text prompt compression)
* **Search & RAG:** RAG (Retrieval-Augmented Generation), PostgreSQL `pgvector`, hybrid lexical/semantic retrieval, memory consolidation algorithms

### Full-Stack Frontend & Mobile
* **Core Languages:** TypeScript, JavaScript, HTML5, CSS3
* **Web Frameworks:** React 19, Next.js 16 (App Router), Zustand (state management), TanStack Query (fetching & caching)
* **Mobile Development:** Bare React Native workflow, Expo 53+, Expo Router, Tailwind CSS, Framer Motion
* **Rich Components:** TipTap Editor, FortuneSheet (in-browser Excel spreadsheet), noVNC (HTML5 VNC visual client), ECharts/Recharts

### Backend, Database & Infrastructure
* **Backend Engines:** FastAPI (Python), Node.js, Express
* **Edge Computing:** Cloudflare Workers (Serverless V8 isolate runtimes, Wrangler deployment)
* **BaaS & Realtime:** Supabase (Realtime subscriptions & database triggers), Firebase (Auth, Firestore, Cloud Functions)
* **Queues & Caching:** Redis, Celery (distributed async workers), APScheduler
* **DevOps & Security:** Docker Compose, OCI-compliant sandboxing (Kata/gVisor), Seccomp & AppArmor syscall profiles, Traefik (load balancer), Cloudflare Tunnel

---

## Featured Projects

Here are three core projects I have designed and implemented, showcasing my skills in full-stack architecture, edge serverless computing, and AI agent orchestration.

### 1. CoCal (AI-Powered Life OS)
*A collaborative, real-time productivity monorepo uniting calendar blocking, task management, document RAG, and headless browser VM automation.*
* **Full-Stack Architecture:** Next.js 16 App Router frontend paired with a Python FastAPI backend, using Supabase for database row-level security (RLS) and real-time state synchronization.
* **Headless Browser VM (noVNC):** Spins up Docker-isolated browser runtimes utilizing Playwright to automatically join and record online meetings (FFmpeg + PulseAudio virtual sound card loopback), featuring an **in-browser VNC canvas (noVNC)** for real-time manual takeover.
* **Dreaming Consolidation Engine:** A background memory consolidation engine that computes cosine similarity embeddings on project and user memories, resolving logical conflicts and merging duplicates using Gemini 2.5 Flash.
* *Stack: Next.js 16, React 19, FastAPI, Supabase (PostgreSQL/pgvector), Redis, Playwright, noVNC, Google Gemini API, Stripe*

### 2. BillCheck (AI-Powered Expense OS)
*A cross-platform React Native app with a Serverless Cloudflare Workers edge backend for intelligent document parsing and financial forecasting.*
* **Edge & Serverless API:** Cloudflare Workers backend implementing Firebase Authentication bearer token verification, routing JSON and visual requests globally with zero cold starts.
* **Long Context Compression:** Created a smart context utility that converts transaction databases from JSON to CSV or ultra-compact text depending on query complexity, **reducing LLM token usage by 60-70%** and enabling cheap, long-context reasoning over 1000+ items.
* **Intent-Based Action Interception:** Integrates a chat agent that detects bill creation requests from conversation history, wrapping them in structured JSON blocks that the React Native app intercepts to automatically render draft invoice sheets.
* *Stack: React Native, Cloudflare Workers, Firebase (Auth/Firestore), Gemini 2.5 Pro/Flash, Stripe*

### 3. PostAI (Post-Processing Agent MVP)
*A high-throughput python automation backend that orchestrates multiple autonomous agents to parse complex binary datasets and output reports.*
* **Orchestrator Architecture:** AutoGen-based multi-agent system coordinating specialized workers (`binout_team`, `d3plot_team`, `report_team`) through an extensible FastMCP tool registry.
* **Binary File Parsing & 3D Visualization:** Reads legacy binary streams and translates raw structures into 3D meshes using PyVista off-screen rendering, generating MP4 animations and interactive 3D WebGL HTML pages.
* **Security & Syscall Sandboxing:** Executes untrusted python scripts inside OCI-compliant runtimes restricted by AppArmor and Seccomp profiles, utilizing read-only volume mounts and copy-on-write workspaces to protect the host machine.
* *Stack: Python, FastAPI, Celery, PyVista, qd-library, lasso-python, SQLite, Autogen, FastMCP*

---

## Git & Profile Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=zhen1991-ch&show_icons=true&theme=radical&count_private=true" alt="Github Stats"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=zhen1991-ch&layout=compact&theme=radical" alt="Top Languages"/>
</p>

---

*“Code with first-principles, build with AI agents, and design for the user.”*
