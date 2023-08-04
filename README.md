> [!NOTE]
> As this is a project developed for the course ECE297 at the University of Toronto, the code for the project is not available.

# ByteMap
A GIS Program coded with C++ and using the OpenStreetMap API. This was a project produced by a team of 3 for ECE297 (Software Design) at the University of Toronto

# Description

As can be seen from the demo available [here](https://www.youtube.com/watch?v=MmpvzcfI8Kg), this program is a GIS system similar to that of Google Maps designed for couriers.

The programs features include:

* Graphical display of a multitude of cities across the world, including all of its geographical features.
* Dynamic zooming with conditional rendering.
* Interactable features with graphical descriptions including: intersections, restaurants, cafes & warehouses.
* Highlighting of POI dense areas.
* Find the fastest path between any two points using the A* algorithm dependent on the mode of travel chosen by the user.
    * Additionally, provides directions both textually and graphically to the user.
* Autofill search bar for intersections, directions & maps.
* Applied solution to the traveling salesman problem

Some of the programming concepts used include:

* Optimizing runtime through the use of the C++ standard library data structures such as vectors, unordered maps, and many more.
* A* algorithm to find the fastest path between any two points on the map.
* Multi-destination Dijkstra's algorithm (illustrated in Figure 1.), greedy algorithm and 2-opt optimization to solve applied traveling salesman problem.
* Multithreading

![plot](Multi-DestinationDijkstra.jpg)
Figure 1. Graphical Representation of Multi-Destination Dijkstra's Algorithm
