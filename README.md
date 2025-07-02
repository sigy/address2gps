# Address to GPS Converter

A simple, one-page web application for converting street addresses to GPS coordinates with real-time visualization.

**🌐 Live Demo:** [https://sigy.github.io/address2gps/](https://sigy.github.io/address2gps/)

## Features

- **Batch Conversion**: Convert multiple addresses at once by entering them line by line
- **Interactive Map**: Real-time map visualization with markers for each converted location
- **Copy Functionality**: One-click copy for individual coordinates or complete GPS pairs
- **Queue Visualization**: See conversion progress with visual queue states

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Mapping**: Leaflet.js with CartoDB tiles
- **Geocoding**: OpenStreetMap Nominatim API

## Usage

1. Enter street addresses in the text area (one per line)
2. Click "Convert to GPS" to start the conversion process
3. View results in the table with copy buttons for coordinates
4. See locations plotted on the interactive map
5. Use the restart button to clear and start over

## File Structure

```
Address2gps/
├── index.html          # Complete single-page application
└── README.md           # This file
```

## Getting Started

Simply open `index.html` in any modern web browser. No installation or build process required.

## Browser Support

Works in all modern browsers that support:
- ES6+ JavaScript features
- CSS Grid and Flexbox
- Fetch API
- Clipboard API