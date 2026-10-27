# LedgerDesk POS — Milestone 2 hotfix

Static, single-file invoicing app for GitHub Pages. Upload `index.html` to the repository root and select **Settings → Pages → Deploy from a branch → main → /(root)**.

## Fix included
- Corrected modal footer event handling so **Save item** in Products & Services invokes `saveProduct()`.
- Corrected recurring schedule footer handling so **Save schedule** invokes `saveRecurring()`.
- Existing client and document save handlers remain in place.

## Storage note
Records are stored in this browser. Export a JSON backup before replacing an existing deployed file. This static build does not synchronize data between devices.

## Testing
Inline JavaScript syntax checked with Node.js; ZIP integrity checked. This is not a substitute for full browser end-to-end testing.
