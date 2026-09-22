# Hi, I'm Alex 👋

**AI Product Manager. I turn AI agents into products that generate revenue — observable, evaluated, auditable.**

Most AI pilots never prove their revenue impact. I ship the ones that do, and prove it in euros.

10+ years turning messy, regulated data into products that move the number.

I build and ship products with impact, not decks:

- **+30M€** unlocked through data quality
- **+8M€** from a pricing product at Decathlon
- **300M€/year** billing platform at BNP Paribas
- **−75%** production time on core reporting

Built observability platforms tracking AI adoption across the BNP Paribas Group. Ran data teams, roadmaps, and stakeholders in regulated industries where failure costs millions.

Then I started building for myself.

---

## What I'm shipping

| Project | What it does | Status |
|---|---|---|
| [nanoAgent](https://github.com/alexandre-darmon/nanoagent) | Agent loop built from scratch, no framework — the nanoGPT of agents | 🟢 Live |
| [EvalBlink](https://github.com/alexandre-darmon/evalblink) | Benchmark prompts × models × tests — quality, cost, latency in one command | 🟢 Live |
| [The AI Compass](https://the-ai-compass.vercel.app) | 10-day email course — AI for non-technical professionals | 🟢 Live |
| [SASU IS Simple](https://www.sasu-is-simple.fr) | Salary vs dividends optimizer for French freelancers | 🟢 Live |
| **ValuePick** | Value-investing screener with LLM-powered thesis generation | 🔨 Building |

---

## Inside nanoAgent

Most people learn an agent framework before they understand what an agent loop actually is.

nanoAgent inverts that: a tool-calling loop written in plain Python, no framework. About **20 lines** run the whole thing. Skills load on demand, the same progressive-disclosure pattern behind Claude's own Skills, rebuilt from first principles.

I ran it on financial tasks, across multiple models and providers, and logged every call. Three findings mattered more than the code:

- **The provider is a second dial below the model.** Same model, same question: one provider took 18s and followed every skill exactly. Another took 8s and drifted.
- **Progressive disclosure isn't free.** Loading skill descriptions on demand cost **+95 tokens** every turn. Loading full skill bodies upfront cost **+266**. On-demand only pays off once a good share of your skills go unused.
- **One sentence beat every code change.** A single line added to a skill file cut a 1,351-token turn down to under 90.

> The loop is the easy part. What decides cost, speed, and correctness sits outside it — the model, the provider, and how the instructions are written.

That's the part most agent demos skip past.

[→ Full repo, logs, and measurements](https://github.com/alexandre-darmon/nanoagent)

---

## What I care about

The gap between "we have an AI strategy" and "our AI product has 10,000 users" is where I work.

Real users. Real revenue. AI that earns its place in the business.

---

## Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-alexdarmon-blue?logo=linkedin)](https://www.linkedin.com/in/alexdarmon/)
[![Website](https://img.shields.io/badge/Website-alexdarmon.net-black?logo=vercel)](https://www.alexdarmon.net)

📍 Paris, France
