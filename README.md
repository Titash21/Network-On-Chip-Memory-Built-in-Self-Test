# Network-On-Chip-Memory-Built-in-Self-Test

The number of computing resources in single-chip has enormously increased. 
The resources on a chip can be a CPU, memory core, custom IPs, etc. 
The challenging issue is the interconnection between each of them creates complex wiring which results in area and power overhead. 
We mainly concerned on testing of the memory cores in the Network on Chip system.

Algorithm
1. User decides how many blocks are needed ie how many memory cores are required to be placed.
2. User decides the dimension of the rectangle to be partitioned.
3. Based on the dimensions and choices of either vertical partition or horizontal partition the rectangle is partitioned into desired no. of blocks each with a core no. or partition no.
4. The memory cores are then mapped to a matrix whose dimensions are chosen by the user. For 10 blocks ay a 3*4 matrix will be chosen where there will be two blanks for the BIST CONTROLLERS
5. The central blocks with 4 neighbours are numbered as 31, the side is numbered as 21, the corners is numbered as 11.
