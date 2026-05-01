# oi-internal-app-pages

Static HTML pages required by Intuit's QuickBooks Online developer-app
production-credential review process for the **OI Internal QuickBooks Connector** —
an internal-only OAuth client used by Overhead Intelligence Inc. to read and
reconcile its own accounting data.

These pages exist solely to satisfy the public-URL requirements of Intuit's app
review (EULA URL, Privacy Policy URL, Launch URL, Connect URL, Disconnect URL).
The actual connector code is private and lives in the
`OI - Accounting/Tools/oi-qbo-tools/` directory of Overhead Intelligence's internal
shared storage.

## Pages

| Page | Purpose |
|---|---|
| `index.html` | Landing page (Launch URL) |
| `eula.html` | End-User License Agreement |
| `privacy.html` | Privacy Policy |
| `connect.html` | Connect endpoint placeholder |
| `disconnect.html` | Disconnect endpoint placeholder |

## Hosting

Served via GitHub Pages from the `main` branch root.

URLs after Pages is enabled:

- `https://rwoneill.github.io/oi-internal-app-pages/`
- `https://rwoneill.github.io/oi-internal-app-pages/eula.html`
- `https://rwoneill.github.io/oi-internal-app-pages/privacy.html`
- `https://rwoneill.github.io/oi-internal-app-pages/connect.html`
- `https://rwoneill.github.io/oi-internal-app-pages/disconnect.html`

## Why this repo is public

GitHub Pages requires a public repository to serve from a free account. The pages
themselves contain no sensitive information — they are deliberately public-facing
EULA / privacy / OAuth-callback placeholders. No application code, no credentials,
and no financial data are stored in this repository.

## License

The HTML in this repository is provided for the operation of Overhead Intelligence
Inc.'s internal application. © 2026 Overhead Intelligence Inc.
