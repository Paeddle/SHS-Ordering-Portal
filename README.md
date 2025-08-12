# Order Data Portal (GitHub Pages)

This repository serves a static portal that reads `data.csv` and renders a searchable, filterable, sortable, paginated table.

## Update Data
- Replace `data.csv` in the repository root (same folder as `index.html`), commit.
- Reload the live site; changes appear immediately (cache-busted automatically).

## Enable GitHub Pages
- Repo **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` (root). Save.
- Your site will be available at `https://<username>.github.io/<repo>/`.

## CSV Requirements
- The **first row must be column headers** (e.g., `Item Name,Part Number,Quantity,URL`).
- Any additional columns are supported and will appear automatically.
- URLs will be auto-linked.

## Optional: Pull CSV from Google Sheets
- Publish your sheet to the web as CSV.
- Edit `index.html` and replace `fetch('data.csv?...')` with your public CSV URL.

