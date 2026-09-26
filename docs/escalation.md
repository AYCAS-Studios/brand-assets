# Escalation-contract - AYCAS Studios Brand Assets

> Added by retrofit-apply on 2026-09-25 (house Stage 1 shape, generated for the other profile; no template stack).
> Work in this repo proceeds on its own EXCEPT for these, which stop and surface to Gus as
> `needs_you` on the AYCAS OS mission; the loop then continues other work. These are the house
> rules: add this repo's own lines when PLAN.md is locked.

- **Anything outward-facing or irreversible**: deploys and publishes, pushes to the default branch, deleting data, public posts, external sends (drafts, not sends)
- **Secrets and credentials**: creating, reading, rotating or deleting any secret; 1Password items; a host's secret settings
- **Money**: payments, pricing, anything that posts beyond a draft
- **New dependencies or tools**: flagged to Gus before they are added
- **Relaxing a guard**: agent permission denies (`.claude/settings.json`), CI checks, lint or test rules
- **Real personal data**: loading real people's data; data-processing agreements
- **Org-level settings**: GitHub repository settings, branch protection, DNS, Cloudflare or Vercel account settings
- **A genuine ambiguity** PLAN.md cannot resolve
- (else) proceed, and report at wave boundaries

## How to escalate

`PATCH /api/missions/:id` on the AYCAS OS with `status: needs_you` and a one-line `detail`
that says what decision is needed and what the default would be. Keep working on anything
that does not depend on the answer.
