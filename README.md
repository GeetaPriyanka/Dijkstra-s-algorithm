# Dijkstra-s-algorithm

A  network  that  follows  the  OSPF  (Open  Shortest  Path  First)  protocol  routes  packets  using 
Dijkstra’s shortest path algorithm.  The criteria used to compute the weight corresponding to a link can 
include the time taken for data transmission, reliability of the link, transmission cost, and available  
bandwidth.   Typically  each  router  has  a  complete  representation  of  the  network  graphand 
associated information available to it.
For the purposes of this project, each link has associated with it the transmission time taken for 
data to get from the vertex at one end to the vertex at the other end.  I have computed the best path
using the criterion of minimizing the total time taken for data to reach the destination.The shortest 
time path minimizes the sum of the transmission times of the links along the path.

Five tasks in this project: 
building the initial graph, 
updating the graph to reflect changes,
finding the shortest path between any two vertices in the graph based on its current state, 
printing the graph, and 
finding reachable sets of vertices.



Programming Language used- Java
Compiler version - JDK 1.8

Following Classes are used in the program:

Graph - Class which reads the file which is passed to it and performs all the operations on the graph.
GraphException - Handles any RuntimeException thrown by the Graph.
Vertex - Class which handles all the information related to the vertex.
Edge - Class which stores the information related to the Egde.
Path - Class which stores the name of the Path.
Pair – Class which stores the String Pairs.
Minheap – Class which implements the minheap for the Dijkstra’s Algorithm.

Data structures used:
HashMap --> To keep track of the vertices
Linked list --> To store the data related to edge(destination name, edge weight)
TreeSet --> Stores the visited nodes   


Steps for running Graph.java thorugh Eclipse -->

Go to Eclipse -> Open Graph.java -> Click on Run -> Run Configurations -> Arguments -> In the Program Arguments tab, give the 3 files with a space between them.

Example: C:\Users\Desktop\network.txt C:\Users\Desktop\queries.txt C:\Users\Desktop\output.txt

Click on 'Apply' and then click on 'Run'.

Output will be stored in --> output.txt specified through the command line. 

