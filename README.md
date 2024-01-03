# Map Project using Mapbox GL JS

This project utilizes Mapbox GL JS to display an interactive map with navigation functionality.

## Description

The HTML file (`index.html`) sets up the structure for displaying the map by including Mapbox GL JS library and its related plugins. The map is displayed within a div element with the ID 'map'.

## Features

- **Map Display**: Renders a map using Mapbox GL JS.
- **Geolocation**: Accesses the user's current location using the browser's geolocation API.
- **Map Controls**: Includes zoom controls and direction/navigation controls.
- **Styling**: Applies a default Mapbox style ('mapbox://styles/mapbox/streets-v11') to the map.

## Setup and Usage

1. Clone or download the repository.
2. Open `index.html` in a web browser to view the map.
3. Ensure an internet connection to load Mapbox tiles and resources.
4. The map initially centers based on the user's geolocation. If geolocation is denied or not available, it defaults to a predefined location.

## File Structure

- `index.html`: Contains the HTML structure for displaying the map.
- `script.js`: JavaScript file that initializes the map, geolocation, and map controls.

## Requirements

- Modern web browser with JavaScript enabled.
- Internet connection to fetch map resources from Mapbox.

## Credits

- [Mapbox](https://www.mapbox.com/) - Provides the mapping platform and resources.
- Icons by [paomedia](https://icons.iconarchive.com/icons/paomedia/small-n-flat/) - Map marker icon used as the favicon.

