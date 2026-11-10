# Fima

Fima is a lightweight personal expense tracker designed to stay private, fast, and easy to use. It runs as a single offline web app, so you can track spending without creating an account or depending on a backend service.

## Overview

This project is a self-contained financial management app focused on personal budgeting and monthly spending review. It lets you:

- add, edit, and delete expenses
- view total spending by month or across all time
- categorize expenses and compare category totals
- search and filter the expense list
- customize categories, currency labels, and theme preferences
- export/import backup data for safekeeping

The app stores data in the browser using local storage, making it suitable for a personal budgeting workflow while keeping the experience simple and offline-friendly.

## Features

- Overview dashboard with total spending and category breakdown
- Monthly navigation with All time view
- Search across details and category names
- Category-based filtering
- Custom category management
- Currency selection for labels (MAD, EUR, USD, GBP, CAD, AED)
- Light/dark theme support
- Local backup export and restore
- No server or installation required for basic use

## Run the app

Because the app is a single HTML file, you can run it in any modern browser.

### Option 1: Open directly

Open `index.html` in a browser.

### Option 2: Serve locally

From the project folder, you can also run a local static server:

```bash
cd /workspaces/fima
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Project structure

```text
/workspaces/fima
├── index.html
├── README.md
└── (browser local storage for saved data)
```

## Data and privacy

Fima is designed for personal use and keeps records in the browser. This means:

- your data is stored locally on the device/browser
- no cloud sync is included
- browser data loss or clearing storage can remove saved records
- exporting backups is recommended before changing devices or clearing browser data

## Use notes

- The app is intentionally minimal and privacy-first.
- It is best suited for tracking your own household or personal expenditures.
- If you are using a shared browser profile, consider keeping backups and being aware that local storage is tied to that browser.

## License

This project is provided as-is for personal use. Add your preferred license here if you plan to distribute or publish it.
