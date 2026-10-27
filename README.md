# LedgerDesk POS — Milestone 1

Static, GitHub Pages-compatible invoicing app. No build step or server is required.

## Deploy
1. Create/open your GitHub repository.
2. Upload `index.html` to the repository root.
3. In Settings → Pages, select Deploy from a branch, branch `main`, folder `/(root)`.
4. Save and open the published Pages URL.

## Included in this milestone
- Existing LedgerDesk dashboard, client records, quotes, invoices, business profile, currency, logo, banking details, local backup/restore, CSV export and print-to-PDF workflow retained.
- Invoice/quote discounts by percentage.
- Multiple tax rates entered as comma-separated percentages; each is applied to the discounted subtotal.
- Partial payment recording with date, method and reference; remaining balance is calculated from recorded payments.
- Printable payment receipts.
- Legacy documents using the original single `taxRate` field remain supported.

## Data and limitations
Records are stored in this browser's localStorage. They do not sync to other devices. Export backups regularly. Browser print dialog is used for PDF output. This milestone does not yet include recurring invoice scheduling or a reusable product/service catalogue; those are planned for subsequent milestones. It is not a tax-compliance/accounting package.

## Validation performed
- JavaScript syntax checked with Node.js.
- ZIP archive integrity checked after packaging.
- Static source checks performed for discount, multiple tax, payment and receipt paths.
- A full browser end-to-end test and live GitHub Pages deployment have not been performed.
