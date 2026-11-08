# GHAR GRISTHI Records Dashboard

A standalone, responsive inventory and sales dashboard for static hosting (including GitHub Pages). No build tools, React runtime, or server are required.

## Run locally

Open `index.html` in a modern browser. If your browser restricts local file storage, serve the folder with a local static server, for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish on GitHub Pages

1. Create a public GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Open the published URL shown in the Pages section.

## Features

- Add, edit, search, restock and delete products.
- Record sales with stock validation and automatic stock deduction.
- Today's sales and item totals, product count and low-stock count.
- Sales history.
- Export product and sales CSV files.
- Download and restore a JSON backup.
- Automatic browser-local saving.

## Data and privacy

Records are stored in the browser's `localStorage` on the current device/browser. GitHub Pages hosts the website files only; it does not synchronize records between users or devices. Clearing browser storage can remove records, so download backups regularly. For shared multi-device use, add a secure backend/database and authentication.
