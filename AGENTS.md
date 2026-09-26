# AYCAS Studios Brand Assets - AGENTS.md (repo root)

Rules every coding tool follows in this repo (Claude Code, Codex, Cursor, CodeRabbit). Added by retrofit-apply on 2026-09-25 (house Stage 1 agent rules).
It describes this repo as it is today (other profile). Add a rule here the moment it is repeated in chat.

# Read first

1. `PLAN.md` - the spec and phased plan; keep it current when a decision changes.
2. `CLAUDE.md` - the session entry for Claude Code.
3. `docs/done-contract.md` and `docs/escalation.md` - what "done" means and what only Gus decides.

# Commands

No build, install or test commands were detected (no package.json, no Python project file, no other toolchain file). None are invented here; add them when the repo has them.

# Platform

- **Deploy**: none found in the repo (a host connected in its own dashboard, such as Cloudflare Pages or Vercel, would not show here). Publishing anything is Gus-gated.

# Non-negotiables

- Secrets never land in files, chat, logs or screenshots. Never read, print or edit a real `.env`, `.env.*`, `.dev.vars` or `secrets.env`; only the `*.example` shapes are committed. 1Password is the source of truth.
- Never deploy and never touch remote resources (`--remote`, deploy, production migrations, secrets): those are Gus-gated (see `docs/escalation.md`).
- Never push to the default branch, never force-push. Everything lands through a PR with CI green.
- No PII in logs, analytics or URLs. Synthetic data only in tests, seeds and screenshots.
- No new dependencies without flagging to Gus first.
- Anything dropped, deferred or stubbed is written down, never a silent cap.
