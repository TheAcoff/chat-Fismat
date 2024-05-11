---
Relacionado:
  - "[[Física Matemática]]"
---
$$
\begin{aligned}
\mathbb{M}_{n \times n} &\rightarrow \mathbb{K}\\
A &\mapsto Tr(A) = \sum\limits_{i} a_{ii}
\end{aligned}
$$
Tal que $\mathbb{K}$ é um [[Corpo|corpo]].
# 1   Propriedades básicas
- O traço é linear:
$$
Tr(\alpha A + \alpha B) = \alpha \; Tr(A+B) = \alpha(Tr(A)+Tr(B))
$$
- Traço da transposta
$$
Tr(A) = Tr(A^{\mathsf{T}})
$$
- Traço do produto
$$
Tr(AB) = Tr(BA)
$$
- Permutação Cíclica
$$
Tr(ABCD) = Tr(BCDA) = Tr(CDAB) = Tr(DABC)
$$
- Traço como soma de autovalores
$$
Tr(A) = \sum \lambda_{i}
$$
---
# Propriedades Adicionais

## Traço e Determinante

Para uma matriz $A \in \mathbb{M}_{2 \times 2}$, a seguinte relação entre o traço e o determinante é válida:

$$
det(A) = \frac{1}{2} [ (Tr(A))^2 - Tr(A^2) ]
$$

## Invariância sob Transformações de Similaridade

Se duas matrizes $A$ e $B$ são similares, ou seja, existe uma matriz invertível $P$ tal que $B = P^{-1}AP$, então elas possuem o mesmo traço:

$$
Tr(A) = Tr(B)
$$

# Código

## Python

```python
import numpy as np

# Criando uma matriz
A = np.array([[1, 2], [3, 4]])

# Calculando o traço
traco_A = np.trace(A)

# Imprimindo o resultado
print(f"O traço da matriz A é: {traco_A}")

