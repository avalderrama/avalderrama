## Hi, I'm Alexander Valderrama 👋

**Senior Data & AI Architect** · Medellín, Colombia 🇨🇴

20+ years designing data platforms, now building AI products end to end: from the data and the models to the app
people hold in their hands. **I build AI tools that help people get care and information in time.**

My mother went through breast cancer. Seeing what she lived through taught me that, with this disease, acting in
time is what saves lives — and that in many parts of Latin America there is no radiologist nearby to read a
mammogram. That is why I started building AI for healthcare.

*Hola 👋 Soy arquitecto de datos e IA. Construyo herramientas de IA para que las personas reciban atención e
información a tiempo.*

---

### 🩺 AI Mammogram Triage

An AI tool that helps physicians see which mammograms look the most worrying, so those women reach a radiologist
first. With high-resolution images, on patients the model never saw, it flags **87 %** of BI-RADS 4-5 cases as
*High priority* or *Review*, with only **6.5 %** of normal cases in *High priority*.

| Repository | What it is |
|---|---|
| [**ai-mammogram-triage**](https://github.com/avalderrama/ai-mammogram-triage) | MCP server in Python: personal-data masking, mammogram check, EfficientNet-B0 ensemble with a high-resolution patch model, calibrated priority levels, heatmaps. CPU inference with ONNX Runtime in 1–3 s per image. Clean (onion) architecture enforced by tests |
| [**ai-mammogram-triage-app**](https://github.com/avalderrama/ai-mammogram-triage-app) | Installable PWA in React + TypeScript: photograph a mammogram with a phone and get the triage result, in English or Spanish. Images never stored |
| `ai-mammogram-triage-training` *(private)* | Data, training, external validation and calibration |

> Research tool, not a medical device. Physicians who want to try it in a pilot can
> [request access here](https://forms.gle/2msrWXkJW7Cj9rYV8).

### 🎨 MonoKromatik — [monokromatik.pro](https://monokromatik.pro)

*Founder & architect.* A multi-tenant SaaS for creative professionals (photographers, video producers, designers):
each one gets a public site with portfolio, pricing, a quote calculator and WhatsApp hand-off, plus a searchable
directory. Designed, built and shipped to production solo, with Claude Code as the main development agent.

- Clean / hexagonal architecture in C# / .NET (Razor Pages, EF Core)
- Azure production stack: Docker VM behind Caddy with blue-green deployments, PostgreSQL, Blob Storage, Cloudflare,
  GitHub Actions CI/CD, daily backups and monitoring
- Media pipeline with direct-to-Blob signed uploads and a transactional outbox → PostgreSQL queue → background worker

### 🔎 Percept — Generative Engine Optimization at Chromatics AI

*Senior data architect.* A platform that tracks how brands appear in the answers of AI assistants (OpenAI, Gemini,
Perplexity). I architect its data, backend and API layer:

- Multi-provider LLM pipelines that run tracked prompts daily for each brand, decoupled from the web layer
- Citation attribution: parsing LLM answers into sources and URLs to compute the competitive gap
- Brand-entity resolution across engines and phrasings, and an analytics layer for a 12-section AI visibility report
- Python, FastAPI, PostgreSQL, SQLAlchemy and Alembic in live production

### 🌦️ Monitor de El Niño en Colombia

[**monitor-elnino-colombia**](https://github.com/avalderrama/monitor-elnino-colombia) — a daily, verified monitor of
El Niño's effects in Colombia (drought, fires, water, emergencies, food prices), by municipality and with sources.
Skeptical by design: it only attributes an event to El Niño when the source does, checks the date of the event, not
of the article, and keeps its own corrections visible.

---

### 📈 Before AI products

- **9 years as sole data architect** of a regulated US money-transfer company: AWS data lake and warehouse with
  250M+ transactions, an **ML fraud-detection system that cut fraud by 80 %**, and the data side of its migration to
  Salesforce Sales Cloud (~20,000 agent locations)
- Data warehouses with **2B+ records** across Colombia, Peru, Mexico and Argentina
- **15+ years** working remotely with US-based companies

### 🛠️ What I work with

- **AI / ML:** PyTorch, ONNX Runtime, model calibration and validation, LLM pipelines (OpenAI, Gemini, Perplexity,
  Claude), RAG, MCP, agentic development with Claude Code, LoRA fine-tuning, OCR
- **Backend:** Python, FastAPI, C# / .NET, PostgreSQL, SQL Server, clean / hexagonal architecture
- **Frontend:** React, TypeScript, PWA, accessibility (WCAG 2.2 AA), i18n
- **Data & cloud:** AWS (Glue, S3, Redshift, Lambda), Azure, Databricks, Docker, Cloudflare, GitHub Actions

### 📫 Let's talk

I'm open to collaborations with physicians, researchers, organizations and investors who want AI to reach the
people who need it most.

[LinkedIn](https://www.linkedin.com/in/alexander-valderrama-a9a01910)
