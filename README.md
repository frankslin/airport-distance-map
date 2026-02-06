# Airport Distance SPA

[中文版本](./README.zh.md)

A single-page app that calculates great-circle distances between airports and visualizes routes on a rotating globe.

## Features
- 3,000+ commercial airports (large/medium, scheduled service)
- Smart airport search with multiple input modes (IATA, city/airport name, mixed input)
- Great-circle distance in km and miles, updates instantly
- Interactive globe that auto-rotates to the route and supports drag rotation

## Files
- `airport-distance-app.html` — the full SPA (HTML/CSS/JS in one file)
- `README.zh.md` — Chinese documentation

## Usage
Open `airport-distance-app.html` in any modern browser.

## Data Source
Airport coordinates are derived from the OurAirports public dataset and filtered to `large_airport` and `medium_airport` entries with `scheduled_service=yes` and valid IATA codes.
