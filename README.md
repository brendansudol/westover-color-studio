# 41 Westover Color Studio

An interactive 3D model of our Craftsman bungalow at 41 Westover Dr in Asheville, NC. We built it to choose paint colors for the new James Hardie siding.

**Live site:** https://brendansudol.github.io/westover-color-studio/

## What it does

- A three.js model of the house, based on our photos and satellite imagery: the front-gable main block, the wing with its inset porch, knee brackets, the rear section, the back addition over the patio, and the walk-out basement.
- Paint by area: siding, gables (lap, shingle, or board and batten), trim, brackets and porch beam, front door, porch ceiling, foundation, porch floor, and roof.
- The full Sherwin-Williams exterior palette: all 1,575 current colors that SW lists for exterior use, from their ColorSnap catalog. They're laid out in the same strips as the in-store color wall, with tabs for the Top 50 Exterior, Historic and Arts & Crafts collections. It has search, LRV values, store-wall locators, a custom color picker, and hover-to-preview on the house.
- The sun position is calculated for Asheville on any date and time. The house faces east, so the front is in shade after about 1:15 PM in late September. There's also an overcast mode.
- Save schemes (they're stored in your browser), compare two in a draggable split view, and copy the paint list.

Screen colors are approximate. Test physical samples on the house before you buy.

## Running locally

It's a single static `index.html` file that loads three.js from jsDelivr. Serve the folder with any static server, for example:

```
python3 -m http.server
```
