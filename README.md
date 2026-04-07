# to.ryo 途旅

> **途** (*tō*) — path, route · **旅** (*ryo*) — journey, travel

**to.ryo** is an open transport portal for interactive map visualization, rail schematic diagrams, timetables and route planning — built on [OpenStreetMap](https://openstreetmap.org) / [OpenGeoFiction](https://opengeofiction.net) data via the Overpass API.

Currently featuring the **Izaland** fictional nation network as primary showcase.

## Features

| Feature | Status |
|---|---|
| IZX high-speed rail diagram | ✅ Live |
| Interactive OSM/OGF map (MapLibre) | 🚧 Coming soon |
| Sainðaul Metro schematic | 🚧 Coming soon |
| Timetables | 🚧 Coming soon |
| Route planner (OTP) | 🚧 Coming soon |

## Tech stack

- **Map**: [MapLibre GL JS](https://maplibre.org/) + OSM/OGF tile server
- **Data**: [Overpass API](https://overpass-api.de/) for live OSM queries
- **Diagrams**: SVG / D3.js
- **Routing** (planned): [OpenTripPlanner](https://www.opentripplanner.org/) + GTFS
- **Frontend**: Vanilla HTML/CSS/JS — no framework dependency

## Getting started

```bash
git clone https://github.com/izaland/toryo.git
cd toryo
# open index.html in your browser — no build step required
```

For the full portal with all features, enable GitHub Pages:
`Settings → Pages → Source: main / / (root)`

## Name

*to.ryo* (途旅) is styled with a dot separator in the spirit of domain names and conlang orthography. Pronounced **to·ryo**, blending Japanese 途 (path) and 旅 (journey).

## License

MIT — map data © OpenStreetMap contributors / OpenGeoFiction community
