This is a new data structure named "Graph1D", it can construct a weighted and undirected graph and sort all the edges in a 1D array (using the formula to convert a 2D coordinate user input to a 1D index).
This data structure only stores the upper-right half of the graph (constructed by adjacency matrix) which saves more than half of the memory. What is more, it converts to a priority queue easily and has a time complexity of O(m log n) when getting the minimum spanning tree (MST) value of the tree.
In general, the user still inputs a 2D coordinate when adding vertices, however, it can be converted to a 1D array automatically (the conversion only costs time complexity of O(1)), saves memory and gets the MST value faster and easier.
