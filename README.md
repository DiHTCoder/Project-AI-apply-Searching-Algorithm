# Project-AI-apply-Searching-Algorithm
Describe the problem: A person will start from his home to a cafe to meet his partner. That person does not know the way to that cafe but has the address of that cafe. And when he started going, his car only had n liters of gasoline. When traveling 1km, that person's car only has n - 1 liter of gasoline left. And on the way there will be dead-end alleys, impassable walls. If that person runs out of gas but still can't go to the cafe, the meeting with the partner is considered canceled. With 4 algorithms BFS, DFS, DLS, A* let's find the algorithm that helps that person reach the cafe.
Problem of the problem:
- Initial state is a coordinate on the matrix start = (x1, y1)
- Goal state is the destination end = (x2, y2)
Possible actions are actions that the person can take.
Problem representation: The problem will be represented by a matrix of size N * N. In which the white cells are walkable cells, the yellow squares represent the starting place of the riders. When meeting a partner, red will represent the destination as a cafe, black will represent the idea that (dead end alley) cannot pass through these black cells. When that person finds the way, we will color those boxes with green, and the path to the destination will be colored blue.
Technology used: In this project, our team will use python language technology and python libraries to implement this project. Libraries used in this project include:
Tkinter library: This library is a python language library used to create Graphical User Interface (GUI) applications. This library is a popular library for creating GUIs in python because it is very simple and accessible. To install tkinter we will use the command pip install tkinter.
Some other libraries are available when we install python.
Algorithms used in the project
- BFS: Breadth First Search (Breadth Search)
- DLS: Depth Limit Search
- A*(A Star)
