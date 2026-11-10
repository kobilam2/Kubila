# Real-Time Inventory Storefront

A lightweight web storefront hosted on GitHub Pages that reads inventory directly from a Google Sheet CSV.

## Features
- Real-time catalog sync from Google Sheets via PapaParse
- Filter by category pills
- Instant search by title, category, or SKU
- Direct buy link buttons to Meesho
- Zero server setup or hosting cost

## Setup Instructions

1. Open your Google Sheet (**inventory update tracker**).
2. Go to **File** → **Share** → **Publish to web**.
3. Select `Sheet1` and choose **Comma-separated values (.csv)**.
4. Click **Publish** and copy the resulting link.
5. In `index.html`, replace `YOUR_GOOGLE_SHEET_CSV_URL_HERE` with your copied link.
6. Push changes to GitHub.
