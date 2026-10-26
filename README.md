# It's a Metric, Too

An interactive board for working on Jane Street's puzzle
[It's a Metric, Too](https://www.janestreet.com/puzzles/current-puzzle/).
It doesn't contain a solution.

Open `index.html` in a browser. No build step and no install.

- Click or drag along grid lines to draw state borders.
- States are coloured automatically, and capitols are found from each state's symmetry.
- Clues turn green when the cheapest travel cost to a capitol matches, and red otherwise.
- Rest the mouse on a cell to see its cheapest route to a capitol.
- **Browse states** lists every symmetric shape of a given size, optionally only those with a capitol.
- Click inside a cell to mark it **Solve** or **Constraint** and choose its allowed state sizes and travel costs.
- **Find solve** lists every set of symmetric states that covers the Solve cells, follows the drawn walls, and keeps every Solve cell, and every Constraint cell it covers, within its limits. Step through the results with the arrows (or ← →), keep one as walls, or clear them.
- Switch between the 11×11 puzzle and the 5×5 example from the puzzle page.

Walls are saved in your browser's local storage.

`metric-too.html` is the same page without the outer HTML wrapper; it's the source for the hosted Claude artifact version.
