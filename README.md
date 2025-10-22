# Grand Teton Region – Earthquakes & Hospitals Web Map

## Overview
This interactive web map visualizes **earthquake activity** in the Grand Teton / Greater Yellowstone region and the proximity of each event to nearby **hospitals and clinics**. It was created using **Leaflet**, **Turf.js**, and **Leaflet.heat**.

### Datasets
1. **Earthquakes** – Seven sample events (M≥3.5) between 2019–2025, derived from USGS regional data.
2. **Hospitals & Clinics** – Key facilities serving Teton County (WY), Teton Valley (ID), Star Valley (WY), and Idaho Falls (ID).

### Analysis
Each earthquake is analyzed for its **nearest medical facility** using Turf.js’s `nearestPoint` function. The **distance in kilometers** is computed geodesically and visualized with connection lines. An **earthquake heatmap**, weighted by magnitude, highlights clusters of seismic activity.

### Tools & Libraries
- [Leaflet](https://leafletjs.com/) – Mapping library for interactive web maps  
- [Turf.js](https://turfjs.org/) – Geospatial analysis functions (nearest point, distance)  
- [Leaflet.heat](https://github.com/Leaflet/Leaflet.heat) – Heatmap layer plugin  

### Features
- Multiple basemap layers (Street, Satellite, Terrain)
- Popups for both datasets with detailed attributes
- Layer controls for toggling heatmaps and connections
- Legend and responsive layout

#### Local Viewing
1. Download and unzip this folder.
2. Open `index.html` in your browser.

### Example Map Layers
- **Earthquakes (red markers)** – Show magnitude, depth, and nearest facility.
- **Hospitals/Clinics (blue markers)** – Show facility name and city.
- **Heatmap** – Intensity proportional to earthquake magnitude.
- **Connections** – Lines from each quake to the nearest hospital.

### Author
Created by *Krystyna Matunis* for a geospatial web mapping assignment using Leaflet and Turf.js.  
© 2025 – Open-source educational use.

