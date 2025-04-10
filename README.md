# leaflet-challenge-

Earthquake & Tectonic Plate Visualization

An interactive web map built using **Leaflet.js**, **D3.js**, and **GeoJSON** data to visualize recent earthquakes and global tectonic plate boundaries. This project displays circle markers for earthquakes with dynamic radius and color based on magnitude and depth, and overlays tectonic plates for geological context.

---

 Features

- 🗺️ Interactive Leaflet map with layer controls
- 🌐 Two base map options: Light (OpenStreetMap) and Dark (CartoDB Dark Matter)
- 🌋 Earthquake data for the past 7 days from the USGS
- 🌍 Tectonic plate boundaries from GeoJSON
- 🎨 Earthquake markers styled by depth and magnitude
- 🧭 Custom legend and popups with detailed quake info

---

Project Structure

project/ │ ├── index.html # Main HTML file ├── static/ │ ├── css/ │ │ └── style.css # Custom styles │ └── js/ │ └── logic.js # Leaflet + D3 logic


---

Technologies Used

- [Leaflet.js](https://leafletjs.com/)
- [D3.js](https://d3js.org/)
- [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)
- [Tectonic Plate Data (GitHub)](https://github.com/fraxen/tectonicplates)

---



Preview

![alt text](<Screenshot 2025-04-09 at 8.59.22 PM.png>)

---
 License

This project is open-source and free to use. Attribution required for data providers (USGS, CARTO, OpenStreetMap).
