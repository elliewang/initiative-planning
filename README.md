# InitiativeOS — Wenting Wang

A responsive, free, static initiative planning and portfolio management application for GitHub Pages.

## Features
- Overview with metrics, execution health and portfolio progress
- Initiative create, edit, delete, search and filter (owner, priority, status, dates, budget, progress)
- Six-month initiative roadmap
- Action-item checklist assigned to initiatives
- Portfolio analytics, planned budgets and completion rates
- On-device, rules-based planning chatbot (no API key, no paid AI service)
- JSON backup / restore and CSV export
- Browser localStorage persistence, mobile responsive layout

## Deploy on GitHub Pages
1. Create a **public** GitHub repository (e.g. `initiativeos`).
2. Upload `index.html`, `styles.css`, `app.js`, `.nojekyll`, and `README.md` to the repository root, or push them with Git.
3. Open **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, select **main** and **/(root)**, then save.
5. Visit `https://YOUR_USERNAME.github.io/initiativeos/` after deployment.

No build step, package manager, database or billing is required. The `.nojekyll` file bypasses unnecessary Jekyll processing.

## Data and limitations
Data is stored **only in the current browser on the current device** using `localStorage`. It is not shared across devices or users. Export JSON backups regularly; clearing browser site data deletes the locally saved portfolio. Starter records are illustrative demo data, not real organizational figures. The chatbot is **not connected to a live LLM** and answers supported questions by analyzing local records. This site is not a secure multiuser enterprise system. Do not store confidential personal or financial information in it.

To reset to demonstration data, clear this website's browser local storage and reload. You can also replace sample entries via the UI.
