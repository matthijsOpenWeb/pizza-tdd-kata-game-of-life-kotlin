# pizza-tdd-kata-game-of-life-kotlin
Kata for tdd: conways game of life - kotlin based


# The Kata
**Game of Life**

You should write a program that can accept an arbitrary grid of cells, and will output a similar grid showing the next generation based on the given rules.

The rules
1. Any live cell with fewer than two live neighbours dies, as if caused by underpopulation.
2. Any live cell with more than three live neighbours dies, as if by overcrowding.
3. Any live cell with two or three live neighbours lives on to the next generation.
4. Any dead cell with exactly three live neighbours becomes a live cell.

**Clues**

_The input starting position could be a text file that looks like this:_

Generation 1:  
4 8  
........  
....#...  
...##...  
........

_And the output could look like this:_

Generation 2:  
4 8  
........  
...##...  
...##...  
........

**Suggested Test Cases**

Make sure you have enough coverage of edge cases - where there are births and deaths at the edge of the grid.

