LedgerDesk POS - Firebase-connected build

Publish steps:
1. Open your GitHub repository for LedgerDesk POS.
2. Open the existing index.html file and choose Edit (pencil) or upload this package's index.html to the repository root, replacing the old index.html.
3. Commit the change to the branch used by GitHub Pages.
4. Wait for GitHub Pages to finish deploying, then open the published site and refresh it.
5. Sign in using one of the Firebase Authentication accounts whose UID is listed in the Firestore rules.

This version uses Firebase Authentication and Firestore document ledgerdesk/shared to share the entire LedgerDesk state. The existing Firestore rules must permit the signed-in user's UID. Keep the rules restrictive; do not make the database publicly readable or writable.

Important: the first authorised user to connect when no shared document exists seeds the shared workspace from that browser's current local data. If the shared document already exists, it is loaded into the browser and replaces the local working state. Export a backup before first deployment if the existing browser contains important data.
