tags: [[Geometria]]

---
Uma abordagem via [[Teoria de Grupos]], é utilizar uma transformação linear, uma vez que $\vec{r}' = \vec{r} - \vec{T}$ não possui essa estrutura. Então, buscamos algo do tipo:
$$
\vec{R}\;' = \vec{T}\vec{R}
$$
em que:
$$
R := \begin{pmatrix} x_1 \\ x_2 \\ x_3  \\ 1\end{pmatrix}
$$
e a ultima entrada é fixa para qualquer operação. E:
$$
T = \begin{pmatrix}1&0&0&-T_1 \\ 0&1&0&-T_2 \\ 0&0&1&-T_3 \\0&0&0&1 \end{pmatrix}
$$
e sua inversa:
$$
T^{-1} = \begin{pmatrix}1&0&0&T_1 \\ 0&1&0&T_2 \\ 0&0&1&T_3 \\0&0&0&1 \end{pmatrix}
$$