<div align="center">
  <a href="https://github.com/matheuskaiky">
    <img src="https://github-readme-stats.vercel.app/api?username=matheuskaiky&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  </a>
  <br/>
  <a href="https://github.com/matheuskaiky">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=matheuskaiky&layout=compact&langs_count=8&theme=tokyonight"/>
  </a>
</div>

# Matheus Kaiky

Computer Science student at the Federal University of Piauí (UFPI), Brazil. Software engineer with a focus on applied AI: backend systems, NLP pipelines and LLM applications that run on-premise for government and privacy-sensitive use cases.

[LinkedIn](https://www.linkedin.com/in/matheuskaiky/)

## Experience

**Undergraduate Researcher, PIBITI (UFPI), Brazil's national undergraduate technology and innovation research program**
Designed and built Termo Fácil (below) for the Piauí Public Security Department (SSP-PI). The research grant has ended. The system was delivered and demonstrated to SSP-PI.

## Projects

### [Termo Fácil](https://github.com/matheuskaiky/termo-facil): Deposition Statement Generator
Event-driven, on-premise system that transcribes police deposition audio and drafts the written statement (*termo de depoimento*) for SSP-PI. Built for PIBITI; delivered and demonstrated to SSP-PI.

- Pipeline: Whisper (ASR) → pyannote speaker diarization → LeNER-Br (legal NER) → local LLM via Ollama or vLLM at temperature 0.0, with the LLM output anchored to the extracted entities.
- Asynchronous processing with Celery and Redis, audio stored in MinIO and purged for LGPD (Brazil's data protection law) compliance, state in PostgreSQL.
- Runs fully on-premise, with no cloud APIs. Deployable with Docker or on an HPC cluster without Docker or sudo.
- FastAPI backend, Angular 17 frontend, 21 documented development phases.

`Python` `FastAPI` `Celery` `Redis` `PostgreSQL` `MinIO` `Angular` `Docker` `Hugging Face` `Whisper` `Ollama` `vLLM`

### [llm-finetuning](https://github.com/matheuskaiky/llm-finetuning): LLM Lifecycle for Public-Sector Data
End-to-end LLM project for the course *Tópicos em IA* (UFPI, 2026.1), using Piauí municipal gazettes and faculty data. Everything is driven by YAML configs, so models and methods can be swapped without changing code.

- Continued pre-training, SFT, LoRA/QLoRA, knowledge distillation, a RAG assistant (standard, agentic and GraphRAG) and a rule-based guardrails layer.
- LoRA matched or beat full SFT while training about 1.7% of the parameters. Guardrails went from 0% to 100% blocking of adversarial prompts and PII on a synthetic benchmark.
- Trained and evaluated on 2x NVIDIA L4 GPUs. Benchmark references were generated with AI assistance, and a hand-written gold set is planned.

`Python` `PyTorch` `Transformers` `PEFT/TRL` `LangChain` `FAISS` `uv` `pytest`

### [Finanças Pessoais](https://github.com/matheuskaiky/financas-pessoais): Local-First Personal Finance
Private finance manager covering accounts, credit cards with invoices and installments, and fixed-income investments. Data stays in a local SQLite database, and the server listens only on localhost.

- Layered architecture (domain, application, infrastructure, interfaces), with layer rules enforced by import-linter.
- More than 1,300 tests, with static checks using ruff and pyright.
- Server-rendered with FastAPI, Jinja2 and HTMX, with no frontend build step.

`Python` `FastAPI` `SQLAlchemy` `Alembic` `SQLite` `HTMX` `pytest`

### [Gupyfy](https://github.com/matheuskaiky/Gupyfy): Job Search Automation (paused)
Full-stack app that uses generative AI to match job postings from Gupy to a candidate profile and sends notifications through n8n workflows.

`Java 17` `Spring Boot 3` `React` `PostgreSQL` `n8n` `Gemini / OpenAI APIs`

## Skills

- **Languages:** Python, Java, TypeScript/JavaScript, SQL, Bash
- **Backend:** FastAPI, Spring Boot, Celery, REST APIs, PostgreSQL, Redis, SQLAlchemy
- **AI/ML:** LLM fine-tuning (SFT, LoRA/QLoRA), RAG, NLP/NER, speech recognition, Hugging Face, LangChain, vLLM, Ollama
- **Frontend:** Angular, React, HTMX, Tailwind CSS
- **Tools and practices:** Docker, Git, Linux, HPC clusters, pytest, clean architecture

## Education

**B.Sc. in Computer Science**, Federal University of Piauí (UFPI), Brazil
