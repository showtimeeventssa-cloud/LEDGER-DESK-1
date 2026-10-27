# LedgerDesk POS — GitHub Pages

## Deploy
1. Extract this ZIP.
2. Open your GitHub repository.
3. Upload the contents of the `LedgerDesk_Milestone1` folder (`index.html` and `README.md`) to the repository root, replacing the previous `index.html`.
4. Commit the changes and allow GitHub Pages to redeploy.

## Fix in this version
The “Add selected” control now has a click handler inside the document modal. It reads the selected saved product/service, adds it as a new line item with its saved description and price, recalculates totals, and displays a confirmation. Other app functionality and the existing visual branding are retained.

## Data
This is a static browser app. Existing data remains in the browser storage on the device/browser where it was entered. Back up data before replacing app files.
