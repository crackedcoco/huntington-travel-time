# Huntington Area Travel Time Maps

Interactive travel time isochrone visualization for the Huntington, WV area. Shows reachable areas by driving, walking, or cycling from popular locations.

**[View Live Site](https://crackedcoco.github.io/huntington-travel-time/)**

## Features

- **6 Pre-cached Locations**
  - Downtown Huntington
  - Marshall University
  - St. Mary's Medical Center
  - Cabell Huntington Hospital
  - Central City
  - Downtown Barboursville

- **3 Travel Modes**
  - Driving
  - Walking
  - Cycling

- **5 Time Intervals**
  - 5, 10, 15, 30, and 60 minutes

- **Fully Static** - No API calls, works offline
- **Mobile Responsive** - Works on phones and tablets

## How It Works

Travel time isochrones are pre-calculated using the [OpenRouteService API](https://openrouteservice.org/) and embedded directly in the HTML file. This means:

- Instant loading (no API latency)
- No API key required
- Works completely offline
- Zero ongoing costs

## Data Sources

- **Isochrone Data**: [OpenRouteService](https://openrouteservice.org/)
- **Map Tiles**: [CARTO Dark Matter](https://carto.com/basemaps/)
- **Geocoding**: [OpenStreetMap Nominatim](https://nominatim.openstreetmap.org/)

## Tech Stack

- Single HTML file (~1.9MB with cached data)
- [Leaflet.js](https://leafletjs.com/) for mapping
- Vanilla JavaScript (no frameworks)
- CSS Grid for layout

## Local Development

```bash
# Clone the repo
git clone https://github.com/crackedcoco/huntington-travel-time.git
cd huntington-travel-time

# Serve locally
python3 -m http.server 8080

# Open http://localhost:8080
```

## License

MIT License - feel free to use and modify.

## Related Projects

- [Regional Demographics Dashboard](https://github.com/crackedcoco/regional-demographics-dashboard) - Appalachian trauma indicators visualization
