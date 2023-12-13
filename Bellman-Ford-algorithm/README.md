        # BELLMAN-FORD (G, w,s)
        1. INITIALIZE-SINGLE-SOURCE(G,S)
           2. for i = 1 to  |G.V| - 1 
           3.     for each edge (u,v) ∈ G.E 
           4.        RELAX(u,v,w)
           5. for each edge (u,v) ∈ G.E 
           6.     if v.d > u.d + w(u,v) 
           7.       return FALSE  
           8. return TRUE
    
       # REALAX (u,v, w)
       1. if v.d > u.d + w(u.v)
          2.     v. d = u.d + w(u.v)
          3.     v.∏ = u

       # INITIALIZE-SINGLE-SOURCE(G,s)
       1. for each vertex v ∈ G.V
          2.    v.d = ∞
          3.    v.∏ = NIL
          4. s.d = 0
