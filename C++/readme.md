# Labyrinth
## Problem Statement
Your applications should find the largest pathway moving only between holes, reading
the labyrinth schema from a txt file, using only standard libraries of c++11. All the lines in
the input file will have the same number of elements. Your application should save the
schema of the largest detected pathway, overwriting the holes (.) with the order in which
the hole has been visited.
## Approach
1. FInd the largest path using BFS
2. Apply DFS recursively to output the path on longest path
## Screenshots of Output
<img src="https://github.com/zenithexpo/Challenges/blob/main/C%2B%2B/screenshots/Screenshot%20from%202021-03-30%2023-46-12.png">
