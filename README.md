# Exchange Baqal

A black-and-gold, mobile-friendly exchange desk prototype with English, Sorani Kurdish, and Arabic UI text.

## Included
- Private-looking passcode screen (no public/customer account)
- Exchange transaction entry with amount, rate, notes, and profit in IQD
- Manual currency/cash stock list
- Searchable exchange records
- CSV export and JSON backup
- Browser-local storage; no external libraries required

## Demo access password
**`Bakal@2026`**

## Important security warning
This is a **front-end demo**, not secure financial software. GitHub Pages publishes the website files publicly. The demo password is visible in `app.js`, and data saved with browser local storage is only stored in that browser/device; it is not shared across devices or backed up automatically. A password screen in a static website does **not** protect confidential business data from someone who can inspect the source code or browser storage.

Do not enter real customer identities, account credentials, or confidential business information in this demo. Before using it for real business, add a secure backend (for example, a server with authenticated user sessions and a database), keep passwords as server-side password hashes, enforce authorization on every request, and use HTTPS. GitHub Pages alone cannot provide that backend.

## Deploy a demo on GitHub Pages
1. Create a GitHub repository named `exchange-baqal` (or any name you prefer).
2. Upload `index.html`, `style.css`, `app.js`, the `assets/` folder, and this README.
3. In the repository, open **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site.

## Local preview
Open `index.html` in a modern browser. The app does not require a build step.

## Data
Records remain in local browser storage until cleared. Use **Download backup** regularly. Clearing browser storage or changing browser/device may make records unavailable.
