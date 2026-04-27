# 461 Anderson — Kitchen Hardware Plan

Final, locked hardware specification for the 461 Anderson kitchen renovation.
Single-page static site published as a shareable reference for the installer
and as the source-of-truth before placing the order.

## What's here

- `index.html` — the spec page: order summary, embedded SVG elevations for Wall A,
  Wall B, the island, and the sitting cabinet, and the per-cabinet hardware
  assignment.
- `vercel.json` — minimal static-site config (clean URLs + a couple of security
  headers).
- `CONTEXT.md` — full design notes and rationale.

## The plan in one line

36 pieces, all Emtek Satin Brass (US4) — **Paxton** round knobs (model
86642-US4) for upper doors and the sitting cabinet, **Trail** bar pulls
(86161 / 86272 / 86165 / 86166-US4) for everything else. Pre-tax total
$769.63 from Cape Cod Brass with the `WKD` coupon.

## Local preview

It's a single static file. Open `index.html` directly, or:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Pushed to GitHub and deployed on Vercel as a static site. No build step.
