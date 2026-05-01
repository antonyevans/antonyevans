# Antony Evans

Cambridge mathematician. YC-backed founder. Currently building at the **agentic commerce** layer — where AI agents shop, transact, and operate autonomously.

Background: maths → strategy consulting (Oliver Wyman, Bain) → startups → COO. I've raised $42M in venture capital, scaled a company to $50M revenue, and shipped software used by 500k+ people. Now building the infrastructure layer for agent-native commerce.

---

## 🔨 Active Projects

### [shop-cli](https://github.com/antonyevans/shop-cli)
**A shopping CLI built for AI agents, not humans.**

Humans configure it once — budgets, approval thresholds, spending policy. Agents use it to shop autonomously. The core primitive is a *mandate*: a signed, revocable spending delegation that encodes purchase policy. Agents reference a mandate ID on every order; they never see payment credentials.

- `git clone https://github.com/antonyevans/shop-cli && pip install -e shop-cli/`
- Every command returns JSON. All mutations take `--idempotency-key`. Semantic exit codes — agents branch on `3` (mandate violation), `5` (low confidence), `6` (retry-safe network error).
- Stack: Python 3.12, typer, pydantic v2, httpx (async), Ed25519 mandate signing, SQLite

### [Agent Engineer Master](https://agentengineermaster.com)
**Production-ready Claude Code skills, on demand.**

Submit a spec — get back a complete skill with SKILL.md, reference docs, evals, and scripts, built to the same standard as skills I run in production. The underlying skill architecture is open-source: a growing library of domain-specific skills covering marketing, product, legal, operations, and more.

- [agentengineermaster.com](https://agentengineermaster.com) — order a custom skill
- [Agent-Engineer-Master/skill-engineer](https://github.com/Agent-Engineer-Master/skill-engineer) — open-source skill library

### [Agentic Grocery Shopping](https://github.com/antonyevans/weekly-food-plan)
Multi-agent pipeline: Claude Code + MCP → recipe generation → cart population → phone notification. No human in the loop after the weekly trigger.

### [AI Doctor App](https://github.com/antonyevans/VirtualNurse)
Android symptom checker — **500k+ downloads**, medical content partnership with Harvard Medical School. Built in Java; still the highest-distribution thing I've shipped.

---

## ⚙️ Technical Stack

**AI / Agents:** Python, Claude SDK (Anthropic), Claude Code, MCP (Model Context Protocol), multi-agent orchestration, LangChain, RAG pipelines, prompt engineering

**Data:** SQL / BigQuery, Tableau, financial modeling (Excel/Python)

**Infrastructure:** Git, Jupyter, VS Code, REST APIs, Stripe

---

## 📍 Currently Building

- **shop-cli** — agent-native shopping protocol ([github.com/antonyevans/shop-cli](https://github.com/antonyevans/shop-cli), alpha)
- **Finch Toys** — DTC dropship store with agentic commerce infrastructure underneath
- **Agent Engineer Master** — skill-as-a-service platform for Claude Code ([agentengineermaster.com](https://agentengineermaster.com))

---

## 📫 Connect

- [LinkedIn](https://www.linkedin.com/in/antonyevans)
- [X / Twitter](https://twitter.com/antonyevans)
- antonyevans@gmail.com
