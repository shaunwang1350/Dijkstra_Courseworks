# Dijkstra Algorithm

## Summary
This algorithm was part of COMS W3134 Data Structures Homework. The code includes the following tasks:

* Implement the method `computeAllEuclideanDistances()` which should compute the euclidean distance between all cities that have a direct link and set the weights for the corresponding edges in the graph. Once this works correctly, the correct distances should be displayed in the GUI when clicking on "Compute All Euclidean Distances".

* In the method `doDijkstra(String s)`, implement Dijkstra's algorithm starting at the city with name s. Use the distances associated with the edges. The method should update the `distance` and `prev` instance variables of the `Vertex` objects. You should not use a priority queue to store vertices that still need to be visited. Instead, keep these vertices on a List and scan through the entire list to find the minimum. We are making this simplification (at the expense of runtime) because `java.util.PriorityQueue` does not support the `decreaseKey` operation.

* Implement the method `getDijkstraPath(String s, String t)`, which uses the `distance` and `prev` instance variables of the Vertex objects to find the shortest path between `s` and `t`. This method should be called only after `doDijkstra(String s)` has been called with the start city. The resulting path should be returned as a list of `Edge` objects. Once this works correctly, you should be able to compute and display paths in the GUI.

I did modification to Dijkstra.java only. All other material belongs to courseworks provided by Columbia University W3134 Data Structures in Java.

## Technologies used:
* Java.util
* Java.io
* Java.awt
* Java.swing

## How to compile java file:
* Open windows cmd, then move to the directory which included the java file: <em>"cd @/dijstra_courseworks"</em>
* Run the java GUI: <em>"java Display"</em>