#definition 
### Types
- $\{C_n(X),\partial_n\}$ : Chain complex

### Definition
Create the following augmented chain complex 
$$
\cdots\longrightarrow C_2(X)\xrightarrow{\partial_2}C_1(X)\xrightarrow{\partial_1}C_0(X)\xrightarrow{\varepsilon}\mathbb{Z}\to0
$$
where $\varepsilon : \sigma \mapsto 1$, then the reduced homology groups are the following
$$ \tilde H_n(X) =
\begin{cases}
\text{ker } \partial_n / \text{im } \partial_{n+1} & \text{for } n \geq 1 \\
\text{ker } \partial_1 / \text{ im } \varepsilon & \text{ for } n =0
\end{cases}
$$
Thus, $\tilde H_n(X) \cong H_n(X)$ for $n \neq 0$ and $H_0(X) \cong \tilde H_n(X) \oplus \mathbb Z$. 