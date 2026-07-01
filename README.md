# Phamax Marketing & BD Dashboard

A static, single-file dashboard reporting monthly marketing and business
development activity across BU1 (Business Intelligence), BU2 (Business
Consulting), BU3 (Forecasting), and Corporate.

## Structure
This is a zero-build static site — `index.html` contains everything
(HTML, CSS, and JS inline). No dependencies, no build step.

## Local preview
Open `index.html` directly in a browser, or serve it locally:

```bash
npx serve .
```

## Deploy
This repo deploys to Vercel with zero configuration. Any push to `main`
triggers a new deployment automatically once the repo is connected.

## Updating the report
Each month, edit the KPI values, coverage matrix, email stats, and
website traffic numbers directly in `index.html`, commit, and push —
Vercel redeploys automatically.
