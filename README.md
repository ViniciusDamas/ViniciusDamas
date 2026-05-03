### Hi, I'm Vini

Building **DREAM** — a memory layer for AI agents and researchers that consolidates knowledge instead of just retrieving it.

Patent pending — USPTO #64/013,667.

---

#### The problem

LLMs forget. Most "memory" systems are flat retrieval — every session starts cold and accumulated context evaporates at every context-window edge.

For researchers, this is the central bottleneck: the cost of *re-discovering what you already knew* compounds with project age.

#### The thesis

A memory system should get **more useful** the longer it runs, not just larger.

DREAM borrows from how the brain consolidates experience during sleep: episodic memories enter a fast store, then a periodic offline cycle organizes them, surfaces contradictions, builds emergent structure, and selectively forgets noise. What you query weeks later isn't a transcript — it's a coherent knowledge layer.

#### What's shipped

- **`dream-api`** — production backend on HF Spaces. EU AI Act Article 12 compliant by architecture (full audit trail + per-memory provenance).
- **MCP server** — DREAM works as long-term memory backend for Claude Code, Claude Desktop, and any MCP-compatible client.
- **REST API** — OpenAPI/Swagger documented.
- **`dream-visual`** — Three.js visualization of the consolidation cycle, plus an early researcher-tool prototype at `/research`.
- **Dogfooded** — I use DREAM to build DREAM.

#### What I'm working on now

A polished researcher tool (codename **memex**) — the SaaS surface for the long-term memory layer, built on `dream-api`. Active roadmap focuses on document ingestion, retrieval-quality upgrades, and a researcher-grade UX.

#### Numbers

**90.3% on LoCoMo** (10-conversation aggregated, gpt-4o-mini judge).

#### Tech

`Python` · `MCP` · `FastAPI` · `ChromaDB` · `Three.js` · hosted on HuggingFace Spaces PRO.

#### Links

- DREAM Visual: https://vinelima-dream-visual.hf.space

---

*"The metric matters more than the system."*
