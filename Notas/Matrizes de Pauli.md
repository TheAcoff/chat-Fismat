---
Endereço: UFJF-Disciplinas-
Relacionado:
  - "[[Física Matemática]]"
---
É um conjunto de matrizes Hermitianas e Unitárias.
$$
\sigma_{x} = \begin{pmatrix}0 &1 \\ 1 & 0\end{pmatrix}
$$
$$
\sigma_{y} = \begin{pmatrix}0 &-i \\ i & 0\end{pmatrix}
$$
$$
\sigma_{z} = \begin{pmatrix}1 &0 \\ 0 & -1\end{pmatrix}
$$
**Forma geral**
Escrevemos na forma geral usando o [[Delta de Kronecker]]
$$
\sigma_{j} = \begin{pmatrix}\delta_{j3} & \delta_{j1}-i\delta_{j2} \\ \delta_{j1} + i\delta_{j2} & -\delta_{j3} \end{pmatrix}
$$

# 1   Propriedades
## 1.1   Operações Entre
$$
\sigma_{i}^{2} = \mathbb{1}
$$
## 1.2   Propriedades Matriciais
**Determinante**
$$
det(\sigma_{i}) = -1
$$
**Traço**
$$
Tr(\sigma_{i}) = 0
$$
## 1.3   Comutador e Anticomutador
**Comutador**
$$
[\sigma_{j},\sigma_{k}] = 2i \epsilon_{jkl} \sigma_{l}
$$
Essa relaçao faz com que as matrizes de Pauli sejam geradoras de uma representação da [[Algebra de Lie]] e das álgebras [[su(2)]] e [[so(3)]]

**Anticomutador**
$$
\{\sigma_{j},\sigma_{k}\} = 2 \delta_{jk} \mathbb{1}
$$
Essa relaçao faz com que as matrizes de Pauli sejam geradoras de uma representação da álgebra de Clifford para o $\mathbb{R^{3}}$. 