# digital_life
Combinatorial implementation of one cell in Conway's Game of Life.

Each cell has eight neighbors. Rules:
* A cell is live on the next update if it has three neighbors.
* A cell is live on the next update if it has two neighbors and was live.

The combinatorial solution has two parts: popcount on the neighbors, and implementation of the liveness logic.

Other logic is for clocking the updates (as shown) and initializing the state (not shown).

Also note that I've included connectors for neighbors in the schematic. You'll also need crossover connectors between cells.
