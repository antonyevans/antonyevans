# Antony Evans

Cambridge mathematician. YC-backed founder. Currently building at the **agentic commerce** layer — where AI agents shop, transact, and operate autonomously.

Background: maths → strategy consulting (Oliver Wyman, Bain) → startups → COO. I've raised $42M in venture capital, scaled a company to $50M revenue, and shipped software used by 500k+ people. Now building the infrastructure layer for agent-native commerce.

---

## 🔨 Active Projects

### [shop-cli](https://github.com/antonyevans/shop-cli)
**A shopping CLI built for AI agents, not humans.**

Humans configure it once — budgets, approval thresholds, spending policy. Agents use it to shop autonomously. The core primitive is a *mandate*: a signed, revocable spending delegation that encodes purchase policy. Agents reference a mandate ID on every order; they never see payment credentials.

- `pip install shop-cli` → `shop search "..." --output json`
- Every command returns JSON. All mutations take `--idempotency-key`. Exit code 10 = escalated to human approval queue.
- Stack: Python, Stripe Agent Toolkit, ACP protocol, CommerceTXT/Schema.org

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

- **shop-cli** — agent-native shopping protocol (`pip install shop-cli`)
- **Finch Toys** — DTC dropship store with agentic commerce infrastructure underneath
- **Multi-agent executive OS** — Claude Code agent system managing strategy, content, and operations

---

## 📫 Connect

- [LinkedIn](https://www.linkedin.com/in/antonyevans)
- [X / Twitter](https://twitter.com/antonyevans)
- antonyevans@gmail.com
