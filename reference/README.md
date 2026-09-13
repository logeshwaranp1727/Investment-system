# Valuation Reference Files

Source: `github.com/anthropics/financial-services` (official Anthropic repo, Apache 2.0 license).
Cloned and manually reviewed on 2026-09-13 — confirmed genuine origin, no suspicious code or
prompt-injection patterns found in these files.

These are **reference documents**, not auto-running agents. Antigravity should consult them the
way you'd consult a textbook — read and apply the methodology, don't execute anything from them
as a script.

## Files
- `valuation-methodologies.md` — the core reference: DCF, trading comps, precedent transactions,
  and how to reconcile all three into a final valuation range. Start here.
- `dcf-model.md` — detailed DCF build skill (longer, more mechanical detail).
- `comps-analysis.md` — detailed trading comparables skill (longer, more mechanical detail).
- `initiating-coverage.md` — the overall workflow these pieces plug into (full company research →
  valuation → recommendation).

## How to use
Add this whole `reference/` folder into your repo (e.g. alongside `expert-framework.md`).
This is the deep-dive tool for when we finally tackle the open "individual mega-cap core stock"
decision — running a real DCF + comps analysis on a candidate like Microsoft or NVIDIA, rather
than eyeballing ratios.

## Attribution
Original content © Anthropic, Apache License 2.0. Reused here under that license.
