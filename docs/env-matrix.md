# Environment matrix - AYCAS Studios Brand Assets

> Added by retrofit-apply on 2026-09-25 (SSDM Stage 1: development, preview and production; generated for the other profile; no template stack).
> Every cell the repo cannot show is TBC - Gus or the integrator fills it. Nothing here was guessed.

|              | development | preview | production |
| ------------ | ----------- | ------- | ---------- |
| Runs where | your checkout | TBC | TBC - no deploy found in the repo |
| Who deploys | nobody (local) | TBC | TBC |
| URL | TBC | TBC | TBC |
| Data | TBC | TBC | TBC |
| Secrets from | none detected (TBC) | TBC (1Password, then the host) | TBC (1Password, then the host) |

## Rules

- Each environment gets its own data and its own secrets; nothing is shared between preview and production.
- Real values live in 1Password (`secrets.env.tpl.example` shows the shape). No file in this repo holds one.
