# Sunrise and Sunset Times

A modern web app to view sunrise, sunset, golden hour, and blue hour times for any location and date, with timezone support and interactive map.

## Features
- Search by city or address with autocomplete
- Select date (with "Today" button)
- View sunrise, sunset, golden hour, and blue hour times
- Interactive map (click to select location)
- Responsive, mobile-friendly UI
- Save favorite locations
- Share results (clipboard or native share)
- Dark mode toggle
- Accessibility enhancements

## Usage
1. Enter a city or address, or use your current location.
2. Select a date or click "Today".
3. View results and interact with the map.
4. Save favorites or share results.

## Deployment
- Automatically deployed to GitHub Pages from the `main` branch using GitHub Actions.
- TimeZoneDB API key is injected during deployment via repository secret.

## Technologies
- HTML, JavaScript
- [Tailwind CSS](https://tailwindcss.com/)
- [Leaflet.js](https://leafletjs.com/)
- [SunCalc](https://github.com/mourner/suncalc)
- [OpenStreetMap](https://www.openstreetmap.org/)
- [Nominatim](https://nominatim.openstreetmap.org/)

## Accessibility & UX
- Keyboard navigation and ARIA labels
- Tooltips for time definitions
- Error handling and loading indicators

## License
MIT
