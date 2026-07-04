<h1 align="center">Akshat Lakhera</h1>

<p align="center">
  <b>Backend &amp; Systems Engineer</b> · Agentic AI · Quantitative &amp; High-Performance Computing
  <br />
  B.Tech. Computer Science &amp; Applied Mathematics @ IIIT Delhi (2023–2027)
</p>

<p align="center">
  <i>I build fast, reliable systems — from OS internals and distributed pipelines to LLM agents and parallel numerical solvers.</i>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/akshat-lakhera-iiit-delhi/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://akshat-lakhera-portfolio.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://leetcode.com/u/AKSHAT_LAKHERA/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
  <a href="https://codeforces.com/profile/Akshat_Lakhera">
    <img src="https://img.shields.io/badge/Codeforces-1F4ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" />
  </a>
  <a href="mailto:akshat23061@iiitd.ac.in">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

## About Me

Systems-oriented engineer with a strong CS + applied-math foundation (DSA, OS, DBMS, Computer Networks, Parallel Programming, Probability &amp; Stochastic Processes, Convex Optimization). I like problems where correctness, latency, and scale all matter at once — distributed backends, concurrency, and numerical computing — and I'm currently deep in **agentic AI** and **quantitative / high-performance systems**.

- 🛠️ **Backend & distributed systems** — FastAPI, Spring Boot, Kafka, REST microservices over TCP/IP.
- ⚡ **Systems & HPC** — C/C++ on Linux, multithreading, OpenMP/MPI, OS internals.
- 🤖 **Agentic AI** — LLM orchestration with LangGraph/LangChain, RAG, and MCP — with deterministic guardrails where money moves.
- 📈 **Quantitative computing** — parallel PDE solvers and performance-critical numerical modeling.
- 🧩 **Codeforces Specialist (max 1458)** — **750+ problems** solved (550+ LeetCode, 200+ Codeforces).
- 🏆 **IMC Prosperity 4 Finalist** — World Rank **823** · All-India Rank **175** · Algorithmic Rank **278**.

> 💼 Open to **SDE · Backend · Quant · AI** — internships &amp; full-time (Class of 2027).

---

## Experience

### Software Developer Intern — Grove Growth · Jan 2026 – Apr 2026
- Shipped a production **gamified campus-ambassador platform for 100+ users** — dual portals, live leaderboards, and **20+ REST APIs** in **TypeScript / Next.js** on a **17-table Supabase (PostgreSQL)** schema across Agile sprint cycles.
- Eliminated concurrency defects under peak load via **atomic transactions and row-level locking**; enforced secure coding (input validation, parameterized queries) and validated releases with **433 automated tests** across 21 suites.

### Undergraduate Research — Parallel Computing for Scientific &amp; Financial Simulations · Aug 2025 – Dec 2025
- Accelerated HPC simulation kernels **15×** by parallelizing with **OpenMP and MPI**, recovering **60+ compute-hours** through multithreaded optimization and performance profiling.
- Implemented **Black-Scholes option-pricing PDE solvers** (Explicit, Implicit, Crank-Nicolson) in C++ and parallelized the explicit scheme, cutting per-cycle solve latency from **2.69 s to 6 ms**.

### Software Developer Intern — DRDO (ISSA Lab, Metcalfe House) · Jun 2025 – Jul 2025
- Engineered asynchronous **inter-service communication between C++ and Java (Spring Boot) microservices using Kafka over TCP/IP** in a distributed, mission-critical defense system, improving processing efficiency by **60%**.
- Trained a **YOLOv8** maritime vessel-detection model on HRSC2016 satellite imagery to **0.83 mAP@0.5**, with **OpenCV**-based image preprocessing and a custom XML→YOLO annotation parser.
- Streamlined C++ Linux service deployments into a **CI/CD pipeline**, eliminating manual integration errors across test environments.

---

## Featured Projects

### [ReturnGuard — Multi-Tenant Returns Resolution Platform](https://github.com/akl-akshat/ReturnGuard) · Python, FastAPI, LangGraph, Kafka, PostgreSQL
- Multi-tenant returns-automation service on an **11-node stateful agent graph** — driven synchronously (REST) and asynchronously (a **Kafka** pipeline), with each tenant's uploaded refund policy grounding every decision via per-tenant vector retrieval (pgvector).
- Money path built to stay correct under failure and concurrency: **deterministic guardrails** (payout caps, rate limits) evaluated outside the model, plus **idempotent execution with a transactional outbox** — retries and redeliveries never double-pay.
- Adversarially red-teamed with every fix pinned by a regression test; **200+ tests** run in CI, gating merges on a **44-case labelled eval** — **88.6% auto-resolution with zero guardrail violations**.

### [Custom Unix Shell with MLFQ Scheduler](https://github.com/akl-akshat/OperatingSystems) · C, Makefile, Linux
- Programmed an **MLFQ-based scheduler daemon** inside a custom C shell (fork/exec/wait system calls), managing **30+ concurrent processes** with adaptive priority scaling (~12% CPU-utilization gain under load).
- Added **semaphore-based synchronization** and timing-driven deadlock detection, eliminating race conditions under heavy concurrency.

### [Black-Scholes Option Pricing via Parallel Computing](https://github.com/akl-akshat/Black-Scholes-using-Parallel-Computing) · C++, Python, OpenMP, MPI
- Built finite-difference solvers for the Black-Scholes PDE with **MPI** and **OpenMP**, using domain decomposition and ghost-cell communication.
- Benchmarked runtime, stability, and accuracy across serial, MPI, and OpenMP variants with supporting analysis.

### CiPD 360 — ERP &amp; LMS for IIIT Delhi · Next.js, PostgreSQL, Node.js
- Launched a full-stack **ERP + LMS serving 250+ students and faculty** — **40+ REST APIs**, analytics dashboards, and event-driven email workflows over a 19-table PostgreSQL architecture.
- Designed a **Wi-Fi-based real-time attendance system** using MAC/BSSID detection backed by Node.js services.

---

## Tech Stack

**Languages**

<p>
  <img src="https://img.shields.io/badge/C-283593?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-E76F00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111111" alt="JavaScript" />
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
</p>

**Backend &amp; Systems**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka" />
  <img src="https://img.shields.io/badge/Linux-B45309?style=for-the-badge&logo=linux&logoColor=111111" alt="Linux" />
  <img src="https://img.shields.io/badge/TCP%2FUDP%2FIP-0F766E?style=for-the-badge&logoColor=white" alt="TCP/UDP/IP" />
  <img src="https://img.shields.io/badge/OpenMP-1D4ED8?style=for-the-badge&logoColor=white" alt="OpenMP" />
  <img src="https://img.shields.io/badge/MPI-047857?style=for-the-badge&logoColor=white" alt="MPI" />
  <img src="https://img.shields.io/badge/Multithreading-7C2D12?style=for-the-badge&logoColor=white" alt="Multithreading" />
</p>

**Frontend &amp; Data**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/MySQL-1F2937?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
</p>

**AI &amp; ML**

<p>
  <img src="https://img.shields.io/badge/LangGraph-FF6F00?style=for-the-badge&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/RAG-059669?style=for-the-badge&logoColor=white" alt="RAG" />
  <img src="https://img.shields.io/badge/MCP-2563EB?style=for-the-badge&logoColor=white" alt="MCP" />
  <img src="https://img.shields.io/badge/LLM%20Applications-412991?style=for-the-badge&logo=openai&logoColor=white" alt="LLM Applications" />
  <img src="https://img.shields.io/badge/YOLOv8-8B5CF6?style=for-the-badge&logoColor=white" alt="YOLOv8" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
</p>

**DevOps &amp; Tooling**

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/CI%2FCD-4B5563?style=for-the-badge&logoColor=white" alt="CI/CD" />
</p>

---

## Achievements

- 🏅 **Codeforces Specialist** — max rating **1458**; **750+ DSA problems** solved (550+ LeetCode, 200+ Codeforces).
- 🏆 **IMC Prosperity 4 Finalist** — IMC Trading's global algorithmic trading competition · World Rank **823** · All-India Rank **175** · Algorithmic Rank **278**.
- 🎓 **SMP Recognition Award (2025–26)** — Student Mentor, IIIT Delhi's Student Mentorship Program.
- 🚀 State-level qualifier, **Smart India Hackathon 2024**.
- 🔢 **Mathematics topper — CBSE 2021** with a perfect **100/100**.
- 🎤 Delivered **3+ tech workshops at ESYA** (IIIT Delhi's tech fest) to **200+ participants** with 90%+ positive feedback.

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=akl-akshat&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&cache_seconds=21600" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=akl-akshat&layout=compact&theme=tokyonight&hide_border=true&hide=cuda&cache_seconds=21600" alt="Top Languages" />
</p>

<p align="center">
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=akl-akshat&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>
