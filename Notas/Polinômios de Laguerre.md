---
Relação:
  - "[[Funções Especiais]]"
Referências: []
---
# 1   Laguerre
Solução da equação diferencial:
$$
xy'' + (1-x)y' +ny = 0
$$
Podem ser definidos pela Fórmula de Rodrigues:
$$
L_n(x) = \frac{e^{x}}{n!} \frac{d ^n}{dx ^n} (e ^{-x} x ^{n}) = \frac{1}{n!}\left(\frac{d}{dx}-1\right)^{n} x ^{n}
$$
---

# 2   Laguerre Associado
Solução da equação diferencial:
$$
xy'' + (\alpha+1-x)y' +ny = 0
$$
Definimos os dois primeiros como:
$$\begin{matrix}
L_{0}^{(\alpha)}(x) = 1 \\
L_{1}^{(\alpha)}(x) = 1+\alpha-x
\end{matrix}$$
Temos uma fórmula de recorrência para um $k\geq1$:
$$
L_{k+1}^{(\alpha)}(x) = \frac{(2k+1+\alpha-x)L_{k}^{(\alpha)}(x)-(k+\alpha)L_{k-1}^{(\alpha)}(x)}{k+1}
$$
então, a fórmula de Rodrigues fica:
$$\large
L_n^{(\alpha)}(x) = \frac{x^{-\alpha}e^{x}}{n!} \frac{d ^n}{dx^n} (e ^{-x} x^{n+\alpha}) = \frac{x^{-\alpha}}{n!}\left(\frac{d}{dx}-1\right)^{n} x ^{n+\alpha}
$$

## 2.1   Fórmulas de Recorrência

