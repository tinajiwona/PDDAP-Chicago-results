# PDD vs PDDAP — Chicago route playback

Interactive results page for the Chicago case study: drone delivery with public-transit (bus) hitchhiking,
comparing **PDD** (take-off / landing at bus stations only) with **PDDAP** (take-off / landing at arbitrary
points of the bus route).

**Open the page:** https://tinajiwona.github.io/PDDAP-Chicago-results/

The page is self-contained (no external requests). For each case (customers × depot × capacity × battery range) it shows:

- the bus network, customers and the depot;
- per-UAV routes over time: flight, hitch (riding on the bus) and waiting;
- station vs free-point take-off/landing and on-bus battery swaps;
- a per-UAV timeline (Gantt chart), and a sortable table of all cases (objective, flight / hitch / wait, battery swaps, run time).
