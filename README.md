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
- The hero photo switches to the home diffuser when "My home" is selected in Q1.
- Only `$8.45` (Wood Car Freshener starter kit) is a verified price; stone and metal formats show `—` on purpose. Refill prices in the Material Edit are separate from the starter kit.
- Cart claims to confirm before launch: "Shipping — Free", "Change your scent any month", "Safe around kids and pets".
- The checkout screen is representative only — it does not connect to Shopify.
