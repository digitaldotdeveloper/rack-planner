# Head Office Rack Planner

Plan a server-room cabinet layout in the browser. Two cabinets, a 2D front elevation with drag-to-place equipment, a live free-U count per cabinet, and a 3D orbit view.

- Single file, no build step: open `index.html`.
- Drag any device inside a rack to move it, or edit cabinet, U height, quantity and bottom U in the table.
- Untick a row to leave it out of the count. Red outline = overlap or outside the cabinet.
- Tower servers are drawn standing upright on a shelf (about 10U + 1U shelf), two per shelf.
- Everything is saved in the browser (localStorage). "Reset" restores the sample head-office list.

Live: https://digitaldotdeveloper.github.io/rack-planner/
