<div align="center">
  <a href="https://github.com/matheuskaiky">
    <img src="https://github-readme-stats.vercel.app/api?username=matheuskaiky&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  </a>
  <br/>
  <a href="https://github.com/matheuskaiky">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=matheuskaiky&layout=compact&langs_count=8&theme=tokyonight"/>
  </a>
</div>

### Hi there 👋, I'm Matheus Kaiky!

I'm a Computer Science student at the Federal University of Piauí passionate about **AI-driven automation** and **building systems that solve real governmental problems**. Currently focused on intelligent document generation, cloud-native architectures, and leveraging modern AI tooling for rapid, high-quality development.

## 🚀 Current Work

### **Termo Fácil** – Intelligent Deposition Statement Generator
**Status:** 🔴 Active Development (PIBITI Research Grant)

An **AI-powered system** for the Piauí Public Security Department that intelligently transcribes, extracts entities, and synthesizes police deposition statements with absolute **juridical traceability**.

**Key Architecture:**
- **ASR Layer** (Whisper Turbo / Parakeet TDT) → Speech-to-text with diarization
- **NER Layer** (LeNER-Br / BERT) → Fact-locking, entity extraction (names, dates, locations, laws)
- **LLM Layer** (vLLM, Ollama) → Deterministic synthesis (Temperature 0.0, on-premise)
- **Compliance:** 100% on-premise (Air-gapped), LGPD-compliant, zero cloud APIs

**Tech Stack:** `Python 3.11` | `FastAPI` | `HuggingFace Transformers` | `Redis/Celery` | `MinIO` | `Docker` | `WireGuard VPN` | `HPC Mandu (Supercomputer)`

**Docs & Specs:**
- [Especificação de Requisitos (ERS)](./docs/1-ersw-pibiti.pdf)
- [Product Backlog & User Stories](./docs/2-backlog-pibiti.pdf)
- [UX/UI & Design System](./docs/3-ui-ux-pibiti.pdf)
- [Architecture & System Design (C4, DER, ADR)](./docs/4-arquitetura-pibiti.pdf)

---

### **Gupyfy** – AI-Powered Job Search Automation
**Status:** 🟠 Paused (architecture stable)

A full-stack application that uses **generative AI to automate job discovery** on the Gupy platform. Demonstrates production-grade architecture for AI integration, asynchronous job processing, and end-to-end automation.

**Key Features:**
- RESTful API with Spring Boot 3 + Spring Data JPA
- React SPA with advanced filtering and real-time updates
- AI matching engine (Google Gemini / OpenAI integration)
- Workflow automation via n8n for smart notifications (Telegram, Discord, Email)
- Job scheduling with asynchronous processing (background workers)

**Tech Stack:** `Java 17+` | `Spring Boot 3` | `React 18` | `Vite` | `Tailwind CSS` | `PostgreSQL` | `n8n` | `OkHttp` | `Maven`

**Repository:** [github.com/matheuskaiky/Gupyfy](https://github.com/matheuskaiky/Gupyfy)

---

### **TCC: IA Forense** – Forensic Intelligence (thesis-in-progress)
**Status:** 🟡 Research Phase

Exploring AI techniques for digital forensics and investigative intelligence within governmental constraints.

## 🛠️ Tech Stack & Skills

### **AI/ML & Prompt Engineering**
<p align="left">
  <a href="https://www.anthropic.com/claude" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Claude_AI-ED8B00?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude AI"/>
  </a>
  <a href="https://github.com/features/copilot" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Claude_Code-121212?style=for-the-badge&logo=github-copilot&logoColor=white" alt="Claude Code"/>
  </a>
  <a href="https://www.langchain.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white" alt="LangChain"/>
  </a>
  <a href="https://huggingface.co/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="HuggingFace"/>
  </a>
</p>

### **Backend & Infrastructure**
<p align="left">
  <a href="https://www.python.org" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  </a>
  <a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  </a>
  <a href="https://www.java.com" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Java_17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  </a>
  <a href="https://spring.io/projects/spring-boot" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot"/>
  </a>
  <a href="https://spring.io/projects/spring-data" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Data JPA"/>
  </a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  </a>
  <a href="https://www.postgresql.org/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  </a>
  <a href="https://redis.io/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
  </a>
  <a href="https://maven.apache.org/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white" alt="Maven"/>
  </a>
  <a href="https://n8n.io/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/n8n-121212?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n"/>
  </a>
</p>

### **Frontend & Design**
<p align="left">
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/React_18+-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  </a>
  <a href="https://vitejs.dev/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
  </a>
  <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS"/>
  </a>
  <a href="https://axios-http.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios"/>
  </a>
  <a href="https://www.figma.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma"/>
  </a>
</p>

### **DevOps & Cloud**
<p align="left">
  <a href="https://kubernetes.io/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  </a>
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  </a>
  <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash"/>
  </a>
</p>

## 💡 Development Philosophy

I believe in **pragmatic AI-assisted development**: leveraging Claude Code and modern LLMs as productivity multipliers while maintaining **deep understanding** of architecture, trade-offs, and system design. Not "just prompts" — but **thoughtful engineering accelerated by intelligent tooling**.

My approach:
- ✅ Architecture-first design (C4 models, ADRs, system thinking)
- ✅ Prompt engineering as a *professional skill* (not a shortcut)
- ✅ Code generation + human judgment (not blind automation)
- ✅ Testing, documentation, and security by default

## 📫 Get in Touch

- **LinkedIn:** [matheuskaiky](https://www.linkedin.com/in/matheuskaiky/)
- **GitHub:** [@matheuskaiky](https://github.com/matheuskaiky)
- **Email:** Through LinkedIn DMs

---

<div align="center">
  <h3>Olá! 👋 Eu sou o Matheus Kaiky!</h3>
</div>

Sou estudante de Ciência da Computação na Universidade Federal do Piauí, apaixonado por **automação inteligente com IA** e **construir sistemas que resolvem problemas reais do governo**. Atualmente focado em geração inteligente de documentos, arquiteturas cloud-native e aproveitando ferramentas modernas de IA para desenvolvimento rápido e de alta qualidade.

## 🚀 Projetos em Andamento

### **Termo Fácil** – Gerador Inteligente de Termos de Depoimento
**Status:** 🔴 Desenvolvimento Ativo (Bolsa PIBITI)

Um **sistema alimentado por IA** para a Secretaria de Segurança Pública do Piauí que transcreve, extrai entidades e sintetiza inteligentemente termos de depoimento policial com **rastreabilidade jurídica absoluta**.

**Arquitetura Principal:**
- **Camada ASR** (Whisper Turbo / Parakeet TDT) → Fala para texto com diarização
- **Camada NER** (LeNER-Br / BERT) → Blindagem de fatos, extração de entidades
- **Camada LLM** (vLLM, Ollama) → Síntese determinística (Temperature 0.0, on-premise)
- **Compliance:** 100% on-premise (Air-gapped), LGPD-compliant, zero APIs nuvem

**Tech Stack:** `Python 3.11` | `FastAPI` | `HuggingFace Transformers` | `Redis/Celery` | `MinIO` | `Docker` | `WireGuard VPN` | `HPC Mandu`

---

### **Gupyfy** – Automação Inteligente de Busca de Vagas
**Status:** 🟠 Pausado (arquitetura estável)

Uma aplicação full-stack que utiliza **IA generativa para automatizar a descoberta de vagas** na plataforma Gupy. Demonstra arquitetura de produção para integração com IA, processamento assíncrono de jobs e automação end-to-end.

**Principais Funcionalidades:**
- API RESTful com Spring Boot 3 + Spring Data JPA
- SPA React com filtros avançados e atualizações em tempo real
- Engine de matching com IA (integração Google Gemini / OpenAI)
- Automação de workflows via n8n para notificações inteligentes (Telegram, Discord, Email)
- Agendamento de jobs com processamento assíncrono (workers em background)

**Tech Stack:** `Java 17+` | `Spring Boot 3` | `React 18` | `Vite` | `Tailwind CSS` | `PostgreSQL` | `n8n` | `OkHttp` | `Maven`

**Repositório:** [github.com/matheuskaiky/Gupyfy](https://github.com/matheuskaiky/Gupyfy)

---

### **TCC: IA Forense** – Inteligência para Perícia Digital
**Status:** 🟡 Fase de Pesquisa

Explorando técnicas de IA para perícia digital e inteligência investigativa dentro de restrições governamentais.

## 🛠️ Tech Stack & Habilidades

### **IA/ML & Engenharia de Prompts**
<p align="left">
  <a href="https://www.anthropic.com/claude" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Claude_AI-ED8B00?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude AI"/>
  </a>
  <a href="https://github.com/features/copilot" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Claude_Code-121212?style=for-the-badge&logo=github-copilot&logoColor=white" alt="Claude Code"/>
  </a>
  <a href="https://www.langchain.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white" alt="LangChain"/>
  </a>
  <a href="https://huggingface.co/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="HuggingFace"/>
  </a>
</p>

### **Backend & Infraestrutura**
<p align="left">
  <a href="https://www.python.org" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  </a>
  <a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  </a>
  <a href="https://www.java.com" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Java_17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  </a>
  <a href="https://spring.io/projects/spring-boot" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot"/>
  </a>
  <a href="https://spring.io/projects/spring-data" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Data JPA"/>
  </a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  </a>
  <a href="https://www.postgresql.org/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  </a>
  <a href="https://redis.io/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
  </a>
  <a href="https://maven.apache.org/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white" alt="Maven"/>
  </a>
  <a href="https://n8n.io/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/n8n-121212?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n"/>
  </a>
</p>

### **Frontend & Design**
<p align="left">
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/React_18+-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  </a>
  <a href="https://vitejs.dev/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
  </a>
  <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS"/>
  </a>
  <a href="https://axios-http.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios"/>
  </a>
  <a href="https://www.figma.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma"/>
  </a>
</p>

### **DevOps & Cloud**
<p align="left">
  <a href="https://kubernetes.io/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  </a>
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  </a>
  <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash"/>
  </a>
</p>

## 💡 Filosofia de Desenvolvimento

Acredito em **desenvolvimento pragmático assistido por IA**: aproveitando Claude Code e LLMs modernos como multiplicadores de produtividade enquanto mantenho **compreensão profunda** de arquitetura, trade-offs e design de sistemas. Não é "apenas prompts" — mas **engenharia pensada acelerada por ferramentas inteligentes**.

Minha abordagem:
- ✅ Design arquitetural primeiro (modelos C4, ADRs, pensamento sistêmico)
- ✅ Engenharia de prompts como uma *habilidade profissional* (não um atalho)
- ✅ Geração de código + julgamento humano (não automação cega)
- ✅ Testes, documentação e segurança por padrão

## 📫 Entre em Contato

- **LinkedIn:** [matheuskaiky](https://www.linkedin.com/in/matheuskaiky/)
- **GitHub:** [@matheuskaiky](https://github.com/matheuskaiky)
- **Email:** Através de DMs no LinkedIn
