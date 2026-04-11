### Hi, I'm Vini

AI researcher building memory systems that learn the way brains do — through sleep.

---

#### DREAM — Dual-pathway Retrieval-Enhanced Agent Memory

> *What if AI agents could consolidate memories during sleep, just like humans?*

DREAM is a sleep-inspired memory consolidation system for LLM agents. It implements biological principles — slow-wave sleep replay, Piagetian routing (assimilation/accommodation/novelty), FSRS forgetting curves, and Hebbian retrieval-induced reconsolidation — to give AI agents long-term memory that improves with use.

**Key results:**
- 95.4% on LoCoMo benchmark (LLM-as-judge) with gpt-4o-mini
- First system with persistent retrieval-time edge updates (Hebbian co-activation)
- Cross-domain connection discovery: 3.00/3.00 (perfect score on custom benchmark)
- All experiments on consumer hardware (AMD Athlon 2C/4T, 8GB RAM, no GPU)

**Patent pending** — USPTO #64/013,667 (filed March 2026)

#### Tech

`Python` `ChromaDB` `NetworkX` `Three.js` `DeBERTa NLI` `nomic-embed` `FSRS` `gpt-4o-mini`

#### Links

- Paper: *coming soon on arXiv (cs.AI)*
- Visual demo: [3D brain visualization](docs/prototype/) built with Three.js

---

*"The metric matters more than the system."*
