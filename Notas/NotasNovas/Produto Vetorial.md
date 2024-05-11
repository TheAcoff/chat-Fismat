# Produto Vetorial

O [[Vetor|produto vetorial]], denotado por $\vec{a} \times \vec{b}$, é uma operação entre dois [[Vetor|vetores]] em um espaço vetorial tridimensional que resulta em um novo vetor. Esse novo vetor possui as seguintes características:

## 1. Módulo

O módulo do produto vetorial corresponde à área do [[Paralelogramo|paralelogramo]] formado pelos vetores $\vec{a}$ e $\vec{b}$. Matematicamente:

$$
||\vec{a} \times \vec{b}|| = ||\vec{a}|| ||\vec{b}|| \sin(\theta)
$$

onde $\theta$ é o [[Ângulo|ângulo]] entre os vetores $\vec{a}$ e $\vec{b}$.

## 2. Direção

A direção do produto vetorial é perpendicular ao [[Plano|plano]] que contém os vetores $\vec{a}$ e $\vec{b}$.

## 3. Sentido

O sentido do produto vetorial é determinado pela [[Regra da Mão Direita|regra da mão direita]]. Para aplicar essa regra, siga os seguintes passos:

1. Aponte o dedo indicador da sua mão direita na direção do vetor $\vec{a}$.
2. Aponte o dedo médio na direção do vetor $\vec{b}$.
3. O seu polegar apontará na direção do vetor $\vec{a} \times \vec{b}$.

## 4. Representação Matemática

Em termos de componentes, o produto vetorial em 3D pode ser calculado utilizando o seguinte [[Determinante|determinante]]:

$$
\vec{a} \times \vec{b} = det \begin{bmatrix}
 \hat i&\hat j  &\hat k \\ 
 a_x& a_y &a_z \\ 
 b_x&b_y  &b_z 
\end{bmatrix} = (E_{ijk}a^ib^j)^k
$$

Onde $E_{ijk}$ é o [[Tensor|tensor]] de Levi-Civita.

## 5. Aplicações

O produto vetorial possui diversas aplicações em [[Física]] e [[Engenharia]]. Algumas das mais comuns incluem:

### 5.1. Torque

O [[Torque|torque]] é uma medida da força que causa a [[Rotação|rotação]] de um objeto em torno de um [[Eixo de Rotação|eixo]]. Ele é definido como o produto vetorial entre a [[Força|força]] aplicada ($\vec{F}$) e o [[Vetor Posição|vetor posição]]  ($\vec{r}$) em relação ao ponto de rotação:

$$
\vec{\tau} = \vec{r} \times \vec{F}
$$

O torque possui as seguintes características:

>- **Módulo**: mede a intensidade do torque, ou seja, a tendência de rotação.
>- **Direção**: indica o eixo de rotação.
>- **Sentido**: indica o sentido da rotação.

### 5.2. Força Magnética

A [[Força Magnética|força magnética]] que atua sobre uma partícula carregada em movimento dentro de um [[Campo Magnético|campo magnético]] é dada por:

$$
\vec{F} = q (\vec{v} \times \vec{B})
$$

onde:
>- $q$ é a [[Carga Elétrica|carga]] da partícula.
>- $\vec{v}$ é a [[Velocidade|velocidade]] da partícula.
>- $\vec{B}$ é o campo magnético.

Nesse caso, o produto vetorial determina a direção e o sentido da força magnética, que é perpendicular tanto à velocidade da partícula quanto ao campo magnético.

### 5.3. Momento Angular

O [[Momento Angular|momento angular]] de uma partícula em relação a um ponto é definido como o produto vetorial entre o vetor posição da partícula ($\vec{r}$) e seu momento linear ($\vec{p}$):

$$
\vec{L} = \vec{r} \times \vec{p}
$$

O momento angular é uma grandeza importante em sistemas que envolvem rotação, como planetas orbitando estrelas ou partículas girando em torno de um núcleo atômico.

### 5.4. Geometria Analítica

Na [[Geometria Analítica|geometria analítica]], o produto vetorial pode ser usado para:

* Encontrar a área de um triângulo ou paralelogramo.
* Determinar a equação de um plano perpendicular a dois vetores dados.
* Calcular a distância entre um ponto e uma reta no espaço tridimensional.

## 6. Conclusão

O produto vetorial é uma ferramenta matemática poderosa com diversas aplicações em física, engenharia e geometria. Sua capacidade de capturar a relação geométrica entre vetores o torna essencial para a compreensão de fenômenos que envolvem perpendicularidade, áreas, rotações e movimentos em três dimensões.
