---
Relacionado:
  - "[[Vetor]]"
---
Definições iniciais:
$$
\begin{aligned}
A = ae^{-i\omega t} = \alpha_{1} + i\beta_{1} \\
B = b e^{-i\omega t} = \alpha_{2} + i\beta_{2}
\end{aligned}$$
---
- Um vetor complexo tem componentes complexas:
$$
\vec{W} = \vec{u}(\vec{r},t) + i\vec{v}(\vec{r},t)
$$

---
# 1   Parte Real
- Tirando o divergente da parte real, a solução é trivial:
$$
Re\{\nabla \cdot \vec{w}\} = \vec{\nabla} \cdot \vec{u}
$$
- Encontrar os coeficientes:
$$
\begin{aligned}
\alpha_{1} = \frac{1}{2}(A + A^{*}) \\
\beta_{1} = \frac{1}{2i}(A-A^{*})
\end{aligned}
$$
- Tirando as partes reais, temos um produto interno:
$$
Re\{AB^{*}\} = \frac{1}{2}(A\;B^{*}+A^{*}B)
$$
e
$$
Re\{A\;B^{*}\} = 2<Re\{A\}\;Re{B^{*}}>
$$
- Aplicando operadores vetoriais:
$$
\begin{aligned}
<Re\{F\}\cdot Re\{G\}> = \frac{1}{2} Re\{F_{0}\cdot G_{0}^{*}\}\\
<Re\{F\}\times Re\{G\}> = \frac{1}{2} Re\{F_{0}\times G_{0}^{*}\}
\end{aligned}
$$

