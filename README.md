# Seputar Berita

Static HTML/CSS news portal website built with pure HTML5 and CSS3. No JavaScript frameworks or build tools required.

## Features

- **Thumbnail grid system** with fixed dimensions and `object-fit: cover`
- **Responsive design** - thumbnails become full-width on mobile (≤768px)
- **Lazy loading** on all images for performance
- **Two image presentation modes**: grid thumbnails and full-width articles
- **Accessible alt text** on all images
- **Hover shadow effects** on article containers

## Project Structure

- **14 HTML files** - article pages with different topics (Politics, Games, Food, Sports, etc.)
- **2 CSS files** - `tampilan depan.css` (main layout) and `isi-berita.css` (article page styles)
- **11 JPEG image files** - used as thumbnails and article headers

## Usage

Simply open any `.html` file in a browser. No build step or installation required.

## Images

All images use `loading="lazy"` for performance. Image paths reference files with `.jpg.jpeg` extensions.