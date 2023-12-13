# Single-Source-Shortest-Paths

1. What is a shortest path and what is the shortest-path problem
   - A shortest path from vertex u to vertex v is any path p with weight w(p) = &(u,v), where 
   - &(u,v) is the shortest-path weigh from u to v. 
   - adf 
   - 
2. _What are some of the variants of the single-source shortest path problem? Given a graph G = (V,E), find a shortest path from a given_
source vertex s ∊ V to every vertex u ∊ V.
   - Single-destination shortest-paths problem: Finding the shortest path from every vertex in the graph to all vertices in the graph 
   - Single-pair shortest-path problem: Finding the shortest path vertex v to u.  
   - All pairs shortest-paths problem: Involves determining the shortest paths and distances between every possible pair of vertices in the graph.
3. _Know and understand the section in our text on the optimal substructure of a shortest path._
   - Shortest-paths algorithms typically rely on the property that a shortest path between two vetices contains other shortest paths within it.
4. _can shortest paths contain negative weights? Can shortest paths contain cycles?_
 - Yes, a shortest path can contain negative weights, given with no negative weigt cycles. 
 - If there negative weight cycles, you can not have a shortest path since there will alway be the next shortest path until - ∞
 - Shortes path can not contain cycle since removing the cycle fromt eh path produces a pth with the same source and destination vertices and a lower path weight. 
         
   



