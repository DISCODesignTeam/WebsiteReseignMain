# DISCO Web Redesign Documentation

## Table of Contents
- [Project Directory](#project-directory)
- [Styling Architecture](#styling-architecture)
- [Reusable Components](#reusable-components)
- [Asset Management](#asset-management)
- [Testing & Deployment](#testing--deployment)

## Project Directory
The website consists of the following pages:
- [`index.html`](./index.html): Home/Landing/Welcome page
- [`mission.html`](./mission.html): Mission statement page
- [`workshop.html`](./workshop.html): Workshop page with persona/ship cards, intro manual, slides, and access need pamphlets
- [`credits.html`](./credits.html): team, headshots, contact info

## Styling Architecture
- [`styles.css`](./css/styles.css): Global/shared styles entry with defined color/font variables
- Page-specific style imports are defined from the shared stylesheet.

## Reusable Components
- Main navigation bar
- Hero section
- Content card (with variations)
- Workshop card grids

## Asset Management
- [`./assets/Headshots`](./assets/Headshots/): headshot images
- [`./assets/crew_persona`](./assets/crew_persona/): crew persona images
- [`./assets/ship_deck`](./assets/ship_deck/): ship deck images
- [`./assets/flavor_images`](./assets/flavor_images/): flavor images to add to the website
- [DISCO Google Drive/Web](https://drive.google.com/drive/folders/1iUoQhwR9JyGbYrZbfBrFK0dK8Q750Vi-): Google Drive directory with web images, headshots, and web copies.

## Testing & Deployment
### What to test:
- Navigation
    - Nav bar
    - Jump to top button
    - Links to external sites (Google Docs, Google Drive, etc.)
- Image display + alt text
- Color contrast: [online color contrast checker as an example](https://webaim.org/resources/contrastchecker/)
- Responsiveness under different screen/viewport dimensions

### Running locally
Open the HTML files directly or use IDE extensions like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).

### Deployment
This site is deployed through GitHub Pages. The current live version is the previous design.