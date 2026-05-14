# clothing-ads landing page

Single-scroll landing page that converts cold visitors into Cal.com fit-call bookings for AireyAI's clothing-brand video ad service (£750 Launch Pack, 5-day turnaround).

- **Spec:** [`/Users/kyleairey/Websites/docs/superpowers/specs/2026-05-14-clothing-ads-landing-page-design.md`](/Users/kyleairey/Websites/docs/superpowers/specs/2026-05-14-clothing-ads-landing-page-design.md)
- **Plan:** [`/Users/kyleairey/Websites/docs/superpowers/plans/2026-05-14-clothing-ads-landing-page.md`](/Users/kyleairey/Websites/docs/superpowers/plans/2026-05-14-clothing-ads-landing-page.md)
- **Business inbox:** `apcapital.ai@gmail.com`

## Local dev

```bash
node serve.mjs                                              # → http://localhost:3000
node screenshot.mjs http://localhost:3000 hero              # → temporary screenshots/screenshot-N-hero.png
```

## Deploy

GitHub Pages under the AireyAI org. Cloudflare CNAME `clothing-ads` → AireyAI Pages target. See plan Task 10 for the full ship checklist.

## Subsystem A integration

The sample reel embedded on this page is produced by the clothing_ad_engine pipeline at `~/jarvis/agents/clothing_ad_engine/`. Running this page's Task 6 doubles as subsystem A's first end-to-end validation with real Higgsfield credits.
