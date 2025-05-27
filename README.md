# 🚲 Citi Bike Station Map – Leaflet.js Interactive Map

This project visualizes Citi Bike stations on an interactive web map using **Leaflet.js**. It loads station data and plots markers over a live OpenStreetMap base layer, offering an intuitive way to explore New York City's bike network.

---

## 🌐 Demo Features

- 🗺️ Dynamic OpenStreetMap background
- 📍 Interactive station markers
- 🧭 Map centered on New York City
- 🧩 Modular structure with external JS/CSS files

---

## 📁 Project Structure

Solved/
├── index.html # Main HTML with map container
├── static/
│ ├── css/
│ │ └── style.css # Custom styles
│ └── js/
│ └── logic.js # Leaflet map and marker logic
└── README.md


---

## 🧪 Technology Stack

- **Leaflet.js** – mapping library
- **OpenStreetMap** – tile layer provider
- **HTML + CSS** – structure and styles
- **JavaScript** – logic to render map and layers

---

## 📦 Setup

To run locally:

```bash
# No installation required – just open index.html in browser
open Solved/index.html

🧩 Sample Snippet

let map = L.map("map-id", {
  center: [40.73, -74.0059],
  zoom: 12,
  layers: [streetmap, bikeStations]
});
