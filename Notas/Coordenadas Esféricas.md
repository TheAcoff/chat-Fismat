Tags: [[Cálculo_Análise]]

---
# 1   Transformações
>[!tip] Obtenção
>Demonstração geométrica utilizando trigonometria

$$\begin{matrix}
x=rcos(\varphi)sin(\theta) \\ y=rsin(\varphi)sin(\theta) \\ z=rcos(\theta)
\end{matrix}$$
Tensor Métrico:
$$
g_{ij} = \begin{pmatrix} 1 & 0 & 0 \\ 0 & r^2 & 0 \\ 0 & 0 & r^2 sin^2(\theta)
\end{pmatrix}
$$
Versores:
$$
\begin{aligned}{\hat {\mathbf {r} }}&=\sin \theta \cos \varphi \,{\hat {\mathbf {x} }}+\sin \theta \sin \varphi \,{\hat {\mathbf {y} }}+\cos \theta \,{\hat {\mathbf {z} }},\\{\hat {\boldsymbol {\theta }}}&=\cos \theta \cos \varphi \,{\hat {\mathbf {x} }}+\cos \theta \sin \varphi \,{\hat {\mathbf {y} }}-\sin \theta \,{\hat {\mathbf {z} }},\\{\hat {\boldsymbol {\varphi }}}&=-\sin \varphi \,{\hat {\mathbf {x} }}+\cos \varphi \,{\hat {\mathbf {y} }}\end{aligned}
$$

---
# 2   Operadores
Gradiente:
$$\huge
\nabla f = \frac{\partial f}{\partial r}\hat{\mathbf{r}} + \frac{1}{r}\frac{\partial f}{\partial \theta}\hat{\boldsymbol{\theta}} + \frac{1}{r\sin\theta}\frac{\partial f}{\partial \varphi}\hat{\boldsymbol{\varphi}},
$$
Divergente:
$$
\nabla \cdot \mathbf{A} = \frac{1}{r^{2}}\frac{\partial}{\partial r}(r^{2}A_{r}) + \frac{1}{r\sin\theta}\frac{\partial}{\partial \theta}(\sin\theta A_{\theta}) + \frac{1}{r\sin\theta}\frac{\partial A_{\varphi}}{\partial \varphi}
$$
Rotacional:
$$
\nabla \times \mathbf{A} = \frac{1}{r\sin\theta}\left(\frac{\partial}{\partial \theta}(A_{\varphi}\sin\theta) - \frac{\partial A_{\theta}}{\partial \varphi}\right)\hat{\mathbf{r}} \\ + \frac{1}{r}\left(\frac{1}{\sin\theta}\frac{\partial A_{r}}{\partial \varphi} - \frac{\partial}{\partial r}(rA_{\varphi})\right)\hat{\boldsymbol{\theta}} \\ + \frac{1}{r}\left(\frac{\partial}{\partial r}(rA_{\theta}) - \frac{\partial A_{r}}{\partial \theta}\right)\hat{\boldsymbol{\varphi}}
$$
Laplaciano: 
$$
\begin{aligned}
\Delta A= \frac{1}{r^{2}}\frac{\partial}{\partial r}\left(r^{2}\frac{\partial A} {\partial r}\right)+ \frac{1}{r^{2}sin(\theta)} \frac{\partial}{\partial \theta}\left(sin\theta \frac{\partial A}{\partial \theta}\right)+\frac{1}{r^{2}sin^2(\theta)}\frac{\partial^{2} A}{\partial \varphi^2}\\ \\
\Delta A= \frac{1}{r}\frac{\partial^{2}}{\partial r^{2}}(Ar) + \frac{1}{r^{2}sin(\theta)} \frac{\partial}{\partial \theta}\left(sin\theta \frac{\partial A}{\partial \theta}\right)+\frac{1}{r^{2}sin^2(\theta)}\frac{\partial^{2} A}{\partial \varphi^2}
\end{aligned}
$$

