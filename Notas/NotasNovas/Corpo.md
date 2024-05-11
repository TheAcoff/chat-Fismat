# Corpo

## Introdução

Um corpo é uma estrutura algébrica que generaliza conjuntos numéricos como os números racionais, reais e complexos.  Ele fornece um conjunto de elementos com duas operações, adição e multiplicação, que satisfazem propriedades específicas que permitem realizar operações aritméticas familiares. Corpos são objetos fundamentais em [[Algebra Linear]] e outras áreas da matemática.

## Definição Formal

Um corpo é um conjunto não vazio $\mathbb{F}$ equipado com duas operações binárias, adição ($+$) e multiplicação ($\cdot$), que satisfazem as seguintes propriedades:

**1. Propriedades da Adição:**

   * **Associatividade:** $(a + b) + c = a + (b + c)$ para todos $a, b, c \in \mathbb{F}$.
   * **Comutatividade:** $a + b = b + a$ para todos $a, b \in \mathbb{F}$.
   * **Existência do elemento neutro:** Existe um elemento $0 \in \mathbb{F}$, chamado elemento neutro da adição, tal que $a + 0 = a$ para todo $a \in \mathbb{F}$.
   * **Existência do inverso aditivo:** Para cada $a \in \mathbb{F}$, existe um elemento $-a \in \mathbb{F}$, chamado inverso aditivo de $a$, tal que $a + (-a) = 0$.

**2. Propriedades da Multiplicação:**

   * **Associatividade:** $(a \cdot b) \cdot c = a \cdot (b \cdot c)$ para todos $a, b, c \in \mathbb{F}$.
   * **Comutatividade:** $a \cdot b = b \cdot a$ para todos $a, b \in \mathbb{F}$.
   * **Existência do elemento neutro:** Existe um elemento $1 \in \mathbb{F}$, chamado elemento neutro da multiplicação, tal que $a \cdot 1 = a$ para todo $a \in \mathbb{F}$.
   * **Existência do inverso multiplicativo:** Para cada $a \in \mathbb{F}$ diferente de $0$, existe um elemento $a^{-1} \in \mathbb{F}$, chamado inverso multiplicativo de $a$, tal que $a \cdot a^{-1} = 1$.

**3. Distributividade:**

   * $a \cdot (b + c) = a \cdot b + a \cdot c$ para todos $a, b, c \in \mathbb{F}$.

## Exemplos de Corpos

* **Números Racionais ($\mathbb{Q}$):**  O conjunto dos números racionais com as operações usuais de adição e multiplicação forma um corpo.
* **Números Reais ($\mathbb{R}$):**  O conjunto dos números reais com as operações usuais de adição e multiplicação forma um corpo.
* **Números Complexos ($\mathbb{C}$):**  O conjunto dos números complexos com as operações usuais de adição e multiplicação forma um corpo.
* **Corpo Finito:**  Existem corpos finitos, como $\mathbb{Z}_p$ (inteiros módulo um número primo $p$), que possuem um número finito de elementos.

## Importância dos Corpos

* **Fundamentação da álgebra linear:** Corpos são a base para [[Espaço Vetorial]], que são conjuntos de vetores que podem ser somados e multiplicados por escalares provenientes de um corpo.
* **Resolução de equações:**  As propriedades de um corpo permitem resolver equações e sistemas de equações lineares.
* **Aplicações em diversas áreas:** Corpos têm aplicações em física, criptografia, ciência da computação e outras áreas.

## Observações

* Um corpo não pode ter divisores de zero, ou seja, não existem elementos $a, b \in \mathbb{F}$ diferentes de zero tais que $a \cdot b = 0$.
* O menor corpo possível é $\mathbb{Z}_2$, que possui apenas dois elementos, $0$ e $1$.


