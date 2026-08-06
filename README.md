# WISP Launch Kit

A digital product: a practical playbook + templates for launching a small wireless ISP (WISP) with no investors, plus a landing page for selling it directly via PayPal with manual delivery (no third-party marketplace account required).

**Live site:** https://capfroggy.github.io/wisp-launch-kit/ (temporary mirror while GitHub Pages recovers from an outage: see `docs/STATUS.md`)

## Structure

- `index.html` — the sales landing page (static, no build step), served at the repo root so GitHub Pages can publish it directly.
- `pricing_calculator.html` — the pricing/breakeven calculator, **free**, linked directly from the landing page.
- `product/FREE_SAMPLE_chapter1.md` — free excerpt used as a lead magnet, linked from the landing page.
- `docs/STATUS.md` — running log of what's live, what's pending, and verified results (visits, sales, revenue).

**The paid content (full playbook, service agreement template, install checklist, and the bundled zip) is intentionally NOT in this public repo** — it lives only in a local `private/` folder (gitignored) and is sent by email after purchase. Earlier revisions of this repo mistakenly committed the paid content publicly; history was rewritten to remove it once caught.

## How a sale works today (manual, by design — zero payment-processing budget)

1. Buyer pays $19 via the PayPal.me link on the landing page.
2. Buyer emails their receipt to `alejandro.amezquita@alumnos.udg.mx`.
3. Whoever checks that inbox replies with the zip attached directly (see `docs/DELIVERY_EMAIL_TEMPLATE.md`) — not a public link, since the file isn't hosted publicly.

This is intentionally low-tech for v1. If sales volume justifies it, an automated delivery step (e.g. a paid Gumroad/Payhip listing, or a simple serverless email-on-payment webhook) is the natural next iteration.

## License

Product content is © the author. Not for redistribution. See `LICENSE`.
