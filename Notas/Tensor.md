Tags:[[Física Matemática]]

Uma transformação do tipo:
$$\begin{aligned}
T: \mathbb{V}^m &\rightarrow \mathbb{R}^n 
\end{aligned}$$
Definindo a notação: índices repetidos indicam soma.
Podemos identificar as componentes de um vetor olhando para a sua regra de transformação.
# 1   Função Escalar
Def.: Uma função $\varphi(x)$ é considerada uma função escalar se for invariante sobre uma mudança de coordenadas
$$
\varphi(x) = \varphi'(x') \Label[1]{escalar}
$$

# 2   Tensor Contravariante de Rank n
Def.: São contravariantes de rank $n$ se os objetos se transformam em $x^i \rightarrow x'^i$, tal como:
$$
A^{i'_{1}...i'_{n}} = \frac{\partial x^{i'_1}}{\partial x^{j_1}}...\frac{\partial x^{i'_n}}{\partial x^{j_{n}}}A^{j_{1}...j_{n}} \Label[2]{Tensorcontra}
$$
# 3   Tensor Covariante de Rank n
Def.: São covariantes de rank $n$ se os objetos se transformam em $x^i \rightarrow x'^i$, tal como:
$$
A'_{i_{1}...i_{n}} = \frac{\partial x^{j_1}}{\partial x^{i'_1}}...\frac{\partial x^{j_{n}}}{\partial x^{i'_n}}A_{j_{1}...j_{n}} \Label[3]{Tensorcov}
$$
# 4   Tensor misto
Vale também para tensores mistos:
$$
B^{j'_{1}...j'_{m}}{}_{i'_{1}...i'_{n}} = \Lambda B^{k'_{1}...k'_{m}}{}_{l'_{1}...l'_{n}} \Label[4]{}
$$
Em que $\Lambda$ é a matriz de transformação constituída das derivadas parciais

# 5   Operações Entre Tensores
- *Soma*: Ocorre entre tensores do mesmo tipo:
$$
(A+B)^{i_{1}...i_{n}}{}_{j_{1}...j_{m}} = A^{i_{1}...i_{n}}{}_{j_{1}...j_{m}} + B^{i_{1}...i_{n}}{}_{j_{1}...j_{m}} \Label[5]{Soma}
$$
- *Multiplicação por um escalar*: Atua em todas as componentes do Tensor
$$
(\alpha A)^{i_{1}...i_{n}}{}_{j_{1}...j_{m}} = \alpha \cdot A^{i_{1}...i_{n}}{}_{j_{1}...j_{m}} \Label[6]{multesc}
$$
- *Multiplicação entre tensores*: Pode ser feito por tensores de qualquer tipo (exemplo: $(m,n)\cdot(t,s)$. Resulta em um tensor $(m+t,n+s)$.
$$
A^{i_{1}...i_{m}}{}_{j_{1}...j_{n}}\cdot C^{k_{1}...k_{t}}{}_{l_{1}...l_{s}} = D ^{i_{1}...i_{n}}{}_{j_{1}...j_{m}}{}^{k_{1}...k_{t}}{}_{l_{1}...l_{s}} \Label[7]{}
$$
- *Contração de índices*: Índices repetidos se contraem em uma multiplicação. Exemplo:
$$
A_{ijk}\cdot B^{lj} = \sum\limits_{j=1}^{3}A_{ijk}B^{lj}  \Label[8]{}
$$

# 6   Simetria de Tensores
- *Tensor simétrico*: exemplo: um tensor simétrico em $i$ e $j$
$$
A^{ijk...}=A^{jik...} \Label[9]{}
$$
- *Tensor absolutamente simétrico*: simétrico em todos os índices
- *Tensor antissimétrico*:
$$
A^{ij} = -A^{ji} \Label[10]{}
$$
- *Tensor absolutamente antissimétrico*: Segue a mesma ideia do absolutamente simétrico
>[!note] Exemplo
>O Tensor que em coordenadas cartesianas é representado pelo símbolo de Levi-Civita
## 6.1   Levi-Civita
Propriedade de multiplicação:
$$
E^{abc}E_{dec} = \delta^{a}{}_{d}\delta^{b}{}_{e} - \delta^{a}{}_{e}\delta^{b}{}_{d}
\Label[11]{multLevi}
$$
utilizando $\Ref[11]{multLevi}$ :
$$
E^{abc}E_{abc} = 6
\Label[]{levisix}$$
# 7   Álgebra Vetorial: Alguns cálculos
Produto vetorial:
$$
[V,W] = E_{abc}\cdot V^{a} \cdot W^{b} \cdot \hat{n}^c
\Label[]{}$$

Para coordenadas curvilíneas, ver livro no cap 4, pag 61.
# 8   Derivada covariante
Quando tratamos de derivadas, temos que levar em consideração as transformações entre referenciais. Com isso, surge a derivada covariante. Seguimos então os passos:
1. Transformar um tensor para coordenadas cartesianas
2. Tomar a derivada parcial em relação às cartesianas
3. Transformar para o sistema original usando a regra de transformação
Algumas formas de escrever:
$$
\nabla_{i}T_{j} = \partial_{i}T_{j} - \Gamma^{k}_{ji}T_{k}
\Label[]{}
$$
Em que $\Gamma$ é o [[Símbolo de Christoffel]]
$$
\nabla_{i}S^{j} = \partial_{i}S^{j} + \Gamma^{j}_{ki}S^{k}
\Label[]{}
$$
então, de forma geral, uma derivada covariante é dada por:
$$\begin{aligned}
\nabla_{i} T^{j_{1}j_{2}...}{}_{k_{1}k_{2}...} &= \partial_{i} T^{j_{1}j_{2}...}{}_{k_{1}k_{2}...} + \Gamma^{j_{1}}_{li}T^{lj_{2}...}{}_{k_{1}k_{2}...}+\Gamma^{j_{2}}_{li}T^{j_{1}l...}{}_{k_{1}k_{2}...} + ...\\
&-\Gamma^{l}_{k_{1}i}T^{j_{1}j_{2}...}{}_{lk_{2}...} - \Gamma^{l}_{k_{2}i}T^{j_{1}j_{2}...}{}_{k_{1}l...}-...
\end{aligned} \Label[]{derivCov}$$
# 9   Relações entre operadores vetoriais
- *[[Divergente]]*:
$$
\nabla \cdot \vec{V} = \partial_{a}V^{a} 
\Label[]{}
$$
- *[[Gradiente]]*:
$$
\nabla \Psi = \hat{n}^{a} \partial_{a} \Psi
\Label[]{}
$$
- *[[Laplaciano]]*:
$$
\Delta = g^{ij} \nabla_{i}\nabla_{j}
\Label[]{}
$$
- *[[Rotacional]]*:
$$
E^{abc}\hat{n}_{a} \partial_{b} V_{c}
\Label[]{}
$$
- *Nabla*:
$$
\nabla = e^{i}\nabla_{i} = g^{ij}e_{j}\nabla_{j}
\Label[]{}
$$
Para os operadores entre diferentes coordenadas, devemos transformar o nabla. Por exemplo, o divergente em coordenadas esféricas. Para isso, ver o livro texto no cap 7 pág 73.

