    # BELLMAN-FORD (G, w,s)
    1. INITIALIZE-SINGLE-SOURCE(G,S)
       2. for i = 1 to  |G.V| - 1
       3.    for each edge (u,v) ∈ G.E
       4.       RELAX(u,v,w) 
       5. for each edge (u,v) ∈ G.E
       6.    if v.d > u.d + w(u,v)
       7.       return FALSE 
       8. return TRUE