# Rooftop Design – 3D Renovation Concept

An interactive, mobile-friendly Three.js model of the rooftop addition on the existing house at plot 268 (Tikathali). The footprint follows the approved ground-floor drawing: about 25'3" × 28' (NW room 13 × 10, NE room 10 × 10, SW room 13 × 11), roughly 690 sq ft of roof slab.

**The plan**
- The brick room with the jasta roof at the south-west comes down.
- The west half gets the new rooms, the bath and a south balcony. New walls sit on the existing wall lines, and the bath sits directly over the existing toilet so it drains into the same stack.
- The stair gets an RCC cover with the 1,000 L water tank on its slab.
- The east half becomes a covered terrace under a jasta shed: salvaged sheets from the old room first, new sheets for the rest, so the leaking slab is fully covered.

## Features
- Three layout options for the west rooms (switch at the top, or link with `#a`, `#b`, `#c`):
  - **A · Office + bed/lounge**: office in the north room with an east window; bedroom with a lounge corner behind a curtain in the south room
  - **B · Living + bed/desk**: living room north; bedroom plus a south-facing desk behind a curtain south
  - **C · Office/lounge + bedroom**: office and lounge share the north room; plain bedroom south
- Curtain toggle to see the studio open or closed off
- Paint tab: colour the house walls, bands and parapets, rooftop rooms, window frames and roof sheets with named RAL Classic shades (any Nepali dealer can tint to a RAL code) and SY Panel roof colours, plus ready-made schemes
- Balcony depth switch (2.5 / 3 / 4 / 5 ft) for the south balcony
- North compass (bottom right): the needle shows where north is; tap it to turn north up
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