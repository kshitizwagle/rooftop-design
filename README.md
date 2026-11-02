# Rooftop Design – 3D Renovation Concept

An interactive mobile-friendly Three.js model of a proposed rooftop home office (9 × 10 ft), living room (11 × 10 ft), and **separately accessible** bathroom (5 × 7 ft) with 10 ft walls and sloped EPS roofs.

## Features
- Three layout options (switch at the top, or link directly with `#a`, `#b`, `#c`):
  - **A · Two rooms** — separate office and living room, each with its own door
  - **B · Studio, bed right** — one open 20 × 10 ft room, no partition; desk by the door, bed behind a ceiling-track curtain
  - **C · Studio, bed left** — open room with the bed at the far end behind a curtain; desk and a small TV lounge by the door
- Curtain toggle to see the studio open or closed off
- Full 3D orbit, zoom and pan on desktop and mobile, with smooth camera moves
- Views: Exterior, Dollhouse (walls cut at 4.5 ft), Plan, and Office / Living / Bath close-ups
- Layers for roof, walls, furniture, electrical & data, plumbing, room labels and the proposed water tank
- Tap any fixture, socket, light, door or window for a description
- Bathroom is fully enclosed and opens onto its own covered nook off the walkway, never through a room
- Static hosting. No backend or build step required. ES modules served from jsDelivr CDN.

## Run

Use a local static server: `python3 -m http.server 8000`, then visit `http://localhost:8000`. To publish, enable GitHub Pages on `main` branch, `/ (root)` folder in **Settings → Pages**.

## Important limitations
This is a schematic design based on an evolving renovation brief, **not a measured survey, structural plan, MEP shop drawing, or building permit drawing**. The existing room is assumed demolished, existing staircase retained, and rooftop tank relocation is indicative only. Engineer must verify RCC loading, anchorage, tank support, wind/seismic design, waterproofing and drainage. Coordinates and window/door placements must be field-measured. No tank relocation or demolition should occur before structural review.