<div align="center">

<h1>Naga Lakshmi Surapureddy</h1>

<p><strong>Aspiring AI / GenAI Engineer &nbsp;·&nbsp; Full Stack Developer</strong></p>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=6C63FF&center=true&vCenter=true&width=550&lines=Building+RAG+%26+LLM+Applications;Exploring+Semantic+Search+%26+Vector+Databases;Learning+LangGraph+%26+Agentic+AI;Open+to+Internship+%26+Full-Time+Opportunities)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naga-lakshmi-surapureddy-861456302/)
[![Email](https://img.shields.io/badge/Gmail-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nagalakshmisurapureddy@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Surapureddynagalakshmi)

<br/>

![Open to Work](https://img.shields.io/badge/✅%20Open%20to%20Work-Internship%20%7C%20Full--Time-00C896?style=flat-square)
![Location](https://img.shields.io/badge/📍%20Location-Andhra%20Pradesh%2C%20India-6C63FF?style=flat-square)
![Profile Views](https://komarev.com/ghpvc/?username=Surapureddynagalakshmi&label=Profile%20Views&color=6C63FF&style=flat-square)

</div>

---

## 👩‍💻 About Me

> CSE (AI) Graduate passionate about building intelligent AI applications — from RAG pipelines and LLM integrations to full stack systems.

- 🔭 Building RAG pipelines, AI workflows & LLM-powered applications
- 🧠 Interested in Semantic Search, Vector Databases, Document Intelligence & GenAI
- 🌱 Exploring LangGraph, GraphRAG, Multimodal AI & Advanced RAG systems
- 🤝 Open to Internship & Software Engineering / AI opportunities
- ⚡ Focused on turning AI ideas into practical, working applications

---

## 🚀 Featured Projects

### 🤖 DocAssist — RAG Document Assistant
> *Featured Project — RAG Pipeline with Full Stack Implementation*

**Upload a PDF and ask questions — get AI-powered answers with the source page cited.**

A full-stack RAG application built as a learning project — implements PDF ingestion, semantic search, vector storage, and LLM-powered Q&A with source citations.

```
┌──────────────┐   upload PDF / ask question   ┌──────────────┐
│   Frontend   │ ─────────────────────────────► │   Backend    │
│  React 19 +  │ ◄──── answer + source page ─── │   FastAPI    │
│  Tailwind 4  │                                └──────┬───────┘
└──────────────┘                                       │
        ┌──────────────────────────────────────────────┤
        ▼                                              ▼
 ┌─────────────┐                             ┌──────────────────┐
 │   SQLite    │  users · docs · chunks      │  FAISS Index     │
 │   app.db    │  query history              │  vector search   │
 └─────────────┘                             └────────┬─────────┘
                                                      │
                                             ┌────────▼─────────┐
                                             │  LLM Provider    │
                                             │  Groq / OpenAI / │
                                             │  Gemini          │
                                             └──────────────────┘
```

**How it works:**
1. PDF is parsed → split into ~800-character chunks
2. Each chunk is embedded with `all-MiniLM-L6-v2` (CPU, 384-dim)
3. Vectors stored in FAISS · chunk text stored in SQLite
4. On query → embed it → FAISS finds top 5 chunks → LLM generates answer with source page

**Key Features:**
- 📄 Upload PDFs (≤ 25 MB) and ask natural language questions instantly
- 🔍 Semantic similarity search using FAISS vector index
- 💬 Answers include **source filename + page number** for full traceability
- 🔐 JWT authentication with bcrypt password hashing
- 🔄 Supports **Groq**, **OpenAI**, and **Google Gemini** — switch via `.env`
- 📊 Dashboard with query history, document manager, and usage stats
- ⚡ Zero-config setup — SQLite + FAISS, no external databases needed

**Tech Stack:**

| Layer | Technology | Why |
|---|---|---|
| Backend | FastAPI + Uvicorn | Async, typed, OpenAPI built-in |
| Vector Index | FAISS `IndexFlatIP` | Lightweight, file-persisted, fast |
| Embeddings | `all-MiniLM-L6-v2` | CPU-friendly, accurate for docs |
| Metadata DB | SQLite | Zero setup, single file |
| LLM | Groq / OpenAI / Gemini | Flexible — use any free API key |
| Auth | bcrypt + JWT | Standard, no extra service |
| Frontend | React 19 + Vite + Tailwind 4 | Modern, fast dev experience |

[![View on GitHub](https://img.shields.io/badge/GitHub-View%20DocAssist-6C63FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Surapureddynagalakshmi/rag-document-assistant)

---

### 🏥 Smart Hospital Management System

Full-stack hospital operations platform with **role-based access control** for Patients, Doctors, and Admins. Features secure authentication, appointment scheduling, and an integrated billing system.

**Tech:** `HTML` `CSS` `JavaScript` `SQL`

[![View on GitHub](https://img.shields.io/badge/GitHub-View%20Project-gray?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Surapureddynagalakshmi)

---

### 🌱 Crop Recommendation System

ML classification system that recommends optimal crops based on **soil parameters and climate conditions**. Trained on real agricultural datasets with high prediction accuracy.

**Tech:** `Python` `Scikit-learn` `Pandas` `NumPy`

[![View on GitHub](https://img.shields.io/badge/GitHub-View%20Project-gray?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Surapureddynagalakshmi)

---

## 🛠️ Tech Stack

### 🤖 AI / GenAI / ML
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

### 🗄️ Vector Databases & Search
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)

### ⚙️ Backend & Databases
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-FF6C37?style=flat-square&logo=postman&logoColor=white)

### 🌐 Frontend & Cloud
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)

### 🔧 Tools
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=Surapureddynagalakshmi&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&border_radius=10"/>
&nbsp;
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Surapureddynagalakshmi&layout=compact&langs_count=6&theme=tokyonight&border_radius=10"/>

<br/><br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=Surapureddynagalakshmi&theme=tokyonight&border_radius=10)](https://git.io/streak-stats)

</div>

---

## 🌱 Currently Learning in 2026

```python
roadmap_2026 = {
    "Agentic AI"    : ["LangGraph", "AutoGen", "CrewAI", "Multi-Agent Systems"],
    "Advanced RAG"  : ["HyDE", "Re-ranking", "Hybrid Search", "GraphRAG"],
    "Multimodal AI" : ["Vision LLMs", "Document AI", "Image+Text Pipelines"],
    "LLM Ops"       : ["LangSmith", "Prompt Engineering", "Fine-tuning", "RLHF"],
    "Cloud AI"      : ["AWS Bedrock", "SageMaker"],
}
```

---

## 🤝 Let's Connect

<div align="center">

I am a fresher actively looking for **Internship & Entry-Level opportunities** in AI / GenAI / Software Engineering.
If you're working on something interesting — let's talk!

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Naga%20Lakshmi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naga-lakshmi-surapureddy-861456302/)
[![Email](https://img.shields.io/badge/Gmail-nagalakshmisurapureddy%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nagalakshmisurapureddy@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Surapureddynagalakshmi-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Surapureddynagalakshmi)

<br/>

---

*⭐ If you find my work useful, a star on my repos means a lot — thank you!*

</div>
