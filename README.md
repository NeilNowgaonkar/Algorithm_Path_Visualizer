
# Algorithm Path Visualizer

Pathfinding algorithms address the problem of finding a path from a source to a destination avoiding obstacles and minimizing the costs (time, distance, risks, fuel, price, etc.). Algorithm Visualization shows a continuous, movie-like presentation of an algorithm’s operations. 

Explaining difficult pieces of algorithms code is a challenge in mathematical and computer education. Providing a view of the algorithms inner working details by visualization of algorithm steps aims at making it more understandable 

# Implemented Pathfinding Algorithms 
#### 1.) Dijkstra's Algorithm :-
This algorithmworks by propogating outwards until it finds the finish and then working its way back to get the path. It uses a priority queue to keep track of nodes that it needs to explore. Each node in the priorty queue is explored and all of its neighbors are added to the queue and once the node is explored it is deleted from the queue.

##### Time Complexity = O(V^2) 
##### Space Complexity = O(V), where V is the total number of vertices.

###
#### 2.) A* Search Algorithm :-
A* Search workds essentially the same as Dijkstra creating  a priorty queue and propogating outwards until it finds the end however, A* builds in a heuristic of distance from any node to the finish. This means that nodes that are closer to the finish will be explored first. This heuristic is built in by sorting the queue according to the hops plus distance until the destination. Although being the best path finding algorithm around, A* Search Algorithm doesn’t produce the shortest path always, as it relies heavily on heuristics / approximations to calculate – h


##### Time Complexity = O(E), where E is the number of edges in the graph
##### Space Complexity = O(V), where V is the total number of vertices.



## Screenshots
Dashboard

![Dashboard](https://github.com/NeilNowgaonkar/Algorithm_Path_Visualizer/blob/main/images/Dashboard.PNG?raw=true)

Example when we visualize using Dijsktra Algorithm

![Dijsktra Example](https://github.com/NeilNowgaonkar/Algorithm_Path_Visualizer/blob/main/images/Dijstra%20Example.PNG?raw=true)

Example when we visualize using A* Algorithm

![A* Search Example](https://github.com/NeilNowgaonkar/Algorithm_Path_Visualizer/blob/main/images/A%20Star%20Example.PNG?raw=true)
