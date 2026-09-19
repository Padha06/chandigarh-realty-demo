# Chandigarh Realty — Interactive Demo

Premium single-file real estate demo for a Chandigarh/Tricity firm: verified listings,
dossier modals, Pannellum 360° room tours, Three.js 3D home (GLB + procedural dollhouse),
EMI calculator, saved/compare pages, locality quiz, and WhatsApp-native lead capture.

## Run locally

Any static server works, e.g.:

```bash
npx serve .
```

Then open the printed URL.

## Deploy

Static — no build step. Import this repo on Vercel and deploy with default settings.

## Notes

- All firm details, listings, prices, reviews, and stats are **placeholder demo content**.
- Sample 3D model: `models/home1.glb` (via kavyasenthamarai/3d-property-f).
- Photography via Unsplash CDN; libraries via CDN (Tailwind, Three.js, Pannellum).
