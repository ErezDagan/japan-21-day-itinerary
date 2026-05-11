# Japan 21-Day Itinerary — Interactive Map

A single-file HTML planning page for an exploratory 21-day trip across Japan: Kanto coast → Tokyo → Kyoto → Hokuriku → Kiso/Alps → Shikoku → Kyushu → finale (Okinawa | Yakushima | Hiroshima).

## What's here

| File | Description |
|---|---|
| [`index.html`](./index.html) | Latest version (v3.4). Open in a browser. |
| [`japan_21_day_map_itinerary_v3-4.html`](./japan_21_day_map_itinerary_v3-4.html) | v3.4 — Days 1–9 LOCKED from v3.3 (Kamakura · Tokyo · Nikko). Days 10–21 driven by the **Japan Travel Guide PDF** in the repo: Karuizawa → Hokuto/Yatsugatake (insider villa-country pick — Suntory Hakushu, Risonare, horseback) → Kyoto + Nara (Kyoto Railway Museum, Fushimi dawn, Nara deer) → Shirahama white beach (Adventure World panda finale). |
| [`japan_21_day_map_itinerary_v3-3.html`](./japan_21_day_map_itinerary_v3-3.html) | v3.3 — Kamakura/Enoshima · Tokyo (parks · museums · taste) · Nikko ryokan · Kyoto-region ryokan · **Third region with 3 options** (Nagano · Tohoku · San'in) · **White-beach finale with 2 options** (Wakayama Shirahama · Okinawa Taketomi). |
| [`japan_21_day_map_itinerary_v3-2.html`](./japan_21_day_map_itinerary_v3-2.html) | v3.2 — wide-Japan explorer plan: Kanto coast → Tokyo → Kyoto → Hokuriku → Kiso/Alps → Shikoku → Kyushu → finale choice. |
| [`japan_21_day_map_itinerary_v3-1.html`](./japan_21_day_map_itinerary_v3-1.html) | v3.1 (original) — kept as historical reference. |
| [`Japan_Travel_Guide.pdf`](./Japan_Travel_Guide.pdf) | Insider PDF travel guide that drove the v3.4 continuation. |

## v3.2 features

- **English map tiles** (Carto Voyager, no API key required)
- **21 numbered day-zone rectangles** drawn on the overview map; each box pops up that day's overview when clicked
- Centroid polyline showing trip flow across Japan
- **Per-day card** with: status flag, overview, transit description (with ⚠ flags for long days), POI list with Google Maps deep-links, **static mini-map**
- **9 accommodation-change boxes** inserted between days when the base changes — each box has 3 vetted options with "Book direct" + "Booking.com" links
- **Sanity-rebalanced days** — Days 7, 11, 14, 15, 16, 17, 18 had unrealistic POIs/transit in v3.1; rebalanced and flagged with ⚠ inline

## Tech

Vanilla HTML/JS · Leaflet 1.9.4 (via unpkg) · Carto Voyager tiles · OpenStreetMap data. No build step, no API keys, no dependencies beyond the two CDN links.

## Open in browser

Just open `index.html` from `file://` — or visit the GitHub Pages URL once enabled.
