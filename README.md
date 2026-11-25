# Budget Tracker

A monthly expense and budget tracker in rupees that answers one question: where did my money go?

**Live:** [budget.mahimlamichhane.com.np](https://budget.mahimlamichhane.com.np)

## Features
- Log income and expenses with amount, date, category and a note
- A monthly budget per category with **On track**, **Near limit** and **Over** flags; click any amount to change it
- **Spending pace** chart: money spent so far against an even pace to the total budget, with a plain-English verdict
- Category split (donut chart), filterable ledger, undo after delete, month-by-month history
- CSV export and import
- Opens with clearly marked example data; **Start fresh** clears it

## Design decisions
- **Privacy:** data is stored only in the visitor's browser (`localStorage`). Nothing is sent to a server.
- **No dependencies:** one HTML file; charts are hand-built SVG.
- Indian/Nepali number grouping (1,23,456) for rupee amounts.

## Run it
Open `index.html` in a browser. Deployed on Cloudflare Workers static assets.

MIT licensed.
