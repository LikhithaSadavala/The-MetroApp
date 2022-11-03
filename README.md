# The Metro App

This is a simple Java program that will take information of the source station and the destination station, of Delhi Metro, from the user and display the fare and shortest metro route to reach the destination. It will also be having a metro map for commuter’s better navigation.

<p align="center">
<img src="demo/first.png" alt="demonstration" height="200" width="750" >  
</p>

<p align="center">
<img src="demo/second.png" alt="demonstration" height="400" width="750" >  
</p>

<p align="center">
<img src="demo/third.png" alt="demonstration" height="100" width="750" >  
</p>

<p align="center">
<img src="demo/fourth.png" alt="demonstration" height="200" width="750" >  
</p>

The concept is implemented utilizing the Graph and Heap data structures. There are nodes and edges in the graph. Nodes represent metro stations and will contain information about that station such as its name, metro corridor, and the lines it connects. Edges (connections between nodes) denote the distance between two stations, and the cost of each edge is equal to the distance between the two connecting stations (nodes).

The shortest path between the source and destination stations is identified using various algorithms such as Dijkstra, breadth-first search, depth-first search, and so on, and the fare is computed based on the total distance between the two stations. Finally, the metro route between the two stations is presented, as well as the total fare.

Graph_M.java cointains all the major code and Heap.java contains heap implementation.


##  REQUIREMENTS

> The project can be run on any online or offline Integrated Development Environment (IDE), such as Eclipse, Netbeans, ideone.com, VSCode, and others. 
> To work on the project, you should have at least basic knowledge of the Java programming language. 
> Knowledge of data structures such as Graph and Heap, as well as algorithms such as Dijkstra, BFS, DFS, and others, is preferred but not required. 
> Finally, a basic comprehension of the Collection framework makes the journey a breeze.
