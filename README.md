# Drift — scent-first concept

A concept redesign of the Drift mobile experience, built for a design exercise.
Not affiliated with Drift or Scentbird.

Live: https://ricardogejao.github.io/drift

Full interactive prototype: homepage → 6-question scent discovery → result → cart drawer → representative checkout → back to homepage.

## Files

- `index.html` — the whole prototype (markup + logic)
- `support.js` — runtime the page loads; must sit next to `index.html`
- `assets/fonts/` — Meta Serif Pro and Brandon Grotesque (official Drift typefaces)
- `assets/*` — official Drift imagery and wordmarks, compressed to WebP

## Notes

- Progress is stored in the browser (`localStorage`, key `drift-prototype-v1`), so a returning visitor resumes where they stopped.
- Only `$8.45` (Wood Car Freshener) is a verified price; stone and metal formats show `—` on purpose.
- Subscription cadence shows "Every month"; no savings, shipping or return promises are stated.
- The checkout screen is representative only — it does not connect to Shopify.
