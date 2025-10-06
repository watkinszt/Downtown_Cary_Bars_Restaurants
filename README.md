# Food and Drink Tour of Downtown Cary, NC

## Project Overview
**Food and Drink Tour of Downtown Cary, NC** is an interactive web map that highlights a walking route through downtown Cary, North Carolina. The map showcases several restaurants and cafés along the route, allowing users to explore local food and drink destinations.

Each location is marked with a tooltip and a clickable popup that provides the restaurant’s name, rating, and a direct link for more information. The goal of this project is to provide an engaging, map-based experience for exploring Cary’s downtown dining scene.

---

## Features
- **Interactive Map:** Built with the [Leaflet](https://leafletjs.com/) JavaScript library for responsive web mapping.  
- **Urban Basemap:** Uses *CartoDB.Positron* 
- **Custom Route:** Displays a walking path with a styled dashed blue line.  
- **Place Markers:** Shows individual restaurants as points with tooltips and popups.  
- **Popups with Links:** Each popup contains the restaurant’s name, rating, and a clickable link to learn more.  

---

## Technologies Used
- **HTML5** for page structure  
- **CSS3** for layout and visual styling  
- **JavaScript (ES6)** for interactivity  
- **[Leaflet 1.9.4](https://leafletjs.com/)** for map rendering  
- **[CartoDB.Positron](https://carto.com/basemaps/)** basemap for clear urban visualization  
- **GeoJSON** data loaded through a local `route.js` file  

---

## Data Sources
- Custom-created route and point data in `data/route.js`, formatted as GeoJSON.  
- Basemap tiles courtesy of [CARTO](https://carto.com/) and [OpenStreetMap](https://www.openstreetmap.org/).  
- Restaurant information compiled from public sources (e.g., Google Maps, Yelp).

---

## Author
**Zachary Watkins**  
Created for *Lab 03: Your First Web Map* — GHY5818 Web Mapping  
