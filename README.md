# Madrasa Darul Falah — Accounts Prototype

Starter project for the management app of Madrasa Darul Falah, Gondghar.

## Included in this prototype
- Income and expense entry form
- Totals for income, expenses, and balance
- Search recent entries
- Export transactions to CSV
- English/Urdu interface toggle
- IndexedDB local storage
- PWA manifest and service-worker app-shell caching

## Important limitations
This is a prototype for testing, not a production accounting system. Records remain on the device and are **not synchronized** with another phone or computer. There is no login, access control, cloud backup, audit trail, or multi-user support yet. Do not enter sensitive or official financial data until those safeguards are implemented.

## Add to your GitHub repository
1. Open https://github.com/naimw7/madrasa-darul-falah-gondghar
2. Select **Add file → Upload files**.
3. Extract this ZIP on your device/computer first.
4. Upload `index.html`, `manifest.webmanifest`, `service-worker.js`, and `README.md` (upload the files, not the ZIP).
5. Commit the files to the `main` branch.
6. In the repository, open **Settings → Pages**. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
7. Wait for the Pages deployment to finish. Open the published URL and test using sample entries only.

## Next development stage
Add secure authentication, a hosted API/database, server-side validation, an idempotent sync queue, conflict handling, encrypted transport, role permissions, backups, and an audit log. Test offline/online synchronization across two devices before using real records.
