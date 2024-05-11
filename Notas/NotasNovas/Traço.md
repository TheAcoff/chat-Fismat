# Traço

## Introdução

O traço é uma operação que associa um escalar a uma [[Matriz]] quadrada. É uma ferramenta útil em [[Algebra Linear]] com diversas aplicações em áreas como física, estatística e aprendizado de máquina. 

## Definição

O traço de uma matriz quadrada $A$ de ordem $n$, denotado por $tr(A)$, é definido como a soma dos elementos de sua diagonal principal:

$tr(A) = a_{11} + a_{22} + ... + a_{nn}$,

onde $a_{ij}$ representa o elemento na linha $i$ e coluna $j$ da matriz $A$.

## Propriedades

O traço possui diversas propriedades importantes:

1. **Linearidade:** $tr(aA + bB) = a \cdot tr(A) + b \cdot tr(B)$ para quaisquer matrizes quadradas $A$ e $B$ de mesma ordem e escalares $a$ e $b$.

2. **Invariância por transposição:** $tr(A) = tr(A^T)$, onde $A^T$ denota a [[Matriz Transposta]] de $A$.

3. **Invariância por permutação cíclica:** $tr(ABC) = tr(CAB) = tr(BCA)$ para quaisquer matrizes $A$, $B$ e $C$ de ordens compatíveis para a multiplicação. Observe que a ordem geral das matrizes não pode ser alterada, apenas permutada ciclicamente.

4. **Traço do produto:** $tr(AB) = tr(BA)$ para quaisquer matrizes $A$ e $B$ de ordens compatíveis para a multiplicação.

## Aplicações

O traço surge em diversas áreas e aplicações:

* **Álgebra Linear:** Simplificação de cálculos com matrizes, demonstração de teoremas. 
* **[[Física Matemática]]:**  Mecânica quântica, relatividade geral.
* **Estatística:** Análise multivariada, inferência estatística.
* **Aprendizado de Máquina:** Otimização de modelos, regularização.
* **Geometria Diferencial:** Cálculo de curvatura, análise de superfícies.

## Exemplos

* Seja $A = \begin{bmatrix} 2 & 1 \\ 4 & 3 \end{bmatrix}$, então $tr(A) = 2 + 3 = 5$.
* Seja $B = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}$, então $tr(B) = 1 + 5 + 9 = 15$.

## Conclusão

O traço é uma operação simples, mas poderosa, com aplicações em diversas áreas da matemática e suas aplicações. Suas propriedades facilitam cálculos com matrizes e permitem a demonstração de resultados importantes em diferentes contextos.
