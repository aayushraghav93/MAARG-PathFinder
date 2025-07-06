MAARG: Implementing Data Structures for Efficient Geolocation Services
Features

1. Add Cities

Users can add cities to the map by providing a unique city ID and a city name.

2. Add Paths
   
Connect cities with paths, specifying the distance between them. Users can also set the availability of the path.

3. Display Graph

Visualize the graph with cities and distances to understand the spatial layout.

4. Remove Cities

Remove cities from the map, updating the graph accordingly.

5. Find Shortest Path
   
Utilizes Dijkstra's Algorithm to find the shortest path between two cities. Displays both the path and total distance.

6. Persistence
   
The graph state is serialized to a file (graph.ser) for persistent storage between program runs.


Data Structures:-

7. LocationGraph
   
Represents the map using an adjacency matrix to store distances between cities.

Uses arrays to efficiently manage cities and their paths.

8. City
   
Represents a city with a unique ID and a name.

9. Path
    
Represents a path between two cities with distance and availability information.


Getting Started:-

10. Compile and Run
    
Ensure you have Java installed on your machine.


Compile and run the Main class to launch the Location Pathfinder.

11. Menu Options
    
Follow the on-screen menu to interact with the application.
Options include:

Adding cities

Adding paths

Displaying the graph

Removing cities

Finding the shortest path
