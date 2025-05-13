#lemma
### Types
- `X` : [[Second Countable]] Space
- `I` : Set
- $\left\{ U_{i} \right\}_{i\in I}$ : [[Covering]] of `X`
### Statement
There exists a [[Countable]] [[Refinement of a Covering|refinement]] of $\left\{ U_{i} \right\}_{i\in I}$ for `X`. In other words, `X` is a [[Lindelöf Space]].
### Proof
Let $\mathcal{B}$ be a [[Countable]] [[Basis]] of `X`. let $\mathcal{B}'=\left\{B\in \mathcal{B}, \exists i \in I, B \subset U_{i}\right\}\subset \mathcal{B}$, which is also [[Countable]] because a subset of a [[Countable]] set is [[Countable]]. For $B \in \mathcal{B}'$, denote by $V_{B}$ the set of $\left\{ U_{i} \right\}_{i\in I}$ which contains $B$, we have $\left\{ V_{i} \right\}_{i\in \mathcal{B}'}$ [[Countable]], all left to do is to prove that it is a [[Covering]] too.
Let $x \in X$, then $x \in U_{i}$ for some $i \in \mathbb{N}$, by definition of a [[Basis]], there exists $B \in \mathcal{B}$ such that $x \in B \subset U_{i}$, but this means that $B \in \mathcal{B}'$, so $\exists V_{b}\in \left\{ V_{i} \right\}_{i\in \mathcal{B}'}$ such that $x\in B \subset V_{B}$, thus \exists $V_{b}\in \left\{ V_{i} \right\}_{i\in \mathcal{B}'}$ is a [[Covering]] of `X`.