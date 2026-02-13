# Distance Tracker

A single-file interactive HTML webapp that calculates and displays the straight-line distance between your home and another location on a map.

## Features

- Pre-filled home address (editable) with automatic geocoding
- Live address autocomplete powered by Nominatim/OpenStreetMap
- Interactive Leaflet.js map with grayscale tiles
- Haversine formula for straight-line distance calculation
- Dashed line connecting home and target locations

## Usage

Open `index.html` in any browser. No server required.

## Tech

- Vanilla HTML/CSS/JS (single file, no build step)
- Leaflet.js (CDN) + OpenStreetMap tiles
- Nominatim API for geocoding
