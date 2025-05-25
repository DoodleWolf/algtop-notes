#lemma
### Types
- $x_0$ : point in $A$
- $(X,x_0)$ : [[Pointed space]]
- $A$ : [[Subspace Topology|subspace]]
- $r_t: (X,x_0) \rightarrow (A,x_0)$ : [[Deformation retraction]]
- $i : A \hookrightarrow X$ : inclusion
### Statement
The [[Induced Homomorphism|induced homomorphism]] $i_* : \pi_1(A,x_0) \rightarrow \pi_1(X,x_0)$ is injective.
### Proof
Since [[Retracts induce injections|retracts induce injections]] we know $i_*$ is injective. Let $[\gamma] \in \pi_1(X,x_0)$ be a [[Homotopy Class|homotopy class]], then since $r_t$ is a deformations retract $r_t \circ \gamma$ defines a homotopy $\gamma \simeq r_1 \circ \gamma$ which is a loop in $A$. Thus, $i_*([r_1 \circ \gamma]) = [\gamma]$, so $i_*$ is surjective.
