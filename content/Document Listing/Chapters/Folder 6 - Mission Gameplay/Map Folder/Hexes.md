---
{"publish":true,"created":"2025-08-07T17:37:26.347+02:00","modified":"2025-08-07T18:41:47.064+02:00","cssclasses":""}
---

Hexes hold a number of variables, describing how they interact with the pilots, NPCs, projectiles and obstacles.


| Hex Variable | Description   |
| ------------ | ------------- |
| [[Document Listing/Chapters/Folder 6 - Mission Gameplay/Map Folder/Hexes Folder/Space]]    | 
Technically hovering above the grid of some other hex, it is a 10-metre column of empty space. Space can be stacked indefinitely unless the map has some sort of ceiling. Most commonly used for flying.
- If you enter an air hex during ground movement, the movement ends and you begin to fall unless you flew.
- If you begin your turn in an air hex, you begin to fall.    |
| [[Document Listing/Chapters/Folder 6 - Mission Gameplay/Map Folder/Hexes Folder/Occupied]] | 
Holds any one Pilot, Frame, NPC, obstacle, or some large entity. Stops being occupied when the unit/entity moves out of the hex, or is destroyed enough to not count as obstacle anymore.
- Cannot be entered during movement. |
| [[Document Listing/Chapters/Folder 6 - Mission Gameplay/Map Folder/Hexes Folder/Terrain]]  | 
Traversable, free of obstacles space on the "ground level", assigned a certain height.
- You cannot fall or move below a terrain hex.
- If the difference in height between adjacent terrain hexes is higher than 10 metres, you cannot enter the adjacent hex.  |
| [[Document Listing/Chapters/Folder 6 - Mission Gameplay/Map Folder/Hexes Folder/Prop]]     | 
Treated identically to a terrain hex, except it can be destroyed with enough effort, and can lie atop another hex type (typically terrain). 
- If a unit occupies a destroyed prop, it begins to fall.

Destructible props have a single value, from 1 upward. The value equals the prop's integrity, as well as all defences equally. The value is typically assigned by the handler.     |
