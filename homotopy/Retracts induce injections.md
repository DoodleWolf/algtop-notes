#lemma
### Types
- $x_0$ : point in $A$
- $(X,x_0)$ : [[Pointed space]]
- $A$ : [[Subspace Topology|subspace]]
- $r: (X,x_0) \rightarrow (A,x_0)$ : [[Retraction]]
- $i : A \hookrightarrow X$ : inclusion
### Statement
The [[Induced Homomorphism|induced homomorphism]] $i_* : \pi_1(A,x_0) \rightarrow \pi_1(X,x_0)$ is injective.
### Proof
It follows that $r \circ i  = id_{A}$ so when taking the induced homomorphisms 
$$
id_{\pi_1(A,x_0)} = (r \circ i)_* = r_* \circ i_*.
$$
As $id_{\pi_1(A,x_0)}$ is an isomorphism, it follows $i_*$ injective.
