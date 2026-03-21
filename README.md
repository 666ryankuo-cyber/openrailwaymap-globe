# Global Railway Monitor - Professional GIS Dashboard

A high-performance, web-based Global Information System (GIS) designed for visualizing worldwide railway infrastructure. This project leverages **CesiumJS** for 3D globe rendering and integrates **OpenRailwayMap** data to provide real-time insights into track speeds, signaling, and electrification.

---

## 🚀 Features

* **3D Global Visualization**: Full 360-degree interactive globe with high-precision camera controls.
* **Multi-Layer Rail Data**: Switch between different specialized railway layers:
    * *Standard Infrastructure*: General track layout.
    * *Max Speeds*: Color-coded visualization of speed limits.
    * *Signalling*: Locations of signals and train protection systems.
    * *Electrification/Gauge*: Technical details of the rail network.
* **Real-time GIS Telemetry**: Live tracking of Latitude, Longitude, Altitude, and a dynamic scale bar.
* **Modern UI/UX**: Professional "Glassmorphism" interface with a responsive digital compass and status monitor.
* **Secure Access**: Built-in authentication gate for Cesium Ion API integration.

## 🛠️ Tech Stack

* **Engine**: [CesiumJS](https://cesium.com/platform/cesiumjs/) (3D Geospatial Engine)
* **Data Source**: [OpenRailwayMap](https://www.openrailwaymap.org/) (via OpenStreetMap API)
* **Frontend**: HTML5, CSS3 (Advanced Backdrop Filters), Vanilla JavaScript
* **Icons/Graphics**: Custom SVG Vector Graphics

## 📖 How to Use

1.  Open the [Live Demo](https://666ryankuo-cyber.github.io/openrailwaymap-globe/rail.html).
2.  Input your **Cesium Ion Access Token** in the system access overlay.
3.  Click **"INITIALIZE ENGINE"** to boot the system.
4.  Use the top-left menu to toggle between railway layers and base map styles (Satellite, Gray Canvas, etc.).
5.  Click the **Compass** at the top-right to reset the view to North.

## 🏗️ Development Progress

This project is currently part of a **18-week Independent Study Program**. 
- [x] Phase 1: Core 3D Engine Setup & Base Maps
- [x] Phase 2: OpenRailwayMap Tile Integration
- [x] Phase 3: Professional UI/UX Implementation & GIS Telemetry
- [ ] Phase 4: (Upcoming) Search functionality and 3D Building layers

## ⚖️ License & Data Credits

* **Map Data**: © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors.
* **Railway Data**: © [OpenRailwayMap](https://www.openrailwaymap.org/).
* **3D Engine**: CesiumJS under Apache 2.0 License.

---
*Developed by Kuruwa Aozora*
