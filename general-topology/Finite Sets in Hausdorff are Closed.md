#lemma
### Types
- `X` : [[Hausdorff Space]] 
### Statement
Every finite set in `X` is [[Closed Set|closed]].
### Proof
The finite union of [[Closed Set]]s is the finite intersection of their [[Open Set|open]] compliments which is [[Open Set|open]], so it is enough to prove that a singleton is closed. Let `p` be a point of `X`, then for every $q \ne p$ in `X` we have $V_{q}$ a [[Neighborhood]] containing `q` but not `p`, then $\bigcup\limits_{q\in X - \left\{ p \right\}}V_{q} = X - \left\{ p \right\}$ is the union of [[Open Set]]s which is [[Open Set|open]], and thus its compliment $\left\{ p \right\}$ is closed.