# Fleetwood Drive — Marketing Site

Static Next.js marketing site for 6705 Fleetwood Drive, Nashville TN.

## Setup

```bash
npm install
npm run dev       # development at localhost:3000
npm run build     # creates /out folder for static deployment
```

## Deployment

After `npm run build`, the `/out` folder contains a fully static site ready to deploy to:
- **Vercel**: `vercel deploy` (recommended — connects to GitHub)
- **Netlify**: drag the `/out` folder into Netlify drop
- **Any static host**: upload contents of `/out`

## Files

- `app/page.js` — main page component
- `app/globals.css` — global styles + Google Fonts import
- `public/fleetwood-plans.pdf` — architectural schematic (embedded + downloadable)

## Notes
- PDF is embedded inline with a download fallback
- Replace `public/fleetwood-plans.pdf` to update the plans
- Contact info in the footer section of `app/page.js` should be updated with the realtor's details
