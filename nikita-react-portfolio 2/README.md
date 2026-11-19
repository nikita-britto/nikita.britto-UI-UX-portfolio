# Nikita Britto — React portfolio

A first working React/Vite portfolio draft based on the supplied Figma screenshots and exported project assets.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. For production: `npm run build`; deploy the generated `dist` folder on Vercel or Netlify.

## Included

- Homepage with featured project cards, about, approach, and contact
- Separate navigable case studies for MedTracker, Kynd Bytes, and CASAI
- Responsive layouts, scroll navigation, original exported app screens and botanical illustration

## Before publishing

- The About portrait is a **placeholder** (no source portrait was included in the export).
- Research, usability testing, and outcome claims are **not invented**. Replace generic research questions with your verified findings.
- Check contact email and LinkedIn URL, and add your actual résumé link.
- The Figma page design was reconstructed from screenshots rather than Figma layout metadata, so exact pixel matching requires further review.
- Project-cover images are assembled from original exported app screens; replace them with the preferred hero artwork when available.


## Editorial artwork update
The landing-page botanical illustration and the three project-cover images are now included under `public/assets/`. The existing React routing and actual exported app screens are preserved. The illustrated covers are raster artwork based on the user's chosen design direction; they are not independently editable Figma layers.

To update the existing live URL, replace the files in the GitHub repository connected to Vercel and commit. Vercel should redeploy automatically.
