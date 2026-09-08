# 👋 Hi, I'm Colin

<div align="left">
  <a href="https://www.linkedin.com/in/colin-j-emmanuel">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="https://github.com/Colin-J-Emmanuel">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</div>

## 🎓 About Me

I'm a Computer Science graduate from Columbia University who builds backend systems, ML/NLP applications, and full-stack tools. I trained as a Machine Learning Fellow through the Break Through Tech AI program at Cornell Tech.

I'm most at home designing event-driven backends, shipping full-stack apps against real databases, and wiring LLMs into practical tools. Recent work spans a production-grade multi-agent PR reviewer, a terminal coding agent, and a three-app web suite — details below.

**🎯 Focus:** Backend & distributed systems · Machine learning engineering · AI-powered tools · Data analytics

---

## 🔧 Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

### AI/ML & Data Science
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=python&logoColor=white)

### Frameworks & Libraries
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)

### Cloud & Tools
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

### Databases
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)

---

## 🚀 Featured Projects

### 🤖 [Multi-Agent PR Reviewer](https://github.com/Colin-J-Emmanuel/multi-agent-pr-reviewer) — Event-Driven AI Code Review
*Parallel LangGraph agents that review GitHub pull requests the way a senior engineer would*

An event-driven system that reviews GitHub pull requests with parallel specialist agents for security, code quality, testing, and documentation. It's a hands-on study of the reliability engineering *around* agents — webhook verification, latency isolation, idempotency, verification gates, and cost control — not just an LLM in a loop.

- **Stack:** Python · FastAPI · Redis · LangGraph · PostgreSQL + pgvector · Docker · LangSmith
- **Architecture:** HMAC-verified webhook ingestion → async Redis pipeline → four-agent LangGraph with deterministic aggregation → idempotent posting behind a confidence gate
- **Highlights:** Unified Postgres data layer with pgvector search, bounded retries with failure classification and attempt limits, and full observability — LangSmith tracing, verified cost accounting, and a daily spend ceiling

### 🖥️ [Terminal Coding Agent](https://github.com/Colin-J-Emmanuel/terminal-coding-agent) — AI Development Assistant
*A ReAct-loop coding agent that reasons, calls tools, and runs code inside a sandbox*

Takes natural-language instructions and acts on your filesystem through a tool system — reading and writing files, searching a codebase, and executing code in a Docker sandbox. Built around the ReAct (Reason–Act–Observe) loop and Anthropic's Claude API, with the load-bearing pieces hand-built for understanding.

- **Stack:** Python · Claude API · Docker · pytest
- **Architecture:** ReAct agent loop over a tool registry (`write_file`, `read_file`, `search_code`) with context persistence and history summarization at a token threshold
- **Highlights:** Docker-based execution sandbox with a code validator and pinned timeout bounds, backed by a pytest suite

### 🎭 [The Humor Project](https://github.com/Colin-J-Emmanuel/the-humor-project) — Full-Stack App Suite
*Three interconnected Next.js apps on a shared Supabase backend*

A production-deployed system for authoring AI prompt chains, generating and rating image captions, and administering the platform. Built over a semester for Columbia's COMSW-4995.

- **Stack:** Next.js (App Router, TypeScript) · Supabase · Tailwind CSS v4 · Vercel
- **The apps:** [Prompt Chain Tool](https://github.com/Colin-J-Emmanuel/humor-prompt-chain) (authoring) · [Caption Rating App](https://github.com/Colin-J-Emmanuel/hello-world-humor-project) (public voting) · [Admin Panel](https://github.com/Colin-J-Emmanuel/humor-admin-panel) (back-office + analytics)
- **Highlights:** Google OAuth with role-based access gates, a four-step caption-generation pipeline, and a vote-analytics dashboard — all built against a shared, RLS-aware multi-tenant database

---

## 📈 GitHub Activity

<div align="center">
  <img src="https://github-stats-lovat-ten.vercel.app/api?username=Colin-J-Emmanuel&show_icons=true&hide_rank=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" height="165">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Colin-J-Emmanuel&theme=default&hide_border=true" alt="GitHub Streak" height="165">
</div>
<div align="center">
  <img src="https://github-stats-lovat-ten.vercel.app/api/top-langs/?username=Colin-J-Emmanuel&layout=compact&theme=default&hide_border=true&langs_count=6" alt="Top Languages">
</div>

---

## 💼 Open to Opportunities

I'm looking for full-time roles in:

- **Software Engineering** — backend & distributed systems
- **AI/Machine Learning Engineering**
- **Data Science & Analytics**

Currently going deeper on distributed-systems design, LLM infrastructure, and production ML — and always happy to talk shop with fellow builders.

---

## ⚽ Beyond the Code

When I'm not building, you'll find me on the soccer field, at the gym chasing incremental goals, or watching films and series for the storytelling. Staying active and engaged outside of tech keeps me a sharper problem-solver and collaborator.

---

## 📫 Let's Connect

- **LinkedIn:** [linkedin.com/in/colin-j-emmanuel](https://www.linkedin.com/in/colin-j-emmanuel)

---

<div align="center">
  <i>⚡ Fun fact: I fell down the ML rabbit hole trying to build a movie recommendation system. Turns out mimicking Netflix and Spotify is harder than it looks — but that failed first attempt is what hooked me.</i>
</div>
