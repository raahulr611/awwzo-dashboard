# Awwzo Business Dashboard

Live analytics dashboard for Awwzo pet care business. Fetches data directly from Google Sheets and computes all metrics client-side.

## Features
- **Overview & Revenue** — ARR, monthly revenue by service, ARPU trends, customer acquisition
- **Customers** — Lifecycle segmentation, RFM analysis, top spenders
- **Retention** — Monthly cohort retention, repeat curves, booking depth
- **Subscriptions** — Subscriber metrics, plan mix, usage distribution
- Date range filtering with quick presets (All Time, Last 6M)
- Live refresh from Google Sheets

## Deploy to Vercel

### Option 1: GitHub → Vercel (recommended)
1. Push this repo to GitHub
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import your GitHub repo
4. Click Deploy — done!

Every push to `main` will auto-deploy.

### Option 2: Vercel CLI
```bash
npm i -g vercel
vercel
```

## Data Source
Connects to published Google Sheets CSV feeds. The spreadsheet must be published via **File → Share → Publish to web → CSV**.

## Tech Stack
- React 18 (CDN)
- Recharts (CDN)
- PapaParse (CDN)
- Babel standalone (CDN)
- Zero build step — single HTML file
