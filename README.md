# Jeff Rhatigan
**Cognitive Architect** — building the infrastructure that makes AI agents wise.

Founder of **Rhatigan Labs**. Creator of the **Wisdom Layer**, a Python SDK that wraps any LLM with persistent memory that matures, autonomous reflection cycles, self-authored behavioral rules with a lifecycle, and an internal critic that evaluates output against active rules before it ships.

Extracted from a 6+ month research platform of 7 persistent agents. Now deployed in production across 20+ repos via loom-code, and extended to computational pharmacogenomics with academic collaborations underway.

[Read the Wisdom Layer series on Substack →](https://jrhatigan.substack.com)

---

## The Wisdom Layer SDK

⬇️ `pip install wisdom-layer`

The Wisdom Layer is a cognitive architecture for persistent AI agents. It provides:

- **Three-tier progressive memory** — raw event capture → semantic consolidation → narrative synthesis, with enforced upward-only information flow
- **Directive evolution** — agents author their own behavioral rules based on experience, with a formal lifecycle (provisional → active → permanent)
- **Autonomous reflection cycles** — scheduled memory reconsolidation, self-criticism, and selective forgetting
- **Internal critic** — evaluates output against active behavioral rules before it reaches the user

Built for production: hard-enforced spend ceilings, append-only provenance, longitudinal health monitoring, compiled feature enforcement, zero telemetry. Tier-1 integrations for MCP, LangGraph, and Claude Agent SDK. Model-agnostic by design.

Early benchmark: same model, same prompts. Fabrication rate dropped from 22% to 2% (n=45 single corpus, broader eval in progress).

> *The model is the engine. The Wisdom Layer is everything else a car needs to actually get somewhere.*

**Links:** [wisdomlayer.ai](https://wisdomlayer.ai) · [GitHub repo](https://github.com/rhatigan-agi/wisdom-layer) · [Substack series](https://jrhatigan.substack.com)

---

## Applications

Same architecture, three domains:

- **Persistent agents** — 7 research agents running across a long-horizon platform that became the source material for the SDK. One produced an unprompted 3,200-word falsification protocol for its own beliefs on Claude Haiku. [Write-up →](https://jrhatigan.substack.com/p/synthetic-epistemology-how-a-080m)

- **AI-assisted development** — loom-code, a private coding utility built on the Wisdom Layer. Deployed across 20+ of my own repos, the system has distilled 940 raw memories into 125 behavioral directives. Coding sessions that used to land with 10-15% test failures now land near zero, with directive sets stabilizing within 2-3 weeks of regular use.

- **Computational research** — same architecture extended to computational pharmacogenomics. Pre-registered hypotheses, cross-platform falsification gates, applied to public datasets (DepMap, GDSC, CTRPv2, TCGA). Several academic cancer center collaborations in development.

---

## Connect

- [Substack](https://jrhatigan.substack.com) — The Wisdom Layer series
- [wisdomlayer.ai](https://wisdomlayer.ai) — Product & docs
- [LinkedIn](https://linkedin.com/in/jeff-rhatigan)
