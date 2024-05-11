tags: [[Cálculo_Análise]]

# 1   Primeira Ordem
## 1.1   Método do fator integrante
Dado: 
$$
P(x)y'+Q(x)y = R(x) \Label[1]{}
$$
Multiplicamos toda a expressão por um fator $\mu$, e supomos que: 
$$\large(\mu(x)P(x)y)'=\mu(x)R(x) \Label[2]{derivada}$$
Expandindo $\Ref[2]{derivada}$, concluímos:
$$\Label[3]{}
[\mu(x)P(x)]'=\mu(x)Q(x)
$$
com isso: 
$$\large\Label[4]{}
\mu(x) = e^{\int \frac{Q-P'}{P}dx}
$$
Retornando à $\Ref[2]{derivada}$, temos: $$
y = \frac{1}{\mu P}\int\mu R
$$

## 1.2   Equação separável
Dado 
$$\Label[5]{}
\frac{dy}{dx}=f(x)=\frac{g(x)}{h(x)}
$$
resolve do jeito "normal".

---
# 2   Segunda Ordem
## 2.1   Homogêneas
$$\large \begin{split}
\lambda_{1}\neq\lambda_{2} \Rightarrow y = c_{1}e^{\lambda_{1}x}+c_{2}e^{\lambda_{2}x} \\

\lambda_{1}=\lambda_{2} \Rightarrow y = c_{1}e^{\lambda_{1}x}+c_{2}xe^{\lambda_{2}x} \\

\lambda_{1},\lambda_{2}^{*} \Rightarrow y = c_{1}e^{\alpha x}cos(\beta x)+c_{2}e^{\alpha x}sin(\beta x) 

\end{split}
$$

## 2.2   Wronskiano e Fórmula de Abel
$$\Label[6]{}

W = det \begin{pmatrix} \phi_{1}(x) & \phi_{2}(x)\\ \phi_{1}'(x) & \phi_{2}'(x) \\ \end{pmatrix}

$$
Fórmula de Abel:$$\large \Label[7]{}
W(x) = c e^{\int P(x)dx}
$$
## Não homogêneas
$$y'' + by' + cy = Q(x)$$

Solução possuí 2 partes, uma homogênea e outra particular:$$
y = y_p + y_h
$$
Exemplo de soluções particulares:
	Exponencial: $y_p = A e^{\gamma}$
	Trigonométrica: $y_p = Asen(\gamma)+Bcos(\gamma)$

## Variação de parâmetros
$$\begin{pmatrix} \phi_{1}(x) & \phi_{2}(x)\\ \phi_{1}'(x) & \phi_{2}'(x) \\ \end{pmatrix} \begin{pmatrix}c_{1}'\\ c_{2}'\end{pmatrix} = \begin{pmatrix}0 \\ Q(x)\end{pmatrix}
$$
$$y_{p} = c_{1}(x) \phi_{1}(x) + c_{2}(x)\phi_{2}(x)$$