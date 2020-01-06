# Hex Puzzle Generator/Solver
The hex puzzle consists of 7 puzzle pieces. A puzzle piece is a hexagon with numbers 1-6 inclusive along its edges.  No two puzzle pieces can have the same sequence of border numbers and no puzzle piece can have a number repeat.

This program will continue to generate random sets of puzzle pieces until it finds one that satisfies the above conditions.  When it does, it will attempt to solve it.  If it cannot be solved, it repeats the above process until it does. Then, using file i/o, this program will display all of the moves required to  solve the puzzle at a specified frame-time.

### Compiling
```
g++ -o hexexe Source.cpp HexPieces.cpp
```

### Running
```
./hexexe frame-time
```
where frame-time is in seconds from 0-5 and is the length of time between consecutive frames.