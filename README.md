# Sushil Dalavi

I'm a software engineer, and I finished my MS in Computer Science at USC in May 2026. I mostly build backend and
distributed systems, with a good amount of retrieval and model serving work alongside.

## Things I've built

### [AegisFS](https://github.com/sushildalavi/aegisfs)

A distributed file system in C++20. Each file is kept on three nodes, any node can take a request, and there is no
metadata server. I built it to learn consistent hashing, gossip membership and crash-safe writes by implementing them.

### [SyncSpace](https://github.com/sushildalavi/SyncSpace)

A collaborative text editor that lets you keep typing when your connection drops. Yjs merges the edits, PostgreSQL
stores them and Redis passes them between API servers. Written in TypeScript with Next.js and NestJS.

### [nanoserve](https://github.com/sushildalavi/nanoserve)

A small LLM serving engine for Apple Silicon, with its own scheduler and decode loop on top of PyTorch. It runs
TinyLlama and has benchmarks against Hugging Face, llama.cpp and MLX.

### [Sourcery](https://github.com/sushildalavi/sourcery)

Ask questions about research papers and get answers with inline citations. It searches uploaded PDFs or public sources
such as arXiv and OpenAlex, then scores how well the cited passages support the answer. FastAPI, pgvector and React.

### [Sidequest](https://github.com/sushildalavi/Sidequest)

A map for finding places, saving them and turning them into a plan. Spring Boot and Angular, with PostGIS for
nearby-place queries.

## Background

- USC Annenberg, Norman Lear Center (June 2025 to May 2026): AI infrastructure, mainly data pipelines and
  validation for multilingual social and media datasets.
- Reliance Jio (December 2023 to July 2024): backend services in Java and Kotlin.
- University of Southern California: MS in Computer Science, May 2026.
- University of Mumbai: BE in Computer Engineering, 2023.

Away from the keyboard it's usually Real Madrid, anime, music, swimming or table tennis.

[LinkedIn](https://www.linkedin.com/in/sushildalavi/) · [Website](https://sushildalavi.dev) · [Email](mailto:sushildalavi@gmail.com)
