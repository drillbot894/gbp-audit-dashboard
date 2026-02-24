# GBP Audit Dashboard

A local SEO competitive analysis tool inspired by GBP Everywhere.

## Quick Start

```bash
# Open in browser
open ./gbp-audit-dashboard.html
# Or serve locally
python3 -m http.server 8000
```

Then search for any local business category + location in the embedded search, or use the mock data to see how it works.

## Features

- **Category Analysis** — See what categories competitors use
- **Services Audit** — Compare services listed
- **Review Tracking** — Monitor ratings and review counts
- **Location Insights** — Geographic distribution
- **Hours & Attributes** — Compare business hours and attributes

## Usage

1. Open `gbp-audit-dashboard.html` in Chrome
2. Search for a local business (e.g., "plumber Austin TX")
3. Click "Scan Results" to analyze the top listings
4. Switch between tabs to see different metrics

## Note

This version uses mock data for demonstration. To make it live:
- You'd need to either build a scraper (complex due to Google ToS)
- Or use an API like SerpAPI, BrightLocal, or Whitespark's API
- The UI is fully functional — just swap in real data when ready
