# Piyush Makad

Backend-leaning full-stack engineer focused on performance, reliability, distributed systems, and AI-enabled products.

I currently work at ChatDaddy, building real-time messaging, automation, commerce, and platform capabilities with Node.js and TypeScript. Recent production work includes:

- Reducing contacts-related API latency from 800 ms to under 150 ms and eliminating 290K+ unnecessary calls per day
- Reducing decryption failures for retried messages from 65% to under 1%
- Building a MongoDB and Elasticsearch hot/cold data layer with double-digit-millisecond response times
- Root-causing a PostgreSQL outage caused by an orphaned replication slot pinning 200 GB+ of WAL
- Building observability tooling that surfaced 257 error patterns across 22 microservices
- Architecting and publishing a 120-tool MCP platform across Claude, Codex, Cursor, and VS Code

## Selected projects

### [PulseFlow](https://github.com/piyushmakad/Pulseflow)

A multi-tenant event-ingestion and notification-delivery platform built around production-oriented reliability patterns.

- Go, PostgreSQL transactional outbox, Kafka, Redis, and tenant-scoped idempotency
- Explicit state machines, bounded worker pools, durable retries, and dead-letter recovery
- Separate API, worker, and migration roles deployed with Docker, Kubernetes, Kustomize, and Oracle OKE
- Race-tested CI, graceful shutdown, lease recovery, backlog monitoring, and multi-architecture image builds

### [PrepTime](https://github.com/piyushmakad/prep-time)

A real-time AI mock-interview platform that conducts role-specific voice interviews and provides structured feedback.

- Next.js, TypeScript, Vapi voice agents, Gemini, and Firebase
- Persistent interview history and end-to-end interview practice flows
- [Live demo](https://prep-time.vercel.app/)

### [AutoGit AI](https://github.com/piyushmakad/ai-github-app)

A repository-intelligence platform for codebase summarization, semantic source-code search, commit analysis, and meeting transcription.

- Next.js, TypeScript, PostgreSQL, Prisma, Gemini, embeddings, and vector search
- [Live demo](https://ai-github-app.vercel.app/)

## Core technologies

**Backend and systems:** Node.js, TypeScript, Go, Kafka, RabbitMQ, Redis, PostgreSQL, MongoDB, Elasticsearch, REST, SSE, Socket.IO, MCP

**Cloud and delivery:** AWS, EKS, Oracle OKE, Kubernetes, Docker, Kustomize, GitHub Actions, CI/CD

**Frontend and AI:** React, Next.js, Tailwind CSS, Gemini, Vapi, Firebase

## Current focus

- Distributed-system reliability and failure recovery
- Event-driven architectures and high-throughput backend services
- Go concurrency and production-oriented service design
- AI automation and developer tooling

## Languages and Tools

<p align="left">
  <img src="https://skillicons.dev/icons?i=js,ts,go,python,java,nodejs,express,react,nextjs,tailwind,postgres,mongodb,mysql,redis,kafka,rabbitmq,docker,kubernetes,aws,github&perline=20" alt="Languages and tools" />
</p>

## GitHub snapshot

<p>
  <img height="155" src="https://github-readme-stats.vercel.app/api?username=piyushmakad&show_icons=true&hide_border=true&theme=transparent&rank_icon=github&include_all_commits=true" alt="Piyush Makad's GitHub statistics" />
  <img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=piyushmakad&layout=compact&hide_border=true&theme=transparent&langs_count=6" alt="Most-used repository languages" />
</p>

## Connect

[LinkedIn](https://www.linkedin.com/in/piyush-makad-758834244/) · [Email](mailto:piyush.makad16@gmail.com)
