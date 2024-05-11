Na [[Teoria dos Conjuntos]], dado um conjunto $X$, uma topologia $\mathfrak{J}$  é uma coleção de subconjuntos de $X$, que segue as seguintes propriedades:
$$
\begin{aligned}
&i)\phi, X \in \mathfrak{J}\\
&ii)\{A_{\lambda}; \lambda \in L\}; A_{L} \subset \mathfrak{J}, \forall \lambda \Rightarrow \bigcup_{\lambda \in L}A_{\lambda} \in \tau\\
&iii)\bigcap_{i=1}^{n} A_{i} \in \mathfrak{J}
\end{aligned}
$$
$A$ são ditos abertos, $\lambda$ e $L$ são subconjuntos. A coleção de subconjuntos é chamado de **família**

# 1   Definindo uma base
Def.: 
$B$ é uma coleção de subconjuntos de $X$, tal que:
$$
\begin{aligned}
&i) \;\forall x \in X, \exists \; b \in B; x \in B \\
&ii) \; \forall x \in B_{1} \cap B_{2}; B_{1,2} \in B, \exists \; B_{3} \in B; x \in B_{3} \subset B_{1} \cap B_{2}
\end{aligned}
$$
Def.: Topologia gerada por $B$