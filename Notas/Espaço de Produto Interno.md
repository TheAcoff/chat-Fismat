---
Endereço: "[[UFJF-Disciplinas-]]()"
Relacionado:
  - "[[Algebra Linear]]"
Referências:
---
**Definição**
Um espaço de produto interno é um espaço vetorial real ou complexo, munido com um [[Produto Interno]].

Um espaço de produto interno finito-dimensional real é normalmente chamado de **Espaço euclidiano** enquanto no espaço complexo **Espaço Unitário**

---
**Teorema 1**
Se $\mathbb{V}$ é um espaço de produto interno e para todos os vetores $\alpha$ e $\beta$, e um escalar $c$.
1. $||c \alpha|| = |c| \; ||\alpha||$
2. $||\alpha|| > 0$ para $\alpha \neq 0$
3. $|(\alpha|\beta)|\leq ||\alpha|| + ||\beta||$
4. $||\alpha+\beta|| \leq ||\alpha|| + ||\beta||$

## 0.1   Menor aproximante
O menor aproximante a um vetor $\beta$ por vetores em $\mathbb{W}$ é um vetor $\alpha \in \mathbb{W}$; 
$$
||\beta - \alpha|| \leq ||\beta - \gamma||
$$

## 0.2   Desigualdade de Cauchy-Schwarz
$$
|(\alpha|\beta)|\leq ||\alpha|| + ||\beta||
$$
---
# 1   Ortogonalidade
Falamos que $\alpha$ é ortogonal a $\beta$ se $(\alpha|\beta) = 0$

**Teorema 2**
Um conjunto ortogonal de vetores não zero é Linearmente Independente

 
## 1.1   Ortogonalização de Gram-Schimidt
Basicamente, tirar a parte paralela de um vetor para sobrar apenas a perpendicular:
$$
\alpha_{m+1} = \beta_{m+1} - \sum \frac{(\beta_{m+1}|a_{k})}{||\alpha_{k}||^{2}}\alpha_{k}
$$
- Todo espaço de produto interno finito-dimensional tem uma base ortonormal

---

