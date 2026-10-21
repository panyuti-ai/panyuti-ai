# Hi, I'm Yu-Ting (Pan) 👋

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

📍 Taiwan | 💻 **Software Engineer (Go & Python)** | 🤖 **AI Tooling & Real-Time Backends**

Software engineer building backend services, AI evaluation tooling, and developer tools. I use **Go** for real-time blockchain event indexing and monitoring, and **Python / TypeScript / JavaScript** for LLM-based tooling, retrieval, and web apps.

---

### 🚀 Featured Projects

- **🔍 [`citecheck`](https://github.com/panyuti-ai/citecheck): Citation Verifier for AI-written Answers (Python)**
  CLI that checks whether the pages cited in an AI-written Markdown answer actually support the claims they are attached to. It fetches each page (with a Wayback Machine fallback), ranks passages with **Okapi BM25**, and has an LLM judge (Claude Code or Codex CLI) label each citation. On my hand-labeled sets it matched 16–20 of 20 citations (v1, three runs) and 13 of 14 (v2); the README documents the misses and limitations.

- **📚 [`course-search`](https://github.com/panyuti-ai/course-search): Course Search & Planner for Feng Chia University (Node.js)**
  Search and planning site covering 3,570 course sections (115-1), with an official-syllabus crawler, AI-generated syllabus summaries, AI course analysis, and a schedule planner. Express + PostgreSQL, deployed on Railway, with campus NID OAuth login.

- **⚡ Cross-Chain USDC Indexers (Go)**
  [`cctp-bridge-monitor`](https://github.com/panyuti-ai/cctp-bridge-monitor) watches Circle CCTP V1 transfers across 7 chains (WebSocket subscriptions plus Solana polling), pairs sent/received events, resumes from checkpoints, and serves a live dashboard. [`usdc-indexer`](https://github.com/panyuti-ai/usdc-indexer) indexes USDC Transfer events on Ethereum into SQLite with a built-in dashboard.

- **📈 [`crypto-grid-bot`](https://github.com/panyuti-ai/crypto-grid-bot): Grid Trading Bot (Python)**
  Automated MEXC spot trading with dynamic grid logic, risk control, batch tracking, and Discord metrics and alerts.

---

### 🛠️ Tech Stack & Focus Areas

- **Languages:** Go, Python, TypeScript, JavaScript, SQL
- **AI tooling:** LLM APIs (Anthropic, OpenAI-compatible), LLM-as-judge evaluation, BM25 passage retrieval, AI-assisted development with Claude
- **Backend:** Node.js / Express, Gin, REST APIs, PostgreSQL, SQLite, web crawling and data pipelines, blockchain RPC / event indexing
- **Security background:** Wrote up 28 Ethernaut levels ([`ethernaut-writeups`](https://github.com/panyuti-ai/ethernaut-writeups)) while learning smart contract security

---

### 📫 Contact

- **Email:** panyouting1124@gmail.com
