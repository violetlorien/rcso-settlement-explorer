# RCSO Settlement Explorer

A visual, web-based explorer of Riverside County Sheriff's Department settlements, budget, consent decree compliance, and timeline of events.

## What's Inside

- **Cases** — Searchable database of 129+ settlement and injury claims with CPRA-verified amounts, categories, and source links
- **Timeline** — 127 events from 1986-2026: settlements, in-custody deaths, consent decree milestones, staffing changes, Board of Supervisors changes, Civil Grand Jury reports, and oversight actions
- **Budget Explorer** — Sheriff's Department budget breakdown, jail healthcare (RUHS), AB 109 realignment, and per-resident spending comparisons
- **Compliance Tracker** — All 28 consent decree requirements from Gray v. Riverside with current status and Grand Jury findings

## Live Site

Deployed via GitHub Pages at: `https://violetlorien.github.io/rcso-settlement-explorer`

## Tech Stack

- React + TypeScript + Vite
- Tailwind CSS + shadcn/ui
- Recharts for data visualization
- Lucide React icons

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

Output goes to `dist/`.

## Auto-Deploy

This repo uses GitHub Actions to automatically build and deploy to GitHub Pages on every push to `main`. See `.github/workflows/deploy.yml`.

## Data Sources

- Riverside County CPRA responses (settlement and injury claim data)
- Riverside County Civil Grand Jury reports (1997-2026)
- Court filings (Gray v. County of Riverside, 5:13-cv-00444-VAP-OP)
- County budgets (FY 2022/23 through FY 2025/26 adopted)
- News articles and public records

## License

Data is compiled from public records. Code is provided as-is for public accountability purposes.
