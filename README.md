# NIKHIL CHARY SRIRAMOJU — Portfolio
BTech CSE (Final Year) · Systems & AI Engineer

- GitHub: [Nikhil-creat](https://github.com/Nikhil-creat)
- LinkedIn: [nikhil-chary-sriramoju](https://in.linkedin.com/in/nikhil-chary-sriramoju-95041b38a)
- Email: sriramojunikhil66@gmail.com
- Instagram: [@nikhil__sriramoju](https://www.instagram.com/nikhil__sriramoju)
- Facebook: [Profile](https://www.facebook.com/profile.php?id=100079201124141)

Live site: https://nikhil-creat.github.io/portfolio/

Single-file static site (`index.html`, HTML/CSS/JS only — no build step, no dependencies to install).

## What's inside
- **Agentic AI lab** — the perceive → plan → act → observe → reflect loop, plus an in-browser "ask my portfolio agent" (guardrail scan, planner, BM25 retrieval over portfolio facts, confidence check, grounded answer). No LLM call; nothing leaves the browser.
- **Core stack & AI skills** — agentic AI, LLM/RAG, AI safety, ML, MLOps, backend, frontend (dashed chips = still exploring).
- **Projects** — AgentShield-X, Omni-Cloud Sentinel, NeuroScan AI, DistWorkspace, TrustGuard AI, ChurnScope, AI PDF Chatbot, CircleUp, Codelint (filterable, with data-flow drawers).
- **Live GitHub feed** — public repos, followers and recently pushed repos from the GitHub API (graceful fallback offline).
- **Credential log**, experience & education, "now" section, contact card (copy email / compose mail).
- **Résumé (PDF)** — built from the same data and printed via the browser ("Save as PDF").
- **Terminal** (⌘/Ctrl+K) — `help`, `ask <question>`, `agents`, `certs`, `github`, `resume --pdf`, `theme`, history with ↑/↓.
- Light/dark theme, scroll progress bar, active-section nav, mobile section bar, keyboard/ARIA accessibility, reduced-motion support, SEO meta + JSON-LD, no-JS fallback.

## Editing content
All content lives at the top of the `<script>`: the `projects` and `skills` arrays, and the `KB` array (facts the agent can answer from). Edit those and the page, résumé and agent all stay in sync.

## Deploy on GitHub Pages
1. Create a new GitHub repo (public).
2. Upload `index.html` (and this README, optional) to the repo root.
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder: `/ (root)` → Save.
4. Wait ~1 minute, refresh the Pages settings tab for your live URL.

## Local preview
Just open `index.html` in any browser — no server required.
