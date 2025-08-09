# Luxury Estates - Real Estate Website

A fully responsive, multi-page real estate listing website built with HTML5, CSS3, and Vanilla JavaScript.

## Features

- **Modern Luxury Design**: Elegant color scheme with gold accents, glassmorphism effects, and smooth animations
- **Responsive Layout**: Fully responsive across all device sizes
- **Property Listings**: Grid and list view options with filtering and sorting
- **Property Details**: Comprehensive property pages with image galleries and contact forms
- **Dark/Light Mode**: Toggle between dark and light themes with localStorage persistence
- **Favorites System**: Save favorite properties using localStorage
- **Contact Forms**: Fully validated contact forms with submission handling
- **Performance Optimized**: Lazy loading, optimized animations, and clean code architecture

## Pages

1. **Home Page**: Hero section, featured properties carousel, company stats
2. **Listings Page**: Filterable property grid with sorting and pagination
3. **Property Detail Page**: Full property details, image gallery, contact form
4. **About Page**: Company information and team profiles
5. **Contact Page**: Contact form with validation and map

## Installation

No installation required. Simply open `index.html` in a web browser.

## Dependencies

- Font Awesome (loaded from CDN)
- Google Fonts (loaded from CDN)
- NoUI Slider (for price range filter, loaded from CDN)

## How to Use

1. Clone or download this repository
2. Open `index.html` in your browser
3. Navigate through the website using the menu

## Adding Real Google Maps

To enable real Google Maps functionality:

1. Get a Google Maps API key
2. Replace the `initMap()` function in `detail.js` and `contact.js` with the actual implementation
3. Add the Google Maps script to your HTML files:

```html
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap" async defer></script>