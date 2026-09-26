# Bank Branch Audit – Documentation Tracker

A single-file, browser-based checklist tool for statutory bank branch auditors to track loan-wise documentation compliance (Statutory Audit).

![App Screenshot](./image.png)

> Upload your screenshot to the repository root with the exact filename **`image.png`** (same folder as this README) — GitHub will render it above automatically once pushed.

---

## Overview

This tool helps bank branch statutory auditors quickly verify, track, and export the documentation status of loan accounts across **15 loan categories** (Cash Credit, Overdraft, Term Loan, Housing Loan, Vehicle Loan, Personal Loan, Jewel Loan, SHG Loan, KCC, Education Loan, MSME/SME, Loan Against Property, Bills Discounting, Gold Loan, and Loan Against FD).

For each loan type, a curated checklist of mandatory and conditional documents (sanction letter, KYC, CERSAI, insurance, stock statements, valuation reports, etc.) is presented with a three-way status toggle — **Verified**, **Pending**, or **Not Applicable** — along with a free-text remarks field for audit notes.

It runs entirely in the browser with no backend, database, or build step. Just open the HTML file.

## Features

- **15 loan-type checklists** covering 30+ standard bank audit documents, mapped per RBI/ICAI-aligned audit practice
- **Left-side navigation** to switch between loan types, with a live verified-count badge per type
- **Three-way status tracking** — Verified / Pending / N/A — per document
- **Mandatory-document progress bar** per loan type
- **Global dashboard** — total, verified, pending, and N/A document counts across all loan types
- **Remarks field** on every document for audit references and notes
- **Bulk actions** — Mark All Verified / Pending / N/A, and Reset per loan type
- **Print / PDF export** — a clean print stylesheet hides interactive controls for a paper-ready audit annexure
- **No installation, no dependencies, no server** — a single self-contained HTML file

## Usage

1. Download `Bank_Audit_Doc_Tracker.html`
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari)
3. Select a loan type from the left navigation
4. Mark each document's status and add remarks as you verify
5. Use **Print / Export** to generate a paper or PDF copy for audit working papers

> **Note:** Data is held in-memory for the current browser session only and is not saved automatically. Export/print before closing the tab if you need a record.

## Tech Stack

- Plain HTML, CSS, and vanilla JavaScript — no frameworks, no build tools
- Google Fonts: [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) (headings) and [Inter](https://fonts.google.com/specimen/Inter) (body/UI)

## Disclaimer

This checklist is **illustrative and not exhaustive**. Documentation requirements vary by credit facility, bank-specific policy, RBI Master Directions, and branch-level instructions. Always refer to the bank's Delegation of Power (DOP) and closing circular before finalising an audit checklist. This tool is for **internal use only** and does not constitute an audit opinion, certificate, or legal document. All conclusions remain subject to the auditor's independent professional judgment.

## Author

**Haresh Kumar Hemani**
🌐 [www.taxonline24.in](https://www.taxonline24.in)
✉️ [contact@taxonline24.in](mailto:contact@taxonline24.in)

## License

MIT — free to use, modify, and distribute with attribution.
