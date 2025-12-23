# Google Maps - Three Locations

A clean, single-page HTML application displaying three Google Maps with highlighted locations.

## Features

- Three Google Maps displayed side by side
- Each map highlights a specific location with a marker
- Responsive design that works on desktop and mobile
- Clean, modern UI with smooth hover effects

## Setup Instructions

1. **Get a Google Maps API Key**
   - Go to [Google Cloud Console](https://console.cloud.google.com/)
   - Create a new project or select an existing one
   - Enable the "Maps JavaScript API"
   - Create credentials (API Key)
   - Copy your API key

2. **Add Your API Key**
   - Open `index.html`
   - Find the line: `src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap"`
   - Replace `YOUR_API_KEY` with your actual Google Maps API key

3. **Open the File**
   - Simply open `index.html` in your web browser
   - The maps will load automatically

## Locations

The page displays three locations:
- **Location 1**: New York City (40.7128, -74.0060)
- **Location 2**: London (51.5074, -0.1278)
- **Location 3**: Tokyo (35.6762, 139.6503)

You can easily modify the coordinates in the `locations` array within the `<script>` tag to display different locations.

## Customization

To change the locations, edit the `locations` array in the JavaScript section:

```javascript
const locations = [
    { lat: 40.7128, lng: -74.0060, name: 'New York City' },
    { lat: 51.5074, lng: -0.1278, name: 'London' },
    { lat: 35.6762, lng: 139.6503, name: 'Tokyo' }
];
```

