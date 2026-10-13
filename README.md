<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img src="assets/hero-light.svg" width="100%" alt="Noreddine Bekkouche — AI Engineer. Grounded retrieval, agents and MCP systems, built for production. Available for missions.">
</picture>

I design and ship LLM systems end to end, from document ingestion to production APIs. Backend roots in **Python** and **TypeScript**, so the AI part holds up in production rather than in a notebook. I run **Outlier**, an independent engineering & creative studio.

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/h-capabilities-dark.svg">
  <img src="assets/h-capabilities-light.svg" width="100%" alt="Capabilities">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/capabilities-dark.svg">
  <img src="assets/capabilities-light.svg" width="100%" alt="RAG pipelines, agentic systems, MCP servers, document AI, evals and fine-tuning, enterprise integration.">
</picture>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/h-system-dark.svg">
  <img src="assets/h-system-light.svg" width="100%" alt="Selected system">
</picture>

<a href="https://github.com/tiger440/groundcite">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/groundcite-dark.svg">
  <img src="assets/groundcite-light.svg" width="100%" alt="groundcite — retrieval funnel: ACL filter inside the index scan, dense and lexical retrieval, reciprocal rank fusion, rerank, span-level citation.">
</picture>
</a>

| Component | Design choice |
|---|---|
| **Retrieval** | Dense (pgvector) and lexical (Postgres full-text), fused with reciprocal rank fusion, then reranked |
| **Citations** | Every claim points at exact `(document, start, end)` character offsets, preserved through parsing and chunking |
| **Permissions** | ACL filters applied inside the index scan, never as a post-filter — recall measured per scope |
| **Evals** | Each stage of the funnel measured separately, paired bootstrap confidence intervals |
| **Storage** | Postgres only. No managed vector service |

**[Repository →](https://github.com/tiger440/groundcite)** &nbsp;&nbsp; **[ML companion docs →](https://tiger440.github.io/groundcite/)** &nbsp;&nbsp; <sub>Also: [n8n-ready](https://github.com/tiger440/n8n-ready), a ready-to-use automation base</sub>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/h-stack-dark.svg">
  <img src="assets/h-stack-light.svg" width="100%" alt="Stack">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.svg">
  <img src="assets/stack-light.svg" width="100%" alt="Models and AI: Claude, MCP, LangChain, pgvector, OCR. Backend: Python, FastAPI, Django, TypeScript, NestJS. Data and delivery: PostgreSQL, Prisma, Docker, Next.js, XState.">
</picture>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/contact-dark.svg">
  <img src="assets/contact-light.svg" width="100%" alt="Let's build something grounded. Available for missions, Paris and remote. 10+ clients, 5.0 rating on Malt.">
</picture>

<sub>Off-duty — MMA · chess as [he-huizheng](https://www.chess.com/member/he-huizheng) · fashion design</sub>
