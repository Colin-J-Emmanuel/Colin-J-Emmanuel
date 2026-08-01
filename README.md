# 👋 Hi, I'm Colin

<div align="left">
  <a href="https://www.linkedin.com/in/colin-j-emmanuel">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="mailto:c.j.emmanuel@columbia.edu">
    <img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail" alt="Email">
  </a>
</div>

## 🎓 About Me

I'm a Computer Science graduate from Columbia University with a passion for leveraging technology to solve real-world problems. Through the Break Through Tech AI program at Cornell Tech, I trained as a Machine Learning Fellow, building both technical expertise and professional skills to make meaningful contributions in the tech industry.

I'm enthusiastic about building data-driven solutions, designing backend systems, and creating intelligent applications. My work spans machine learning and NLP, full-stack web development, and event-driven backend services. I'm actively seeking full-time and/or internship opportunities where I can apply my skills, collaborate with industry professionals, and contribute to impactful projects.

**🎯 Current Focus:** Software engineering (backend & distributed systems), machine learning engineering, AI-powered tools, and data analytics

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

### 💳 [Midas Core](https://github.com/Colin-J-Emmanuel/forage-jpmc-advanced-swe) — Event-Driven Transaction Backend
*Java/Spring Boot backend processing financial transactions through a Kafka pipeline*

The backend of a transaction-processing system built for the J.P. Morgan Chase Advanced Software Engineering program. Transactions flow in from a Kafka topic, are validated against business rules, enriched via an external REST API, persisted to a relational database, and exposed through a REST endpoint.

- **Tech Stack:** Java 17, Spring Boot, Apache Kafka, Spring Data JPA, H2, RestTemplate, Maven
- **Architecture:** Layered design (Kafka listener → service → persistence) with separation of concerns; external systems isolated behind dedicated conduit components
- **Key Features:** JSON serialization across Kafka and HTTP boundaries, `@ManyToOne` JPA relationships, business-rule validation, and integration testing against embedded Kafka and in-memory H2
- **Learnings:** Event-driven architecture, consuming and exposing REST APIs, and convention-over-configuration with Spring Boot

### 🎭 [The Humor Project](https://github.com/Colin-J-Emmanuel/the-humor-project) — Full-Stack App Suite
*Three interconnected Next.js apps on a shared Supabase backend*

A suite of three production-deployed web apps forming an end-to-end system for authoring AI prompt chains, generating and rating image captions, and administering the platform. Built over a semester for Columbia's COMSW-4995.

- **Tech Stack:** Next.js (App Router, TypeScript), Supabase, Tailwind CSS v4, Vercel
- **The Apps:** [Prompt Chain Tool](https://github.com/Colin-J-Emmanuel/humor-prompt-chain) (authoring) · [Caption Rating App](https://github.com/Colin-J-Emmanuel/hello-world-humor-project) (public voting) · [Admin Panel](https://github.com/Colin-J-Emmanuel/humor-admin-panel) (back-office + analytics)
- **Key Features:** Google OAuth with role-based access gates, full CRUD over a shared schema, a four-step external caption-generation pipeline, and a vote-analytics dashboard
- **Learnings:** Building against a shared multi-tenant database, schema-first development, Next.js server actions, and RLS-aware data flows

### 🤖 [Terminal Coding Agent](https://github.com/Colin-J-Emmanuel/terminal-coding-agent)
*AI-Powered Development Assistant*

A sophisticated terminal-based coding agent that interprets natural language instructions and executes code safely using Claude AI. This project demonstrates practical application of LLM integration and secure code execution.

- **Tech Stack:** Python, Claude AI API, subprocess management
- **Key Features:** Natural language to code translation, sandboxed execution environment, error handling and debugging assistance
- **Impact:** Streamlines development workflow by enabling conversational programming
- **Learnings:** API integration, security best practices, prompt engineering

---

## 📈 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Colin-J-Emmanuel&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" height="165">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Colin-J-Emmanuel&theme=default&hide_border=true" alt="GitHub Streak" height="165">
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Colin-J-Emmanuel&layout=compact&theme=default&hide_border=true&langs_count=6" alt="Top Languages">
</div>

**📊 Contribution Highlights:**
- Actively maintaining personal projects with regular commits and updates
- Contributing to collaborative coursework and team projects
- Building a portfolio spanning backend systems, full-stack apps, and machine learning
- Consistent learning demonstrated through project evolution and skill development

---

## 🎯 What I'm Learning

As a recent Computer Science graduate, I'm continuously expanding my skill set:

- **Backend & Distributed Systems:** Event-driven architecture, message queues, REST API design, and layered service architecture
- **Advanced Machine Learning:** Deep learning, neural networks, and model optimization techniques
- **Natural Language Processing:** Text analysis, sentiment classification, and language model applications
- **Software Engineering Best Practices:** Clean code, testing, documentation, and collaboration workflows
- **Data Engineering:** ETL pipelines, data warehousing, and scalable data processing

---

## 🏆 Certifications & Programs

- **Break Through Tech AI Fellow** - Cornell Tech
  - Intensive machine learning foundations program
  - Industry collaboration and mentorship
  - Real-world project experience with tech companies
- **Advanced Software Engineering** - J.P. Morgan Chase (Forage)
  - Built an event-driven transaction-processing backend with Kafka, Spring Boot, and JPA

---

## ⚽ Beyond the Code

When I'm not coding or analyzing data, you can find me:
- **On the field:** Playing soccer—taught me the importance of teamwork, strategy, and staying focused under pressure
- **At the gym:** Maintaining discipline and setting incremental goals, skills that translate directly to tackling complex coding challenges
- **Exploring stories:** Watching films and series to unwind and appreciate narrative structure and character development

I believe staying active and engaged outside of tech makes me a better problem-solver and collaborator!

---

## 💼 Open to Opportunities

I'm actively seeking full-time roles, and summer 2026 internship opportunities if given the chance, in:
- **Software Engineering (backend & distributed systems)**
- **Machine Learning Engineering**
- **Data Science & Analytics**
- **AI/ML Research & Development**

I'm particularly interested in roles where I can apply my technical skills to solve meaningful problems, work with diverse teams, and continue learning from experienced professionals in the industry.

---

## 📫 Let's Connect!

I'm always excited to discuss technology, data science, collaboration opportunities, or just connect with fellow developers and learners!

- **Email:** c.j.emmanuel@columbia.edu | colinjemmanuel@gmail.com
- **LinkedIn:** [linkedin.com/in/colin-j-emmanuel](https://www.linkedin.com/in/colin-j-emmanuel)
- **Location:** New York City, NY

---

<div align="center">
  <i>⚡ Fun Fact: I fell down the ML rabbit hole trying to build a movie recommendation system. Turns out, mimicking Netflix and Spotify is harder than it looks—but that failed first attempt hooked me on machine learning!</i>
</div>
