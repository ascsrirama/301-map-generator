# 301 Map Generator

A COMPSYS 301 map visualiser and path generator. Single-file web page, no build step.

**Live:** <https://ascsrirama.github.io/301-map-generator/>

## Usage

1. Pick a click mode (**Start**, **Add visit**, **Goal**) and click path cells on the grid.
2. Click **Generate path** to route through the visits in order, using A* with 4-directional moves. Tick **end at goal** to finish at the goal.
3. Copy the generated directions (U/D/L/R) or the C code (`MAP_START_*`, `MAP_GOAL_*`, `food_list`).

You can also paste existing C code into the C code box to load its start, goal and food points onto the map. To change the map itself, open **Edit map** (rows of `1`/`0`, where `1` is a path cell).

