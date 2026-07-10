# ON THE FLOOR v2026 - web app 2026

> **Browser-based Los Angeles dance studio finder with live open-now filtering, parking details, and cost estimates for 2026.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/andrew-foster2002/on-the-floor-2026-web-app?style=flat-square)](https://github.com/andrew-foster2002/on-the-floor-2026-web-app)

---

<p align="center">
  <a href="https://andrew-foster2002.github.io/on-the-floor-2026-web-app/">
    <img src="https://img.shields.io/badge/Download-ON%20THE%20FLOOR%20Latest-brightgreen?style=for-the-badge" alt="Download ON THE FLOOR">
  </a>
</p>

> **[Direct Download - ON THE FLOOR v2026](https://andrew-foster2002.github.io/on-the-floor-2026-web-app/)**

---

[Download Latest Build](https://andrew-foster2002.github.io/on-the-floor-2026-web-app/)

---

## What ON THE FLOOR Does

ON THE FLOOR is a browser-based web app built for discovering dance studios across Los Angeles, with a strong emphasis on what is open at the moment. It combines studio discovery, filtering, parking lookup, and trip cost context so you can compare choices without bouncing between different websites.

The experience is meant to support quick decisions. You can narrow listings by neighborhood, dance style, price, and free parking, then open a studio detail page for hours, vibe, style notes, pricing, and review links.

---

## Key Capabilities

- Discover LA dance studios that are open right now
- Sort and filter by area, style, price, and free parking
- See parking search results and parking cost details on a map
- Compare estimated door-to-door costs for driving or rideshare
- Open detailed studio cards with hours, styles, vibe, and price
- Visit review links associated with studio listings
- Run as a client-side single-page app in the browser
- Use map sources such as Google Maps and Parkopedia references

---

## Getting Started

This project runs as a browser app, so the setup is intentionally simple.

1. Download or clone the repository:
   - `git clone https://github.com/andrew-foster2002/on-the-floor-2026-web-app.git
2. Open the app in a browser from the published build or from local files.
3. If you are running it locally, serve the files with any static web server and load the entry page in your browser.

Example local launch:

- `python3 -m http.server 8000`

Then visit:

- `http://localhost:8000`

---

## How to Use It

1. Open ON THE FLOOR in your browser.
2. Search or browse Los Angeles dance studios.
3. Apply filters for area, dance style, price, and free parking.
4. Check which studios are open now.
5. Review the parking map and cost estimate before picking a location.
6. Open a studio detail view to compare hours, vibe, pricing, and external reviews.

For the smoothest workflow, narrow the list first and then open individual listings, especially when comparing nearby studios or planning around parking availability.

---

## Configuration Notes

ON THE FLOOR is a client-side single-page app, so most of the behavior is handled directly in the browser.

In general, settings are driven by the app's data sources and built-in filters rather than a separate config file. If you customize the project, keep data, map references, and review links in sync with the app's HTML and client-side scripts.

Example project-level settings pattern:

- Studio data source: app-managed content
- Map and parking references: external service links
- Filters: area, style, price, parking
- Trip estimates: drive or rideshare context

---

## Requirements

- A modern browser
- Internet access for map, parking, and review links
- Static file hosting if running a local copy
- No special runtime is required beyond browser support for HTML and client-side app behavior

---

## FAQ

**Does the app show studios that are open right now?**  
Yes, this is one of the main browsing modes the app supports.

**Can I narrow results by parking or price?**  
Yes. Filtering and sorting cover area, style, price, and free parking.

**Where does the parking information come from?**  
The app points to parking search and parking cost mapping, with external map sources such as Google Maps and Parkopedia noted in the project metadata.

**How do I update the app?**  
Replace your local copy with the newest build from the published download location, then reopen it in the browser.

**What if something looks outdated or missing?**  
Refresh the data view, double-check the filter settings, and make sure any external map or review links still resolve properly.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
