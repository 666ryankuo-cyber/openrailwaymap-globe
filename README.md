# Global Railway Monitor - Professional GIS Dashboard

A high-performance, web-based Global Information System (GIS) designed for visualizing worldwide railway infrastructure in a 3D geospatial environment. This project leverages **CesiumJS** for high-fidelity globe rendering and integrates **OpenRailwayMap** vector tiles to provide professional insights into global rail networks.

---

## 🚀 Key Features

* **Advanced 3D Environment**: 
    * **3D Buildings**: Integrated Cesium OSM Buildings for realistic urban context.
    * **3D Global Terrain**: Real-world elevation data (createWorldTerrain) for mountain and valley rail route analysis.
* **Intelligent Navigation System**:
    * **Neutral Boot-up**: System initializes at $(0.0, 0.0)$ for a neutral monitoring starting point.
    * **Smart Home Reset**: Custom Home button logic that performs a vertical ascent to 15,000km while maintaining the current observation target.
    * **One-Click North Alignment**: Integrated SVG compass that resets camera heading and pitch to a top-down North view.
* **Professional Railway Layers**: 
    * *Standard Infrastructure*: General track layout.
    * *Max Speeds*: Color-coded visualization of speed limits.
    * *Signalling*: Locations of signals and train protection systems.
    * *Electrification*: Analysis of power supply overhead lines.
    * *Track Gauge*: Worldwide gauge distribution data.
* **Global Search Engine**: Integrated OpenStreetMap (Nominatim) geocoder for instant navigation to any station or city.
* **Real-time GIS Telemetry**: Live digital HUD displaying Solar Time, UTC Offset, Latitude, Longitude, and Altitude (km).
* **Modern UI/UX**: Professional "Glassmorphism" interface with a responsive sidebar and a hideable HUD for immersive presentations.

## 🛠️ Tech Stack

* **3D Engine**: [CesiumJS](https://cesium.com/platform/cesiumjs/) (Web-based Geospatial Engine)
* **Data Providers**: 
    * **Rail**: [OpenRailwayMap](https://www.openrailwaymap.org/) (via WMTS/TMS)
    * **Buildings**: Cesium OSM Buildings
    * **Terrain**: Cesium World Terrain
    * **Base Maps**: ArcGIS (Gray/Dark), Bing Satellite, Sentinel-2, OSM
* **Search API**: [OSM Nominatim](https://nominatim.org/)
* **Frontend**: Pure Vanilla JavaScript, HTML5, CSS3 (Advanced Backdrop Filters)

## 📖 How to Use

1.  Open the [Live Demo](https://666ryankuo-cyber.github.io/openrailwaymap-globe/rail.html).
2.  Input your **Cesium Ion Access Token** in the system access overlay.
3.  Click **"INITIALIZE ENGINE"** to boot the system.
4.  **Navigation**:
    * Use the **Left Menu** to toggle 3D Buildings/Terrain and switch Railway styles.
    * Use the **Search Bar** to fly to a specific location.
    * Click the **Compass (Top-right)** to align North.
    * Click the **Home Icon (Cesium Default)** to perform a vertical zoom-out.
    * Press the **Satellite Icon (Bottom-right)** to toggle the HUD.

## 🏗️ Development Progress (18-week Program)

This project was developed as part of a **18-week Independent Study Program**.
- [x] **Week 1-4**: Core 3D Engine Setup, Neutral View Logic & Multi-Basemap Integration.
- [x] **Week 5-8**: OpenRailwayMap Tile Integration & HUD Glassmorphism UI Design.
- [x] **Week 9-12**: Compass Correction, Custom Home Logic & Nominatim Search Implementation.
- [x] **Week 13-16**: 3D Buildings & World Terrain Integration with Imagery Draping.
- [x] **Week 17-18**: Performance Optimization, HUD Toggles & Final Refactoring.

## ⚖️ License & Data Credits

* **Map Data**: © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors.
* **Railway Data**: © [OpenRailwayMap](https://www.openrailwaymap.org/).
* **3D Engine**: CesiumJS under Apache 2.0 License.

---
*Developed by Kuruwa Aozora*
