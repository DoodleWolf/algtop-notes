#lemma #todo 
### Types
- `X` : [[Compact Space]]
- `Y` : [[Hausdorff Space]]
- $f : X \to Y$
### Statement
If $f$ is [[Continuity|continuous]], then:
- $f$ is a [[Closed Map]]. 
- if $f$ is surjective, it is a [[Quotient Map]].
- if $f$ is injective, then it is a [[Topological Embedding]].
- if $f$ is bijective, then it is a [[Homeomorphism]].
### Proof
If $A$ is [[Closed Set|closed]] in $X$, then it is [[Compact Space|compact]] by [[Every Closed Subset of Compact is Compact]].
As [[Continuity Preserves Compactness]], $f\left( A \right)$ is [[Compact Space|compact]] in $Y$, thus it is [[Closed Set|closed]] in $Y$ because [[Every Compact Subset of Hausdorff is Closed]]. Thus $f$ is a [[Closed Map]].
The rest of the conditions are the first condition combined with the lemmas:
- [[Open Or Closed Continuous Injections Are Embeddings]].
- [[Open Or Closed Continuous Surjection is a Quotient Map]].
- [[Open Or Closed Continuous Bijections are Homeomorphisms]].