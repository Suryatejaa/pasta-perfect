# pasta-perfect

A tiny, static "Love Proposal" landing page (single `index.html`).

## Deploy to Vercel — quick setup ✅

This project is a static site and is ready for Vercel. Two easy ways to deploy:

1. CLI (one-off or manual)
   - Install the Vercel CLI: `npm i -g vercel`
   - Login: `vercel login`
   - Deploy: `vercel --prod` (or `vercel` for a preview)

2. Git integration (recommended)
   - Push your repo to GitHub/GitLab/Bitbucket
   - Import the repository at https://vercel.com/new
   - Vercel will detect a static site; no build command required.

Files added in this repo:
- `vercel.json` — Vercel config (serves `index.html` as a static site)
- `.vercelignore` — files to skip during upload
- `package.json` — convenience scripts: `npm run dev` and `npm run deploy`

Local dev:
- `npm run dev` (requires the Vercel CLI)

Notes:
- No additional env vars are required for this site.
- For automatic deploys from pushes, connect the repo in the Vercel dashboard.
