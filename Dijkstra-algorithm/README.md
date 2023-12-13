    # DIJKSTRA(G,w,s)
    1. INITIALIZE-SINGLE-SOURCE(G,s)
       2. S=⦰
       3. Q=⦰
       4. for each vertex u ∈ G.V
       5.    INSERT(Q,u)
       6. while Q ≠ ⦰ 
       7.    u = EXTRAT-MIN(Q)
       8.    S = S ∩ {u}
       9.    for each vertex v in G.Ad[u]
       10.       RELAX(u,v,w)
       11.       if the call of RELAX decreased v.d
       12.            DECREASE-KEY(Q,v,v.d)
    # REALAX (u,v, w)
       1. if v.d > u.d + w(u.v)
          2.     v. d = u.d + w(u.v)
          3.     v.∏ = u

       # INITIALIZE-SINGLE-SOURCE(G,s)
       1. for each vertex v ∈ G.V
          2.    v.d = ∞
          3.    v.∏ = NIL
          4. s.d = 0
# Running time O(V^2 + E) = O(v^2)