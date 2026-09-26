# AYCAS Studios Brand Assets - house rules for every Claude session

AYCAS Studios Brand Assets is an AYCAS repo (AYCAS Investments (Pvt) Ltd, world `studios`). Added by retrofit-apply on 2026-09-25 (Stage 1 session entry).

## Read order

1. `PLAN.md` - the spec and phased plan; keep it current when a decision changes.
2. `AGENTS.md` - the rules every coding tool follows, and this repo's commands.
3. `docs/done-contract.md` and `docs/escalation.md` - what "done" means and what only Gus decides.
4. The AYCAS OS context pack for `studios` (loaded by the SessionStart hook; else `GET /api/context?world=studios`).

## Sessions

Plan mode for decisions, auto mode with the allowlist in `.claude/settings.json` for building. Bypass-permissions never. One branch per unit; conventional commits; everything lands via PR. Never push to the default branch; never deploy without Gus. Post decisions, rules and state to the AYCAS OS as they happen.
