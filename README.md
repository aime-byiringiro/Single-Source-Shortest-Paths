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
   - Shortest-paths algorithms typically rely on the property that a shortest path between two verices contains other shortest paths within it.
4. _can shortest paths contain negative weights? Can shortest paths contain cycles?_
   - Yes, a shortest path can contain negative weights, given with no negative weight cycles. 
   - If there negative weight cycles, you can not have a shortest path since there will always be the next shortest path until - ∞
   - Shortest path can not contain cycle since removing the cycle from eh path produces a pth with the same source and destination vertices and a lower path weight. 
5. What is the triangle inequality? What does the term “relaxing an edge” mean with respect
to finding the shortest path.
- Let G = (V,E) be a weighted, directed graph with weight function w: E --> R and source vertex s. Then, all edges (u,v) ∊ E, &(s,v) ≤ &(s,v) + w(u,v)
-  [Video](https://www.youtube.com/watch?v=fqcSpN9sLTo)
6. Know and understand the Bellman-Ford algorithm. Complexity?
   - Relax edges n-1 time from the root vertex.  Look at the director of Bellman-Ford
7. Be able to trace through an example of the Belman-Ford algorithm similar to the example in
class and in the textbook. **TBD**
8. Know and understand Dijkstra’s algorithm. Complexity?
   - View the Dijjstra's directory. 

   




