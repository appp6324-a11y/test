<!-- UI ONLY — no backend -->
# LabourMandi — UI-only demo (index.html)

This is a static UI-only scaffold for **Step 1 — Repo scaffold + global layout & config** converted into an `index.html` build you can open directly in the browser.

## What this contains
- Global layout (TopNav, Sidebar, Main content, Right column)
- Dashboard cards with skeleton loaders & empty states
- Mobile bottom nav (responsive)
- Floating Voice AI button with permission modal mock
- PWA install prompt mock
- CSS tokens (primary/secondary/gray-bg) in `styles/tokens.css`
- Accessibility attributes and data-testid for QA:
  - `data-testid="topnav"`
  - `data-testid="sidebar"`
  - `data-testid="mobile-nav"`
  - `data-testid="voice-ai-btn"`
  - `data-testid="pwa-prompt"`
  - `data-testid="analytics-chart"`
  - Dashboard cards: `data-testid="card-labour-hiring"`, `card-contractor-bidding`, `card-equipment-rental`, etc.

## How to run
1. Copy the files into a folder (keep the structure).
2. Open `index.html` in your browser (double-click or `open`).
3. No build tools or servers required.

## Commands (for parity; not required for static demo)
- `npm i` (if you later add a package.json)
- `npm run dev`
- `npm run build`

## Notes
- **UI ONLY — no backend**. Nothing in this demo calls external services.
- This is a single-file / static convert of Step 1 (global layout). Use this as a demo or quick prototype.
