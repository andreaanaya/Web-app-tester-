# Mobile UI PWA

A small progressive web app exploring simple mobile-first UI patterns.

This project focuses on:
- A centered popup component
- Conditional UI behavior based on user interaction
- Minimal JavaScript logic
- Clean and readable CSS
- Basic PWA setup (manifest + service worker)

## Features

- Popup-style interface
- Two selectable options
- Conditional content rendering
- Responsive layout
- Installable as a Progressive Web App
- Offline support via Service Worker

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- PWA (Web App Manifest + Service Worker)

## Project Structure
```
 mobile-ui-pwa/
├── index.html
├── style.css
├── script.js
├── manifest.json
├── service-worker.js
└── img/
    ├── option-a.jpg
    └── option-b.jpg
```

## Running the project

Because this project uses a Service Worker, it must be served from a local server.

Recommended:
- VS Code + Live Server extension

Steps:
1. Open the project folder in VS Code
2. Right-click `index.html`
3. Select **Open with Live Server**

## Notes

This project is intentionally kept simple to focus on UI logic and interaction flow without external libraries or frameworks.
