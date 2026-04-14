### Hi, I'm Vini

AI researcher building memory systems for LLM agents — inspired by how brains consolidate knowledge during sleep.

---

#### DREAM — sleep-inspired memory consolidation

LLMs forget. Most "memory" systems are just retrieval over a flat buffer. DREAM is different: it consolidates memories through a *sleep* cycle that mirrors how the human brain processes the day's experiences — extracting structure, resolving contradictions, and discovering analogies across domains.

The result is a memory system that becomes *more useful* the longer it runs, not just larger.

#### Highlights

- **95.4% on LoCoMo** (LLM-judge, gpt-4o-mini answerer) — competitive with reported SOTA on long-term conversational memory.
- **Dual-pathway consolidation** — slow-wave (SWS) replay for assimilation + REM-like creative recombination for cross-domain links. Both implemented, both ablated.
- **Cross-domain discovery** — surfaces structural analogies between physics, biology, economics that flat-RAG baselines never produce.
- **Hebbian retrieval-time edge reinforcement** — first known LLM memory system applying *neurons-that-fire-together-wire-together* during query, not training.
- **Patent pending** — USPTO #64/013,667 (filed March 2026).

#### What I'm working on now

Preparing a NeurIPS/ICLR submission with **SCHEMA** — a 225-question benchmark across 9 cognitive categories (cross-domain connection, abstraction, counterfactual reasoning, selective forgetting, interference, temporal reasoning, multi-hop, retention, adversarial abstention). The four most-claimed memory abilities aren't covered together by any existing benchmark; SCHEMA is.

In flight:
- External baselines (Mem0, HippoRAG) under apples-to-apples protocol.
- 3-judge triangulation (GPT-4o-mini + Gemini 2.5 Flash + Claude Haiku 4.5) to defuse self-preference bias.
- Human anchor validation with Fleiss κ pre-registered thresholds.
- Pre-registered hypothesis database (every change auditable, Kapoor 2023 immune).

#### MCP integration

DREAM ships as a [Model Context Protocol](https://modelcontextprotocol.io) server — it works as a long-term memory backend for Claude Code, Claude Desktop, and any MCP-compatible client. Talk to it like a normal AI; it remembers, consolidates, and connects what you say across sessions.

#### Tech

`Python` · `ChromaDB` · `NetworkX` · `DeBERTa NLI` · `nomic-embed` · `FSRS` · `gpt-4o-mini` · `MCP` · `Three.js`

#### Links

- Paper: *coming soon on arXiv (cs.AI)*
- 3D brain visualization (Three.js): [docs/prototype/](docs/prototype/)

---

*"The metric matters more than the system."*
