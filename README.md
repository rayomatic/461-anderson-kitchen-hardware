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

Kitchen + sitting cabinet: 36 pieces, all Emtek **Timeless Classics
Collection** in Satin Brass (US4) — **Paxton** round knobs (86642-US4)
for upper doors, **Westridge** handle pulls (86633 / 86635 / 86637 /
86639-US4) for drawers and base-cabinet doors. Pre-tax total $670.53
from Cape Cod Brass with the `WKD` coupon. Plus laundry ($81.92, Top
Knobs Hopewell Bar Pull 15" M433A-BSN × 4) and office ($66.08, Top
Knobs Hopewell Bar Pull 8-13/16" M432-ORB × 4). Combined ~$888 all-in.

## Local preview

It's a single static file. Open `index.html` directly, or:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Pushed to GitHub and deployed on Vercel as a static site. No build step.
