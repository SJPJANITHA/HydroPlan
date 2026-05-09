<img width="1856" height="913" alt="Screenshot 2026-04-21 141653" src="https://github.com/user-attachments/assets/f4b76f6e-75d7-4b05-bac6-3cd234b3894c" />






# 🚢 HydroPlan

> Can we make hydrographic survey planning more data-driven before going to the field?

A browser-based pre-survey decision platform built to centralize operational intelligence for hydrographic surveying — no installs, no heavy software.

---

## The Problem

Hydrographic survey planning means checking multiple disconnected sources — weather, waves, hazards, daylight windows — before every deployment. HydroPlan pulls it all into one place to reduce downtime, improve safety, and support faster decision-making.

---

## What It Does

**Survey Area Planning**
- Draw your survey area on the map with automatic area calculations
- Plan survey lines and export as CSV, KML, GeoJSON, or HYPACK Line File

**Operational Scoring**
- GO / CAUTION / NO-GO scoring based on live conditions
- 48-hour and 7-day survey window optimization

**Environmental Analysis**
- Wave, wind, and weather forecasts
- Daylight window analysis
- Hazard alerts relevant to survey operations (storms, seismic activity, disasters)

**Automated Briefing**
- Generate a pre-survey operational briefing report before mobilization

---

## Why It's Useful

Survey teams typically check weather portals, tide tables, hazard feeds, and forecast services separately. HydroPlan attempts to centralize this into one operational view to:

- Reduce mobilization risks and vessel downtime
- Improve crew safety during operations
- Optimize deployment windows
- Support faster, data-driven go/no-go decisions

---

## No Install Required

Open the HTML file in Chrome, Firefox, or Edge. No server. No Python. No setup.

---

## Data Sources

| Source | Data |
|---|---|
| Open-Meteo Marine API | Wave and wind forecasts |
| Open-Meteo Weather API | Atmospheric forecasts |
| NOAA Marine Forecast | Ocean conditions |
| GDACS | Disaster and hazard alerts |
| USGS | Seismic activity |
| OpenStreetMap / Natural Earth | Basemap layers |

## Stack

- Vanilla JavaScript + HTML
- Leaflet.js (interactive mapping)

---

> This is an ongoing exploration. Planning to add more hydrographic-specific capabilities over time.

Open to suggestions from anyone working in hydrographic surveying, marine operations, or survey planning.

---

## License

MIT
