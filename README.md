# expense_8_puzzle
This is a programming project to build an agent that solves a modified version of the 8 puzzle problem, called the Expense 8 puzzle problem.


The code is an implementation of the 8-puzzle problem using various search algorithms like A*, BFS, DFS, UCS, Greedy, IDS, and DLS.

The input and output files are taken from the command line arguments, and the input file consists of a 3x3 matrix representing the initial state, and the output file consists of a 3x3 matrix representing the goal state. The code takes the input file and converts it into a matrix and creates a Node object with the given initial state matrix. The goal state is also converted into a matrix.

The program then has a Node class with properties data, parent, heuristic, depth, move, and cost. The methods defined include hueristic_2, copy_matrix, make_child, zero_position, position, and print_data_in_matrix. These methods are used in the search algorithms.

The search algorithms used are A*, BFS, DFS, UCS, Greedy, IDS, and DLS. The search algorithm used is determined by the command line argument passed. For DLS, a depth limit is also asked from the user. Each search algorithm is implemented differently, but all the algorithms use the same Node class and methods.

The program outputs the cost of the solution, the depth of the solution, the sequence of steps taken, the number of nodes popped, the number of nodes expanded, the number of nodes generated, and the maximum size of the fringe. The output is written to a file passed in the command line argument. The program also has an option to dump the search tree to a file by passing a True value in the command line argument.
