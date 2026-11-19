# MKT Visibility SearchPilot

Standalone website discovery and indexing management tool by MKT Visibility.

## Current build
- Responsive forest-themed dashboard in `index.html`
- Add/remove website records (browser localStorage only)
- Search engine compatibility directory
- Open a site's conventional sitemap URL
- Export saved website inventory to CSV

**No live submission, indexing verification, AI audit, authentication, or cloud persistence is implemented yet.** Do not treat the dashboard as evidence of submission.

## Publish with GitHub Pages
Repository Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save.
Once GitHub Pages is active, the usual project URL is:
https://mktvisibility.github.io/mkt-visibility-searchpilot/

## Next development milestones
1. Supabase Auth and row-level-secured website/report storage.
2. Server-side sitemap discovery and crawl diagnostics with SSRF protection and crawl limits.
3. Verified IndexNow key setup and server-side notification logs.
4. Google Search Console OAuth, sitemap submission, and inspection reporting.
5. AI-assisted explanations, scheduled monitoring, and downloadable reports.

Keep API keys and OAuth secrets in server-side environment variables, never in GitHub Pages source.
