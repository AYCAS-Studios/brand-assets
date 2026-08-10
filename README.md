# AYCAS Studios — Brand Assets (public)

Public, CDN-served brand assets for AYCAS Studios. Intended to be loaded over
HTTPS by email clients, sites, and third-party tools.

Served via jsDelivr, e.g.:
`https://cdn.jsdelivr.net/gh/AYCAS-Studios/brand-assets@main/email/core-circle-teal-192.png`

- `email/` — logos sized for email signatures.
- `logo-pack/svg/` — the Core mark in vector. `core-mark-{dark,light,teal}.svg`
  and `core-tile-teal.svg` are the canonical names used by the brand book. The
  `core-circle-*.svg` files are the same artwork under the earlier name, kept so
  existing references keep resolving.
- `logo-pack/png/` — raster exports of the same marks.
- `tokens/` — the token list. See below.

## Tokens

`tokens/brand-tokens.css` is the **canonical token list** for the AYCAS Studios
brand system — **version 2.1, dated 2026-08-10**. Import it; never copy the hex
values into a product, because a hex without its role is not the brand.

The approved system is light-first: white ground, `#12201D` ink type, and one
teal held in three working steps — `--teal #3E9A8F` (the brand teal: mark
ground, avatar, covers, large display), `--teal-deep #2F766D` (the working teal
on white and the print teal, 4.9:1), and `--teal-bright #45C7B3` (on ink only,
never on white). Inter carries everything; Space Grotesk is the codes-and-figures
accent. `--rust #9A3B1F` is a caution accent only, never a brand colour.

Two earlier systems are retired — recognise them, never match them: the v1.0
pine system (`#1B544E` pine, rust-as-brand, `#6FE3BC` spark, Space-Grotesk-only)
and an unapproved dark-first draft from 2026-08-10 a.m. (`#0A0B0A` / `#1d5c57`,
Zalando Sans / DM Sans / Bitcount).

## Source of truth

Source of truth for the brand system is the "AYCAS Studios — Brand Logo Pack"
Claude Design project; these are exported copies for public hosting. Where an
export here and the Design project disagree, the Design project is right and
this repo gets re-exported.
