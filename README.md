# Rising-Waters
  Sea levels have been rising globally. Natural disasters cause the waters to increase at a smaller scale and for shorter amounts of time. Urban planners for future cities and development, as well as governments and citizens of existing cities, need to know which areas are at risk of being flooded when the water level increases. This Java program uses recursion, stacks, and queues to evaluate what happens to a given terrain when the waters are rising.

Input:
The program expects three command line arguments. The first one is the name of the input file that contains a description of the grid, water sources, and the height of the water to simulate. The second one determines which algorithm should be used to simulate the rising waters. The possible values are stack, queue, and recursive. The third command line argument indicates if the program should display visualization as the simulation progresses. The possible values are true or false.

Input File:

-Line 1 contains the water height for the simulation.

-Line 2 contains the number of water sources.

-Lines 3 and 4 contain row and column numbers for the first water source and repeat as many times as there are water sources.

-The next line contains the number of rows in the terrain map.

-The next line contains the number of columns in the terrain map.

-All remaining lines contain the actual map(there are as many lines as the number of rows, and each line contains space-separated floating point numbers).

For example, this file has the water level reaching 2 feet (first line), one water source at grid point { 0, 0 } (lines 2 to 4), and the terrain map that is 7 by 7 grid point (lines 5 to 13):

2

1

0

0

7

7

0 1 2 3 4 2 1

1 2 3 4 5 4 2

3 4 5 6 6 5 4

2 4 5 7 5 3 2

1 2 4 5 3 2 1

0 1 2 3 1 1 1

0 0 1 2 1 1 1
