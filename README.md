# Model Y Scout v2

A search dashboard for finding underpriced Tesla Model Y vehicles (2020–2023) across auctions and marketplaces.

## Features
- Search across Copart, IAAI, CarGurus, AutoTrader listings
- Filter by year, price, mileage, trim, condition, source, state
- AI Price Scout powered by Claude
- Deal scoring (% below market)
- ROI estimator
- CSV export
- Favorites + alerts

## Usage
Open `index.html` directly in a browser — no build step required.
To use the AI Scout, the page calls the Anthropic API directly from the browser.

## Backend (optional)
See `/backend` folder in the full repo for the FastAPI + scraper stack.
