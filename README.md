# Investment Portfolio Tracker

A single-file, offline-first HTML web app for tracking private lending
investments across multiple portfolios (Wadiaa, Tamluk, Ufuq Fund, etc.).

## Features
- Multi-portfolio deal and payment tracking
- Free Capital Pool: Equity / Overdraft / Loan financing, all fungible
- Three commission models (upfront cash, % of invested amount, % of profit)
- XIRR-based return calculations (blended and true-equity)
- Analytics: concentration risk, cash flow forecast, collections/aging
- CSV export, maturity reminders (.ics), JSON backup/restore
- Installable as a PWA (Add to Home Screen), works fully offline

## Usage
Open `index.html` in any modern browser (mobile or desktop). No build step,
no server, no dependencies beyond a CDN-loaded Chart.js and Google Font.
All data is stored locally in the browser (`localStorage`). Use the
Setup tab to export/import JSON backups.

Default app password: `1234Abc` (change it from the Setup tab after first use).
