# 41 Westover Color Studio

An interactive 3D model of our Craftsman bungalow at 41 Westover Dr in Asheville, NC. We built it to choose paint colors for the new James Hardie siding.

**Live site:** https://brendansudol.github.io/westover-color-studio/

## What it does

- A three.js model of the house, based on our photos and satellite imagery: the front-gable main block, the wing with its inset porch, knee brackets, the rear section, the back addition over the patio, and the walk-out basement.
- Paint by area: siding, gables (lap, shingle, or board and batten), trim, brackets and porch beam, front door, porch ceiling, foundation, porch floor, and roof.
- A fan deck of 74 Sherwin-Williams and Benjamin Moore colors, with LRV values, plus a custom color picker.
- The sun position is calculated for Asheville on any date and time. The house faces east, so the front is in shade after about 1:15 PM in late September. There's also an overcast mode.
- Save schemes (they're stored in your browser), compare two in a draggable split view, and copy the paint list.

Screen colors are approximate. Test physical samples on the house before you buy.

## Running locally

It's a single static `index.html` file that loads three.js from jsDelivr. Serve the folder with any static server, for example:

```
python3 -m http.server
```
