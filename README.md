# PNE Flags – Website

Static site for **PNE Flags by PNE Online**. Primary deploy via **cPanel**; repo used for versioning, QA, and issue tracking.

## Deploy (cPanel)
1. **Code → Download ZIP** from this repo.
2. In **cPanel → File Manager**, upload ZIP to the site root (e.g., `public_html/pneflags.net/`).
3. **Extract** and **overwrite**.
4. Clear caches and hard-refresh the browser.

## Optional preview (GitHub Pages)
- Settings → Pages → Source: **Deploy from a branch** → Branch: `main` → Folder: `/ (root)`.

## Webby-Readiness
- Backlog and QA checklists live in the **Project: Webby Readiness**.
- Tickets follow the templates in `.github/ISSUE_TEMPLATE/` (Feature and A11y Bug).

## Tech/Perf
- Images: use WebP/AVIF with `srcset`/`sizes`; keep hero ≤ 200KB.
- CSS/JS: inline critical CSS ≤ 14KB, defer non-critical JS.
- Accessibility: WCAG 2.2 AA across templates; keyboard-only journeys pass.

## License
Content and images © their respective owners. Code snippets MIT unless stated otherwise.
