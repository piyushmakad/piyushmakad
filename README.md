# Piyush Makad

**Full Stack AI Engineer | Production LLM products, MCP, and backend systems**

I have 2.2+ years of experience shipping AI features and high-volume backend services. At ChatDaddy, I work across React interfaces, LLM workflows, APIs, data systems, and production reliability.

## Production AI work

- Architected and published a **120-tool MCP platform** for messaging, CRM, automation, and commerce, with typed schemas, team-scoped access, and approval-gated writes.
- Built a **prompt-to-flow generator** with React and OpenAI Responses that turns natural-language requests into structured, editable automation workflows; refined generated steps through human-led evaluation.
- Owned **Daily AI Reports** end to end, including 24-hour analytics comparisons, LLM prompts, fallback handling, billing, email, and React UI.
- Shipped **LLM-powered WhatsApp Business insights** that use conversation histories and account quality signals to recommend ways to improve messaging performance.
- Created **Architect Suite**, whose code was adopted into ChatDaddy's production Backend Doctor. It correlates Kibana, frontend, and backend evidence across **257 patterns and 22 services**. With human approval, AI-assisted triage cut investigation time from **1–2 hours to 10–15 minutes** and reduced the ticket backlog from **30–40 to 2–3**.

## Backend engineering

- Built hot/cold data partitioning across MongoDB and cold storage with Elasticsearch-backed search, maintaining double-digit millisecond response times.
- Made contact lookups **5× faster** and removed **290K+ API and operational calls per day**.
- Reduced decryption failures on retried WhatsApp channel messages from **65% to under 1%** across **200K+ daily messages**.
- Root-caused a production PostgreSQL disk-full outage to an orphaned replication slot retaining **200GB+ of WAL**.

## Selected public projects

### [PulseFlow](https://github.com/piyushmakad/Pulseflow)

A Go portfolio project for multi-tenant event ingestion and notification delivery. It uses a PostgreSQL transactional outbox, Kafka, Redis, tenant-scoped idempotency, bounded workers, durable retries, and dead-letter recovery. Its API, worker, and migration roles can run with Docker or Kubernetes.

### [PrepTime](https://github.com/piyushmakad/prep-time) · [Live demo](https://prep-time.vercel.app/)

A real-time AI mock-interview app built with Next.js, TypeScript, Vapi voice agents, Gemini, and Firebase, with persistent interview history and structured feedback.

### [AutoGit AI](https://github.com/piyushmakad/ai-github-app) · [Live demo](https://ai-github-app.vercel.app/)

A repository-intelligence app for codebase summaries, semantic code search, commit analysis, and meeting transcription, built with Next.js, TypeScript, PostgreSQL, Prisma, Gemini, embeddings, and vector search.

## Technologies

**AI and full stack:** React.js, Next.js, OpenAI Responses API, MCP, LLM tool calling, Gemini, Vapi, Tailwind CSS  
**Backend and data:** Node.js, TypeScript, Go, PostgreSQL, MongoDB, Elasticsearch, Redis, Kafka, RabbitMQ, REST, SSE, Socket.IO  
**Cloud and delivery:** Docker, Kubernetes, AWS EKS, Oracle OKE, GitHub Actions, CI/CD

## Connect

[Portfolio](https://piyush-portfolio-ruby.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/piyush-makad-758834244/) · [Email](mailto:piyush.makad16@gmail.com)
