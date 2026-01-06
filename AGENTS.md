# AGENTS.md

This repository is a simple and practical analog clock Static Web App. It runs as a single HTML file, requires no server or build steps, and works by opening it directly in a browser.

## Goals and principles
- Keep the structure easy to distribute as a Static Web App
- Prioritize good visuals and smooth performance
- Align updates to second boundaries to avoid unnecessary redraws
- Redraw static elements only on initial render and resize
- Update date-related information only when it changes
- Avoid OS-dependent layout measurements when clamping date UI; use fixed layout dimensions with current scale instead

## Primary file
- Main working file: `index.html`

## How to run
- Open `index.html` directly in a browser (no build needed)
- For GitHub Pages, place it at the repository root

## External library
- SVG.js (CDN, MIT License)

## Repository
- https://github.com/igapyon/AnalogClocket
