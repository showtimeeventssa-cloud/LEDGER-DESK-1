# LedgerDesk POS — Milestone 2

A self-contained, browser-local invoicing and POS-style business app designed for GitHub Pages. The HTML, CSS, JavaScript and vector brand artwork are embedded in `index.html`.

## Deploy
1. Extract this ZIP.
2. Upload `index.html` to the root of your GitHub repository, replacing the previous version after backing it up.
3. Keep `README.md` if you want the instructions in the repository.
4. In GitHub, open **Settings → Pages** and select **Deploy from a branch**, branch `main`, folder `/(root)`.

## Included in this milestone
- Existing LedgerDesk dashboard, clients, quotes, invoices, settings, banking details, backup/restore, quote-to-invoice conversion and print-to-PDF workflow.
- Multiple tax rates and percentage discounts.
- Partial payment records, payment methods/references, balance calculations and printable receipts.
- Reusable products/services catalogue, including add/edit/delete and add-to-invoice/quote.
- Recurring invoice schedules (weekly, monthly, quarterly, yearly), editable/pausable schedules and manual invoice generation that advances the next date.
- Expanded CSV document export and payment history in Income & Reports.
- Backward-compatible defaults for older browser backups without the new arrays.

## Browser-local storage limitations
Data stays in the browser profile on the device being used. It does not synchronise between devices. Export backups regularly, especially before updating the app. Recurring schedules cannot generate invoices while the browser/app is closed; open the app and use **Generate** on the Recurring invoices page when a schedule is due. PDF output uses the browser print dialog; choose **Save as PDF**.

## Testing status
The JavaScript passes Node syntax validation and the ZIP passes archive-integrity testing. Browser-based end-to-end testing and live GitHub Pages deployment have not been completed, so test workflows with sample data and keep a backup before replacing a live copy.
