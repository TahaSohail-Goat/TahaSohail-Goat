<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:38bdf8&height=220&section=header&text=Taha%20Sohail&fontSize=48&fontColor=ffffff&animation=twinkling&desc=BS%20Software%20Engineering%20Student%20%7C%20AI%2FML%20Engineer%20%7C%20Full-Stack%20Developer&descAlignY=58"/>
</p>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=800&lines=Building+Sabaq+AI+%E2%80%94+Syllabus-Grounded+AI+Study+Companion;RAG+%26+LLM+Systems+Engineer;MERN+Stack+%2B+Next.js+Developer;AI%2FML+Intern+%40+ORBIT-I"/>
</p>

<p align="center">
<a href="https://tahasohail.vercel.app/">Portfolio</a> •
<a href="https://www.linkedin.com/in/taha-sohail-7b03b8320/">LinkedIn</a> •
<a href="mailto:tahasohail85@gmail.com">Email</a>
</p>

<p align="center">
<img src="https://komarev.com/ghpvc/?username=TahaSohail-Goat&color=38bdf8&style=for-the-badge"/>
<img src="https://img.shields.io/github/followers/TahaSohail-Goat?label=Followers&style=for-the-badge&color=38bdf8&logo=github"/>
</p>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=38bdf8&height=40&section=header&animation=fadeIn"/>
</p>

## 👨‍💻 Who I Am

```ts
const taha = {
  title: "BS Software Engineering Student @ FAST-NUCES | AI/ML Intern @ ORBIT-I",
  stack: ["React", "Next.js", "Node.js", "Express", "Python", "Django", "Flask",
          "MongoDB", "SQL Server", "PyTorch", "LangChain", "LangGraph"],
  flagshipProject: "Sabaq AI — grounded RAG tutor for Pakistani board students",
  launchedProjects: ["Sabaq AI", "Studify", "Smart Disaster Response MIS",
                      "Cybercrime Digital Evidence Integrity Management System",
                      "Ocean Route Navigator"],
  certifications: ["Google Coursera - Crash Course on Python",
                    "Teaching Assistant, Discrete Structures - FAST-NUCES"],
  status: "Interning @ ORBIT-I (AI/ML) & FlyRank | Officer @ FAST Computing Society",
  openTo: ["Open Source", "Internships", "Freelance Work", "Collaboration"]
}
```

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=38bdf8&height=40&section=header&animation=fadeIn"/>
</p>

## 🌟 Flagship Project

<div align="center">

### 📚 [Sabaq AI](https://github.com/TahaSohail-Goat/SabaqAI) — Syllabus-Grounded AI Study Companion

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=1BB56B&center=true&vCenter=true&width=700&lines=Answers+strictly+from+the+student's+own+syllabus;Cites+the+exact+chapter+and+page%2C+every+time;Refuses+honestly+instead+of+guessing;Built+for+Bano+Qabil+AI+Hackathon+2026"/>

[![Live demo](https://img.shields.io/badge/demo-live-1BB56B?style=for-the-badge&logo=vercel&logoColor=white)](https://sabaq-ai-three.vercel.app)
[![CI](https://img.shields.io/github/actions/workflow/status/TahaSohail-Goat/SabaqAI/ci.yml?branch=main&style=for-the-badge&label=CI&color=1BB56B)](https://github.com/TahaSohail-Goat/SabaqAI/actions/workflows/ci.yml)
[![Stars](https://img.shields.io/github/stars/TahaSohail-Goat/SabaqAI?style=for-the-badge&color=1BB56B)](https://github.com/TahaSohail-Goat/SabaqAI/stargazers)
[![License](https://img.shields.io/github/license/TahaSohail-Goat/SabaqAI?style=for-the-badge&color=1BB56B)](https://github.com/TahaSohail-Goat/SabaqAI/blob/main/LICENSE)

</div>

A full RAG pipeline, not a chatbot wrapper: retrieval runs against the real FBISE textbook and
past-paper corpus (embedded with Jina AI, stored in Supabase pgvector), and a **confidence gate
blocks the LLM call entirely** when similarity is too low — the app says a topic isn't covered
rather than inventing an answer. On top of that: chapter-scoped quizzes graded server-side, live
mastery tracking per chapter, a deterministic day-by-day revision planner, and Urdu voice input.

| Layer | Choice |
|---|---|
| App | Next.js 16 (App Router, Turbopack) + TypeScript + Tailwind |
| Database | Supabase — Postgres + pgvector + Auth + Storage |
| Embeddings | Jina AI `jina-embeddings-v3`, retrieval filtered by board + class + subject |
| Generation | Google Gemini, with citations validated server-side against retrieved chunks |
| Voice | Whisper via Groq (Urdu speech-to-text) |
| 3D | three.js + react-three-fiber + gsap |

<p align="left">
<img src="./profile/pin-sabaqai.svg"/>
</p>

**Live:** https://sabaq-ai-three.vercel.app • **Code:** https://github.com/TahaSohail-Goat/SabaqAI

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=38bdf8&height=40&section=header&animation=fadeIn"/>
</p>

## 🚀 More Projects

### Studify — AI-Powered Study Companion
Full-stack MERN study platform where students chat with their own notes via a custom RAG pipeline with local embeddings and MongoDB Atlas Vector Search, plus AI summaries, quizzes, and OCR for scanned documents. Ships secure auth (JWT + email OTP), rate limiting, per-user data isolation, and multi-provider LLM failover.

<p align="left">
<img src="./profile/pin-studify.svg"/>
</p>

| Layer | Technology |
|---|---|
| Frontend | React |
| Backend | Node.js, Express |
| Database | MongoDB Atlas (Vector Search) |
| AI/ML | Local RAG, OCR, Multi-provider LLM failover |
| Auth | JWT, Email OTP |

**Live:** https://studify-six.vercel.app • **Code:** https://github.com/TahaSohail-Goat/Studify

### Smart Disaster Response MIS
Full-stack disaster management information system with role-based dashboards, real-time coordination, SQL Server triggers, and ACID transactions.

<p align="left">
<img src="./profile/pin-smart-disaster-response-mis.svg"/>
</p>

| Layer | Technology |
|---|---|
| Frontend | Next.js |
| Backend | Node.js, Express.js |
| Database | SQL Server |
| Features | RBAC Dashboards, Triggers, ACID Transactions |

**Code:** https://github.com/TahaSohail-Goat/SmartDisasterResponseMIS

### Cybercrime Digital Evidence Integrity Management System
Desktop evidence management system with SHA-256 tamper detection, immutable chain-of-custody logs, a state-machine workflow, and RBAC for three investigative roles.

<p align="left">
<img src="./profile/pin-cdiem.svg"/>
</p>

| Layer | Technology |
|---|---|
| Application | Java, JavaFX |
| Database | SQL Server |
| Security | SHA-256 Integrity Verification, Chain-of-Custody Logs |

**Code:** https://github.com/TahaSohail-Goat/CDIEM

### Ocean Route Navigator
Maritime route planner using Dijkstra's and A* algorithms, built with custom priority queues and graph data structures.

<p align="left">
<img src="./profile/pin-searoute-navigator.svg"/>
</p>

| Layer | Technology |
|---|---|
| Language | C++ |
| Library | SFML |
| Algorithms | Dijkstra's, A* Search |

**Code:** https://github.com/TahaSohail-Goat/SeaRoute-Navigator

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=38bdf8&height=40&section=header&animation=fadeIn"/>
</p>

## 🛠 Tech Stack

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=js,ts,py,java,cpp,cs,c"/>

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite,html,css"/>

**Backend**
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,django,flask"/>

**AI / Database**
<br/>
<img src="https://skillicons.dev/icons?i=pytorch,mongodb,sqlite,supabase"/>

*Also working with: SQL Server, LangChain, LangGraph, Scikit-learn, Pandas*

**Dev Tools**
<br/>
<img src="https://skillicons.dev/icons?i=git,github,docker,vscode,postman"/>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=38bdf8&height=40&section=header&animation=fadeIn"/>
</p>

## 📈 GitHub Stats

<p align="left">
<img src="./profile/stats.svg" height="165"/>
<img src="./profile/top-langs.svg" height="165"/>
</p>

<p align="left">
<img src="https://streak-stats.demolab.com?user=TahaSohail-Goat&theme=nord&border=38bdf8"/>
</p>

<p align="left">
<img src="https://github-profile-trophy.vercel.app/?username=TahaSohail-Goat&theme=nord&no-frame=true&row=1&column=7"/>
</p>

<p align="left">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=TahaSohail-Goat&theme=react-dark&color=38bdf8&line=38bdf8&point=ffffff&bg_color=0d1117"/>
</p>

### 🐍 Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TahaSohail-Goat/TahaSohail-Goat/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/TahaSohail-Goat/TahaSohail-Goat/output/github-contribution-grid-snake.svg" />
  <img alt="A snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/TahaSohail-Goat/TahaSohail-Goat/output/github-contribution-grid-snake.svg" />
</picture>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=38bdf8&height=40&section=header&animation=fadeIn"/>
</p>

## 📬 Connect

<p align="left">
<a href="https://tahasohail.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-38bdf8?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/taha-sohail-7b03b8320/"><img src="https://img.shields.io/badge/LinkedIn-38bdf8?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:tahasohail85@gmail.com"><img src="https://img.shields.io/badge/Email-38bdf8?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38bdf8,100:0f172a&height=120&section=footer"/>
</p>
