# Invoice Generator

A single-file invoice generator for freelancers and small businesses. No installation, no build tools, no server required.

## Usage

**Option 1 — Open directly in a browser**

```
open invoice-generator.html
```

**Option 2 — GitHub Pages**

Push this repo to GitHub, enable Pages (Settings → Pages → Deploy from main branch root), and visit `https://<username>.github.io/<repo>/invoice-generator.html`.

## Features

- Fully editable inline invoice — click any field to edit in place
- Line items with live Qty × Price calculation
- VAT toggle (20%) with VAT number field
- Currency selector (£, $, €, CA$, A$, ¥, CHF)
- Download as a clean text-based PDF (jsPDF)
- New Invoice button auto-increments invoice number
- All field values saved to `localStorage` per invoice number — reload safely
- **Invoice Tracker** — a running table of all invoices with paid status, expenses, and tax columns
- Drop PDFs onto the tracker to auto-parse and import invoice data (PDF.js)
- Tracker totals row auto-calculates Amount, Expenses, and Tax columns
- Fully responsive and mobile-friendly

## Libraries (loaded from CDN, no install needed)

- [jsPDF](https://github.com/parallax/jsPDF) — PDF generation
- [PDF.js](https://mozilla.github.io/pdf.js/) — PDF text extraction for import
