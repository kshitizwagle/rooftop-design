# Rooftop Design – 3D Renovation Concept

An interactive mobile-friendly Three.js model of a proposed rooftop home office (9 × 10 ft), living room (11 × 10 ft), and **separately accessible** bathroom (5 × 7 ft) with 10 ft walls and sloped EPS roofs.

## Features
- Full 3D orbit, zoom and pan on desktop/mobile
- Exterior, cutaway, overhead, and room-focused camera presets
- Layer controls for roof, exterior walls, furniture, power/data points, plumbing, labels and relocated water tank
- Click/tap inspection of switches, sockets, CAT6, ceiling lights, AC points, WC, basin, shower, floor drain, and fixtures
- Static hosting. No backend or build step required. ES modules served from jsDelivr CDN.

## Run

Use a local static server: `python3 -m http.server 8000`, then visit `http://localhost:8000`. To publish, enable GitHub Pages on `main` branch, `/ (root)` folder in **Settings → Pages**.

## Important limitations
This is a schematic design based on an evolving renovation brief, **not a measured survey, structural plan, MEP shop drawing, or building permit drawing**. The existing room is assumed demolished, existing staircase retained, and rooftop tank relocation is indicative only. Engineer must verify RCC loading, anchorage, tank support, wind/seismic design, waterproofing and drainage. Coordinates and window/door placements must be field-measured. No tank relocation or demolition should occur before structural review.