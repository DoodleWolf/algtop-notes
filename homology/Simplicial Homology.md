#definition 
### Types
- $X$ : [[Topological Space]]
- $\{ \sigma_\alpha \}$ : [[Delta Complex]] structure on $X$

### Definition 
We first define the [[chain complex]] associated with the $\Delta$-complex of $X$. The $n$-chains will be maps $\sigma_\alpha : \Delta^n \rightarrow X$ from the $\Delta$-complex structure. 
We now define the boundary map $\partial_n$ on the abelian free group of the $n$-chains $C^\Delta_n(X)$
$$
\partial_n : C_n^\Delta(X) \rightarrow C_{n-1}^\Delta (X) :  \sigma_\alpha \mapsto \sum_i(-1)^i\sigma_\alpha|[v_0,\cdots,\hat{v}_i,\cdots,v_n]
$$
