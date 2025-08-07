---
{"publish":true,"created":"2025-08-07T17:37:26.325+02:00","modified":"2025-08-07T18:41:47.047+02:00","cssclasses":""}
---

Distances between points of interest always use the grid, starting from the hex occupied by the first point of interest, to a hex occupied by the second point of interest.
- In order to measure horizontal distance, begin from the first point's' hex, and move to the adjacent hex. Repeat this process until you reach the second point's hex. The shortest possible number of repeats that connects these in a path is the distance.
- In order to measure vertical distance, calculate the difference in elevation between the two points of interest, in 10-metre increments.
- In order to measure a three-dimensional distance, sum horizontal and vertical distances between the points of interest.