# AI / Semiconductor / Battery Boom — Personal Investment System
Last updated: 2026-09-13
Status: **Phase 0 — Research & System Building (no capital deployed yet)**

---

## 1. GOAL

Grow a small recurring monthly investment into significant long-term capital by riding a connected
chain of tech booms:

**AI / Semiconductor demand → Power & Grid buildout → Battery & Raw Materials demand**

- Platform: INDmoney app, US stocks, via Federal Bank / GIFT City account route.
- Capital: ₹1,000/month (committed, starting the month investing actually begins) + occasional
  irregular add-ons of ₹100–200 (not guaranteed monthly).
- Horizon: long-term hold. A strategy **pitstop / reassessment checkpoint** is planned around
  **2030–2033**, after which the approach may change with whatever capital has been built.
- Investor profile: no prior investing experience, high tolerance for volatility, low tolerance
  for fees eating a small monthly amount, wants a repeatable *system* rather than one-off picks.

---

## 2. PORTFOLIO STRUCTURE (agreed shape — tickers not yet finalized)

| Slot | Purpose | Notes |
|---|---|---|
| **Core 1 — AI / Semiconductor ETF** | Broad exposure to chip/AI leaders (e.g. NVIDIA, TSMC, Broadcom) in one buy | Avoids single-company risk. Ticker TBD (e.g. SMH/SOXX-style fund — verify current options in-app). |
| **Core 2 — Battery / Raw Materials ETF** | Broad exposure to global battery makers + critical minerals miners | Ticker TBD (e.g. LIT/PICK-style fund — verify in-app). |
| **Satellite — Power / Grid Infrastructure** | Smaller, rotating slice covering the "connective tissue" link (data center power, grid, nuclear/energy buildout) | Lower conviction than the two cores; size flexes over time. |
| **Individual mega-cap "core stock"** | A single company to accumulate slowly, forever-style hold | **UNRESOLVED — see Open Decisions below.** Dividend requirement has been dropped. Choice is between durability (e.g. Microsoft) vs. maximum theme exposure (e.g. NVIDIA) vs. a middle ground (e.g. Broadcom, Amazon, Alphabet). |

**Monthly buy discipline:** the fixed ₹1,000 splits across Core 1 / Core 2 / Satellite on a set
ratio (to be finalized). Irregular ₹100–200 add-ons go opportunistically toward whichever theme
looks most compelling that period, or toward the individual core stock once chosen — especially
if it's trading low relative to its own recent average while the rest of the portfolio is green
(exact "dip" definition still needs to be set — see Open Decisions).

---

## 3. FEES

- Account type: INDmoney Federal Bank / GIFT City route.
- No fixed remittance fee on this route — cost is a **percentage-based forex spread**
  (roughly 0.5–1.2%, unconfirmed — verify current number in-app).
- Brokerage per trade: small/capped — verify current number in-app.
- **Action item:** open the app's live pricing page and record the exact current numbers here.

---

## 4. RESEARCH METHOD

Not technical analysis. Not hourly/daily price-watching. A **quarterly fundamental review** of a
small set of leading indicators — things that move *before* they show up in prices:

- Hyperscaler capex guidance revisions (raised/cut vs. prior quarter)
- Data center grid/power buildout progress (interconnection queues, new power deals)
- Battery cost-per-kWh trend and commercialization milestones (not just lab announcements)
- Critical minerals supply/price signals (lithium, copper, etc.)
- Custom silicon vs. merchant GPU market share shifts

**Multi-AI survey process:** each quarter, take the same standardized question set to 2–3 other
AI tools. Log their answers in `ai-opinions-log.md`. Bring the log back to this system for
synthesis — agreement across models = higher confidence; disagreement = flag it and dig into why,
rather than picking one answer at random.

**Event logging, not constant monitoring:** log only genuinely *material* geopolitical/market
events in `event-log.md` as they happen (a sentence or two). Review the log pattern once a month.

---

## 5. REVIEW CADENCE

- **Monthly:** quick check — did anything material happen? Does it need action now, or wait for
  the quarterly review?
- **Quarterly:** full review — indicators + multi-AI survey + decision entry.
- **2030–2033 Pitstop:** predefined trigger conditions decide whether/how the strategy changes.
  **Not yet written — this is a required Open Decision before the pitstop date matters.**

---

## 6. OPEN DECISIONS (unresolved — revisit when ready, not blockers)

1. **Individual core mega-cap stock** — durability vs. max theme exposure vs. middle ground.
   Candidates discussed: Microsoft, NVIDIA, Amazon, Alphabet, Broadcom.
2. **Exact "dip-buy" rule** — e.g., price vs. its own 50-day/200-day moving average, or relative
   strength vs. a sector ETF. Needs a precise, mechanical definition once the core stock is picked.
3. **Core 1 / Core 2 / Satellite split ratio** — exact percentages not yet fixed.
4. **Pitstop trigger conditions for 2030–2033** — must be written *before* that period arrives,
   while decisions can be made calmly rather than emotionally in the moment.
5. **Real fee numbers** — confirm current forex spread % and brokerage from the live app.

---

## 7. FILES IN THIS SYSTEM

| File | Purpose | Status |
|---|---|---|
| `system-rules.md` | This file — the constitution of the system | Living document |
| `research-log.md` | Findings as each chain-link (AI/semi, power, battery) gets researched | To start |
| `event-log.md` | Material geopolitical/market events only | To start |
| `ai-opinions-log.md` | Template log of questions taken to other AI tools + their answers | To start |
| `portfolio-snapshot.md` | Actual holdings/amounts | Empty until investing begins |
| `monthly/` | One file per month once investing starts | Empty |
| `quarterly-review/` | One file per quarter once investing starts | Empty |

**Template for `ai-opinions-log.md` entries:**
```
Date:
Question asked:
AI tool used:
Their answer (2-3 lines):
Agrees / disagrees with prior conclusion:
Notes:
```

---

## 8. HOW THIS SYSTEM IS BUILT (infrastructure notes)

- **Level 1 (do now):** these markdown files live in a repo (e.g. GitHub, free), managed via
  Google Antigravity (free agentic IDE) instead of manual copy-pasting each session.
- **Level 2 (once Level 1 has real content):** a simple free viewer page (e.g. GitHub Pages)
  displays the files nicely. Still not live data — just a formatted mirror of what's written here.
- **Level 3 (later, only once real money is invested):** automated sync of real portfolio data
  from INDmoney's MCP into `portfolio-snapshot.md` on a schedule. Grant **read-only** access to
  any AI agent connected to a financial account — never write/trade permissions.

---

## 9. HOW TO USE THIS FILE IF STARTING A NEW SESSION / NEW AI

Paste or link this file first. It contains the full goal, structure, method, and open decisions
as of the last update. Update the "Last updated" line and relevant sections whenever a real
decision is made — this file is the single source of truth, not any one conversation.
