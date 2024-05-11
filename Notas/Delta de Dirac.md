links: [[Funções]]

Def.: É uma função que apresenta uma "explosão no zero"
$$
\delta(x) = \left\{\begin{matrix}
\infty, \; x=0\\
0, \; \forall x\neq 0
\end{matrix}\right.
$$
satisfaz a identidade:
$$
\int_{-\infty}^{\infty}\delta(x)dx = 1
$$

Algumas propriedades:
$$
\int_{-\infty}^{\infty}\delta(x)g(x)dx = g(0)
$$
- Alguma que não sei o nome
$$
\int_{-\infty}^{\infty} \delta(x-x')f(x) = f(x')
$$
- Multiplicação por escalar
$$
\int_{-\infty}^{\infty} \delta(\alpha x) dx = \int_{-\infty}^{\infty}\delta(u)\frac{du}{|\alpha|} = \frac{1}{|\alpha|}
$$
- Translação
$$
\int_{-\infty}^{\infty} f(t)\delta(t-T)d = f(T)
$$
- Simetria
$$
\delta(x-x') = \delta(x'-x)
$$



