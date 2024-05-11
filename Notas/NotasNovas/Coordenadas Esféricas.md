
Tags: [[Cálculo_Análise]]

---
# 1   Transformações
>[!tip] Obtenção
>Demonstração geométrica utilizando trigonometria

As coordenadas esféricas são um sistema de coordenadas tridimensional que se baseia em três parâmetros: raio ($r$), ângulo polar ($\theta$) e ângulo azimutal ($\phi$). Elas são particularmente úteis para descrever sistemas que possuem simetria esférica, como átomos e planetas.

A relação entre as coordenadas esféricas ($r$, $\theta$, $\phi$) e as coordenadas cartesianas ($x$, $y$, $z$) é dada por:

$$\begin{matrix}
x=rcos(\varphi)sin(\theta) \\ y=rsin(\varphi)sin(\theta) \\ z=rcos(\theta)
\end{matrix}$$

**Tensor Métrico:**

O tensor métrico, $g_{ij}$,  é uma ferramenta fundamental para calcular distâncias e ângulos em diferentes sistemas de coordenadas. Em coordenadas esféricas, o tensor métrico é dado por:

$$
g_{ij} = \begin{pmatrix} 1 & 0 & 0 \\ 0 & r^2 & 0 \\ 0 & 0 & r^2 sin^2(\theta)
\end{pmatrix}
$$

**Versores:**

Os versores, $\hat{\mathbf{r}}$, $\hat{\boldsymbol{\theta}}$ e $\hat{\boldsymbol{\varphi}}$,  são vetores unitários que apontam nas direções das coordenadas $r$, $\theta$ e $\phi$, respectivamente. Em coordenadas cartesianas, eles são dados por:

$$
\begin{aligned}{\hat {\mathbf {r} }}&=\sin \theta \cos \varphi \,{\hat {\mathbf {x} }}+\sin \theta \sin \varphi \,{\hat {\mathbf {y} }}+\cos \theta \,{\hat {\mathbf {z} }},\\{\hat {\boldsymbol {\theta }}}&=\cos \theta \cos \varphi \,{\hat {\mathbf {x} }}+\cos \theta \sin \varphi \,{\hat {\mathbf {y} }}-\sin \theta \,{\hat {\mathbf {z} }},\\{\hat {\boldsymbol {\varphi }}}&=-\sin \varphi \,{\hat {\mathbf {x} }}+\cos \varphi \,{\hat {\mathbf {y} }}\end{aligned}
$$

---
# 2   Operadores
**Gradiente:**

O gradiente, $\nabla f$,  de uma função escalar $f$ é um vetor que aponta na direção de maior crescimento da função. Em coordenadas esféricas, o gradiente é dado por:

$$\huge
\nabla f = \frac{\partial f}{\partial r}\hat{\mathbf{r}} + \frac{1}{r}\frac{\partial f}{\partial \theta}\hat{\boldsymbol{\theta}} + \frac{1}{r\sin\theta}\frac{\partial f}{\partial \varphi}\hat{\boldsymbol{\varphi}},
$$

**Divergente:**

O divergente, $\nabla \cdot \mathbf{A}$,  de um campo vetorial $\mathbf{A}$ mede a tendência do campo de convergir ou divergir em um ponto. Em coordenadas esféricas, o divergente é dado por:

$$
\nabla \cdot \mathbf{A} = \frac{1}{r^{2}}\frac{\partial}{\partial r}(r^{2}A_{r}) + \frac{1}{r\sin\theta}\frac{\partial}{\partial \theta}(\sin\theta A_{\theta}) + \frac{1}{r\sin\theta}\frac{\partial A_{\varphi}}{\partial \varphi}
$$

**Rotacional:**

O rotacional, $\nabla \times \mathbf{A}$,  de um campo vetorial $\mathbf{A}$ mede a tendência do campo de girar em torno de um ponto. Em coordenadas esféricas, o rotacional é dado por:

$$
\nabla \times \mathbf{A} = \frac{1}{r\sin\theta}\left(\frac{\partial}{\partial \theta}(A_{\varphi}\sin\theta) - \frac{\partial A_{\theta}}{\partial \varphi}\right)\hat{\mathbf{r}} \\ + \frac{1}{r}\left(\frac{1}{\sin\theta}\frac{\partial A_{r}}{\partial \varphi} - \frac{\partial}{\partial r}(rA_{\varphi})\right)\hat{\boldsymbol{\theta}} \\ + \frac{1}{r}\left(\frac{\partial}{\partial r}(rA_{\theta}) - \frac{\partial A_{r}}{\partial \theta}\right)\hat{\boldsymbol{\varphi}}
$$

**Laplaciano:**

O Laplaciano, $\Delta A$,  de uma função escalar $A$ mede a curvatura da função em um ponto. Em coordenadas esféricas, o Laplaciano é dado por:

$$
\begin{aligned}
\Delta A= \frac{1}{r^{2}}\frac{\partial}{\partial r}\left(r^{2}\frac{\partial A} {\partial r}\right)+ \frac{1}{r^{2}sin(\theta)} \frac{\partial}{\partial \theta}\left(sin\theta \frac{\partial A}{\partial \theta}\right)+\frac{1}{r^{2}sin^2(\theta)}\frac{\partial^{2} A}{\partial \varphi^2}\\ \\
\Delta A= \frac{1}{r}\frac{\partial^{2}}{\partial r^{2}}(Ar) + \frac{1}{r^{2}sin(\theta)} \frac{\partial}{\partial \theta}\left(sin\theta \frac{\partial A}{\partial \theta}\right)+\frac{1}{r^{2}sin^2(\theta)}\frac{\partial^{2} A}{\partial \varphi^2}
\end{aligned}
$$
