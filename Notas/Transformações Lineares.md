Links:[[Algebra Linear]]
Referência: [Hoffmann]
# 1   Definição
Dado os espaços $V$ e $W$ sobre o corpo $F$, uma transformação $T$ é dada por:$$\begin{matrix}
T:V\rightarrow W
\end{matrix}$$
em que:$$T(c\alpha + \beta) = c(T \alpha)+T\beta$$
**Teorema**: Existe uma única transformação $T$ entre $V \rightarrow W$ , tal que $T \alpha_j=\beta_j$ 

>[!note] O *range* de $T$ é um subespaço de $W$

Se $T \alpha = 0$, $T$ é um subespaço de $V$

---
- **Definições**:
	- Espaço nulo (*null space*) é o conjunto dos vetores $\alpha$ tal que $T \alpha = 0$.
	- Rank de $T$ é dimensão do *range*
	- A nulidade (nullity) de $T$ é a dimensão do *null* space de $T$

**Teorema**: rank($T$)+nulidade($T$) = dim($V$)

---
# 2   Álgebra
**Teorema**:
$(T+U)(\alpha)=T \alpha + U \alpha$ 
$(cT)(\alpha)=c(T \alpha)$

O conjunto de todas as transformações lineares $V \rightarrow W$ é um espaço vetorial sobre $F$ e uma destas transformações é um subespaço de todas as funções $V \rightarrow W$. 
>[!note] O espaço dessas transformações vai ser definido por $L(V,W)$.

**Teorema** Definindo $T: V \rightarrow W$ e $U: W \rightarrow Z$, então, $UT$ (definido por: $(UT)(\alpha) = U(T(\alpha))$) é uma transformação $V \rightarrow Z$. 

**Definição**: Um operador linear é uma transformação $V \rightarrow V$.

**Lemma**: Definindo as transformações como operadores, temos:$$\begin{matrix}IU = UI = U \\U(T_1+T_2) = UT_1+UT_2; (T_1+T_2)U = T_1U+T_2U  \\ c(UT_1) = (cU)T_1 = U(cT_1) \end{matrix}$$
>[!tip] O espaço $L(V,V)$ com a operação de composição é conhecido com **Álgebra Linear** com identidade

**Definição**: Função é chamada de invertível se: $T,U$ tal que $UT=I$ em $V$ e $TU=I$ em $W$, então, podemos chamar $U=Tˆ-1$

**Definição**: $1:1$: $T \alpha = T\beta \Rightarrow \alpha = \beta$ (característica para ser invertível)

**Teorema**: $T: V \rightarrow W$ e $T^{-1}: W \rightarrow V$

---
# 3   Representação por matrizes
Determinamos uma representação de matrizes por:
$$
T \alpha_j = \sum\limits
_{i=1}^n A_{ij} \beta_i
$$
Definimos então uma matriz $A$ que representa a transformação $T$ de um vetor nas bases $\mathfrak{B}$ e $\mathfrak{B'}$ 
$$
[T\alpha]_{\mathfrak{B'}}=A[\alpha]_{\mathfrak {B}}
$$
>[!note] Os vetores transformados viram colunas da matriz de representação

veja o exemplo a seguir: ![[Imagens/Screenshot_20230619_123652_Samsung Notes 1.jpg]]

Pelo Teorema 13, podemos compor as transformações e suas matrizes

Para converter a mesma transformação entre diferentes bases, temos que tirar a matriz de transformação de bases $P$, e usar: 
$$
[T]_{\mathfrak{B'}} = Pˆ(-1)[T]_{\mathfrak{B}} P
$$
>[!note] A maior parte dos problemas podem ser resolvidos utilizando um sistema para expressar entre diferentes bases (ver pdf com exercícios resolvidos)

---
