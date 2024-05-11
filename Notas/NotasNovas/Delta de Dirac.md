## Delta de Dirac

Links: [[Funções]]

Def.: É uma função generalizada que apresenta um "pico infinito" no zero e é zero em qualquer outro ponto. 

$$
\delta(x) = \left\{\begin{matrix}
\infty, \; x=0\\
0, \; \forall x\neq 0
\end{matrix}\right.
$$

Apesar de não ser uma função no sentido tradicional, o Delta de Dirac é uma ferramenta poderosa na física e matemática, representando um pulso infinitamente estreito e intenso. 

### Propriedades importantes

1. **Normalização**: A integral do Delta de Dirac sobre todo o eixo real é igual a 1.

$$
\int_{-\infty}^{\infty}\delta(x)dx = 1
$$

   Essa propriedade garante que a função represente um pulso unitário.

2. **"Filtragem"**: Ao multiplicar o Delta de Dirac por uma função  [[Funções|$f(x)$]] e integrar, obtemos o valor da função no ponto onde o Delta de Dirac é não nulo, ou seja, em $x=0$.

$$
\int_{-\infty}^{\infty}\delta(x)f(x)dx = f(0)
$$

   Essa propriedade é fundamental para selecionar valores específicos de uma função.

3. **Translação**:  Podemos deslocar o pico do Delta de Dirac para qualquer ponto  $x'$ utilizando  $\delta(x - x')$. 

$$
\int_{-\infty}^{\infty} \delta(x-x')f(x) = f(x')
$$

   Dessa forma, a função  $f(x)$ é "amostrada" no ponto $x'$.

4. **Multiplicação por escalar**: Multiplicar o Delta de Dirac por uma constante  $\alpha$  altera sua amplitude, mas mantém a propriedade de normalização.

$$
\int_{-\infty}^{\infty} \delta(\alpha x) dx = \int_{-\infty}^{\infty}\delta(u)\frac{du}{|\alpha|} = \frac{1}{|\alpha|}
$$

5. **Simetria**: O Delta de Dirac é simétrico em relação à origem.

$$
\delta(x-x') = \delta(x'-x)
$$

O Delta de Dirac pode ser visualizado como o limite de uma série de funções que se tornam cada vez mais estreitas e altas, mantendo a área total igual a 1. Exemplos comuns dessas funções são:

* Função retangular
* Função gaussiana


### Aplicações do Delta de Dirac:

* **Física**:  modelagem de impulsos instantâneos, como colisões, cargas pontuais e fontes de luz.
* **Processamento de sinais**: amostragem de sinais, filtragem e análise espectral.
* **Equações diferenciais**: solução de equações diferenciais com termos descontínuos ou impulsivos.




