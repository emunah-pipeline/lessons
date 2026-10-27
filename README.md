# lessons

The lesson pipeline of Emunah Shlemah / Shiur Hebraico, on GitHub (moved here from
`emunah-caption-harvest` on 2026-10-27 for its own pool of runners).

`.github/workflows/lessons.yml`: find the new lessons (the site's teachers, or `set=kabbalah`) →
WhisperX + ivrit.ai transcription → Claude curation → quote colours, book export, Shiur Hebraico
catalog, committed to the site repos. Deploys stay manual.

Secrets: `YT_COOKIES`, `REPOS_TOKEN`, `CLAUDE_CODE_OAUTH_TOKEN`, `SUPABASE_URL`,
`SUPABASE_SERVICE_KEY`, `SUPABASE_ANON_KEY`.
