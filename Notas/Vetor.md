Tags: [[Algebra Linear]]

Um vetor é um [[Tensor]] de rank 1

# 1   Cálculos Básicos

Como o vetor é um tensor, segue a lei de transformação de suas componentes:
$$
V^{\alpha} = \frac{\partial x^{\alpha}}{\partial x^\beta}V^{\beta}
$$
Definimos a soma de vetores como:
$$
\vec a + \vec b = \sum\limits_{i}(a_{i}+b_{i}) \hat e_i
$$
Produto escalar:
$$
\vec{a} \cdot \vec{b} = \delta_{ij} a^ib^j 
$$
Produto Vetorial: define um vetor perpendicular e também um valor de área para um plano
$$
\vec{a} \times \vec{b} = (E_{ijk}a^ib^j)^k
$$
em 3D:
$$
=det \begin{bmatrix}
 \hat i&\hat j  &\hat k \\ 
 a_x& a_y &a_z \\ 
 b_x&b_y  &b_z 
\end{bmatrix}
$$
Produto misto: $U\cdot(V\times W)$ (módulo define volume $|U|\cdot(|V|\times W) \cos(\theta)$)
 
## 1.1   Ângulo entre dois vetores
$$\theta=\arccos \frac{V\cdot W}{|V|\cdot|W|}$$
A ideia vem do produto escalar!
