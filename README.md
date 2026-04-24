## Sebastian Tirelli

I work on LLM systems. Specifically the parts where they waste money, where they break, where they surprise.

Twelve years building software. Four of those leading engineering teams of 35+. Lately I write up what I find: ingestion cost leaks, retrieval reliability gaps, hash bugs that sit quietly in framework defaults. Rhythm is irregular, only when something is worth reading.

### Selected projects

- [**llamaindex-embedding-churn**](https://github.com/stirelli/llamaindex-embedding-churn). Reproducer for a two-bug interaction in `llama-index-core` that silently re-embeds unchanged content across half the fsspec backend ecosystem. Three-line fix filed upstream as [PR #21462](https://github.com/run-llama/llama_index/pull/21462). [Writeup](https://sebastiantirelli.com/writing/llamaindex-embedding-churn/).
- [**ChatGPT LightSession**](https://chromewebstore.google.com/detail/chatgpt-lightsession/fmomjhjnmgpknbabfpojgifokaibeoje). Chrome extension that trims long ChatGPT threads client-side. Currently at 60,000+ users and 4.8 stars, shipped without paid distribution. [Writeup](https://sebastiantirelli.com/writing/chatgpt-lightsession/).
- **CodeGraph**. Local MCP server I built for Claude Code. Pre-computes a tree-sitter call graph and exposes it through six tools. On a 484-file FastAPI benchmark: 59% fewer investigation tokens, 60% fewer turns, and 82 seconds less wall time, with file recall preserved at 100%. [Writeup](https://sebastiantirelli.com/writing/codegraph/).

### Background

- 12 years software engineering. 4 of those leading teams of 35+.
- Built an AI SDR platform end-to-end as a solo founder (LangGraph, async workers, human-in-the-loop). Reached production with paying users.
- Led architecture and evaluation / benchmarking pipelines for an AI memory and retrieval platform.
- UC Berkeley postgrad certificates in Machine Learning and AI, and Technology Leadership.

Based in Argentina. Italian and Argentine citizenship.

### Elsewhere

[sebastiantirelli.com](https://sebastiantirelli.com) · [LinkedIn](https://www.linkedin.com/in/stirelli) · [X / Twitter](https://x.com/stirelli) · tirelli@gmail.com
