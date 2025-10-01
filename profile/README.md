# thecontextcache™  
**Privacy-first, local-first memory engine for AI research.**  

---

## 🔎 What We’re Building  
**thecontextcache** is a **local-first, zero-knowledge memory engine** that ingests documents, extracts knowledge **quads (subject, predicate, object, context)**, and returns explainable answers with **citations and cryptographic audit trails**.  

It is designed for **researchers, students, and power users** who need **traceable, privacy-preserving AI answers** without relying on centralized SaaS platforms.  

---

## 🛠 Tech Stack  
- **Backend** → Python 3.13 · FastAPI · PostgreSQL (pgvector)  
- **Frontend** → Next.js (App Router) · TypeScript · Tailwind CSS · Cytoscape.js  
- **Security** → XChaCha20-Poly1305 · Ed25519 signatures · Argon2id KDF · BLAKE3 hash chains  
- **Infra** → Cloudflare Pages (frontend) · Google Cloud Run (backend) · Neon Postgres · Upstash Redis  
- **Docs** → Mintlify  

---

## 🚀 Current Status  
- ✅ **Phase 1 Complete** → Core models, crypto utilities, storage adapters  
- 🚧 **Phase 2 In Progress** → MCP servers (docs, extractor, memory, audit, policy-gate)  
- 📅 Upcoming → Frontend integration (Dashboard, Graph, Explain panel), test suites (pytest, Schemathesis, Playwright, k6), Mintlify docs  

---

## 📂 Repositories  
- **[contextcache](https://github.com/thecontextcache/contextcache)** → Main project repository  

---

## 🌐 Links  
- **Website** → [thecontextcache.com](https://thecontextcache.com)  
- **Social** → [Bluesky](https://thecontextcache.bsky.social)  
- **Email** → thecontextcache@gmail.com  

---

## 🤝 Contributing  
We welcome contributions! Please see [`CONTRIBUTING.md`](CONTRIBUTING.md) and join the conversation in [GitHub Discussions](https://github.com/orgs/thecontextcache/discussions).  

---

## ⚖️ Licensing  
Dual-licensed under:  
- [Apache 2.0](LICENSE-APACHE) → SDKs, client libraries, CLI tools, documentation  
- [PolyForm Noncommercial 1.0.0](LICENSE-PolyForm-NC) → server code (backend, analyzers, MCP servers, adapters)  

> **Trademark Notice:** *thecontextcache™* name and logo are reserved as trademarks of the maintainers.  
