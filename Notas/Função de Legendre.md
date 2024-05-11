Links: [[Funções Especiais]]
Refs: [Notas de Aula Zé Paulo](https://drive.google.com/file/d/1K0JkiYrTLuE1NeEE5MOFNSwKKKp_3xGV/view?usp=drive_link)

$$\large
P_l(x),P_{l}^{m}(x), Y_{lm}(x)
$$
# 1   Legendre não Associado
## 1.1   Função Geratriz:
$$\large
g(x,t) = (1-2xt+t^{2})^{-\frac{1}{2}} \equiv \sum\limits_{n=0}^{\infty} P_{n}(x)t^{n}, |t|<1
$$
## 1.2   Relações de Recorrência: 
$$\large
P_{0}(x) = 1
$$
$$\large
P_{1}(x) = x
$$
$$ \large
P_{n+1}(x) = \frac{1}{n+1}[x(1+2n)P_{n}(x) - n P_{n-1}(x)]
$$
Com derivadas:
$$\large
P_{n+1}'(x) + P_{n-1}'(x) = P_{n}(x) + 2xP_{n}'(x)
$$
$$\large
P_{n+1}'(x) = (n+1)P_{n}(x) + x P_{n}'(x)
$$
$$\large
P_{n-1}'(x) = -n P_{n}(x) + P_{n}'(x)
$$

## 1.3   Equação diferencial de Legendre
$$ \huge
(1-x^{2})P_{n}''(x) - 2xP_{n}'(x) + n(n+1)P_{n}(x) = 0
$$
>[!tip] Ao resolver uma eq dif em [[coordenadas esféricas]], podemos ter uma solução angular envolvendo seno, para resolver, considere $x = cos(\theta)$ na equação anterior e irá encontrar que a solução de $\Theta = P_{n}(cos(\theta))$  ^[Pag12]

Obs: Equação diferencial em [[coordenadas esféricas]], parte angular:
$$
\frac{1}{sen(\theta)} \frac{d}{d\theta} \left(sen \left(\theta \frac{d\Theta}{d\theta}\right)\right) + n(n+1)\Theta = 0
$$

## 1.4   Paridade
$$
(-1)^{n}P_{n}(-x) = P_{n}(x)
$$

## 1.5   Ortogonalidade
$$\large
\int\limits_{-1}^{1} P_{n}(x)P_{m}(x) dx = \delta_{mn}\left(\frac{2}{2n+1}\right)
$$
$$\large
\int\limits_{0}^{\pi} P_{n}(cos(\theta))P_{m}(cos(\theta))sen(\theta) d\theta = \delta_{mn}\left(\frac{2}{2n+1}\right)
$$
>[!note] Autofunções que são compostas por polinomios de Legendre são feitas de maneira usual (pag20)

## 1.6   Representação Integral
$$\large
P_{l}(z) = \frac{1}{2\pi i} \oint (1-2zt+t^{2})^{-\frac{1}{2}} t^{-l-1}dt
$$
Ou pela Integral de Schlaefli:
$$
P_{l}(z) = - \frac{1}{2\pi i} \oint \frac{(u^{2}-1)^{l}}{(u-z)^{l+1}}du
$$
## 1.7   Fórmula de Rodrigues
$$\huge
P_{l}(z) = \frac{1}{2^{l}l!}\frac{d^{l}}{dz^{l}}[z^{2}-1]^{l}
$$

---

# 2   Legendre Associado
$$\huge
P_{n}^{m}(x)
$$
Problemas com todos os ângulos das [[Coordenadas Esféricas]], implica em uma solução do tipo $x = cos(\theta)$:
$$
\frac{1}{sen(\theta)} \frac{d}{d\theta} \left(sen \left(\theta \frac{d}{d\theta} P_{n}^{m}(cos(\theta)\right)\right) + \left[n(n+1)-\frac{m^2}{sen^{2}(\theta)}\right]P_{n}^{m}(cos(\theta) = 0
$$
A equação diferencial "original":
$$\large
(1-x^{2})P_{n}^{m''}(x) - 2xP_{n}^{m'}(x) + [n(n+1) - \frac{m^{2}}{1-x^{2}}]P_{n}^{m}(x) = 0
$$
têm os polinômios escritos como:
$$\huge
P_{n}^{m}(x) = (1-x^{2})^{\frac{m}{2}}\frac{d^{m}}{dx^{m}} P_{n}(x)
$$
## 2.1   Relações de Recorrência

