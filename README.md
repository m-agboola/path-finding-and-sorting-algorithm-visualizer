# Path Finding and Sorting Algorithm Visualizer

# Sorting
Sorting algorithms are classical algorithms for ordering an array of data. Some are more suited for some use case than other. We are going to be visualizing some of the 5 most popular sorting algorithms.
They are Merge Sort, Quick Sort, Selection Sort, Insertion Sort and Bubble Sort.

There are some python scripts which can visualize several famous sorting algorithms and generate the animations via Pygame. 

running `python visualiser.py` runs the sorting algorithms with the test cases given while also monitoring time taken for the completion of the algorithms

# A* Path Finding Algorithm

An A* path finding algorithm is used to find the shortest distance between two given points on a graph. A-Star search, unlike other path-finding algorithm such as Dijkstra's algorithm doesn't brute force search for every node to find a path, but use a  heuristic function that guides which path is essential for accomplishing the task.

The formula used is `F(n) = G(n) + H(n)`
where,
- G(n) => The G score is the shortest distance between start node to the current node.
- H(n) => The H score is the heuristic the estimates the distance of end node from the start node.
- F(n) => The F score is the addition of both G score and H score.

You can learn more about A-star path finding algorithm [here](https://en.wikipedia.org/wiki/A*_search_algorithm).

