# Earthquake Data Visualization

## Overview

This project is an interactive web-based visualization of earthquake data. It uses Leaflet, an open-source JavaScript library, for interactive map features, and D3.js for handling and visualizing data. The map displays earthquakes from across the country, showing their locations, magnitudes, and depths.

## Features

- **Interactive Map**: Utilizes Leaflet to render an interactive map.
- **Earthquake Markers**: Earthquakes are represented as markers on the map. The size of each marker corresponds to the earthquake's magnitude.
- **Color-Coded Depths**: Each marker's color indicates the depth of the earthquake, providing an immediate visual cue of its geological characteristics.
- **Tooltips**: Clickable markers that display detailed information about the earthquake, including its location, magnitude, and depth.
- **Depth Legend**: A legend on the map explains the color coding of the earthquake depths.

## Technologies Used

- **Leaflet**: An open-source JavaScript library for mobile-friendly interactive maps.
- **D3.js**: A JavaScript library for manipulating documents based on data.
- **HTML/CSS**: For structuring and styling the webpage.

## Data Source

The earthquake data is sourced from the United States Geological Survey (USGS) and is updated regularly. The data is fetched in GeoJSON format, providing a rich dataset for visualization.
