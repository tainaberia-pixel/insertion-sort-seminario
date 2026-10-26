#Insertion Sort — Seminário de Programação

> Trabalho de Seminário — Disciplina de Programação / Estrutura de Dados
> **Aluno:** [Tainá Beria]
> **Data:** 26 de outubro de 2026

## Descrição
Este repositório contém a implementação em Java do algoritmo de ordenação **Insertion Sort**, também conhecido como Ordenação por Inserção. O algoritmo funciona de forma intuitiva, semelhante à maneira como ordenamos cartas em uma mão de baralho.

## Conceitos Demonstrados

| Conceito | Descrição |
|**Estrutura de Dados** | Lista sequencial (vetor/arranjo) |
|**Algoritmo** | Insertion Sort — construção incremental da sequência ordenada |
|**Lógica** | Percorre a lista, inserindo cada elemento na posição correta |
|**Estabilidade** | Preserva a ordem de elementos com valores iguais |
|**No local** | Ordena o próprio vetor, sem precisar de espaço extra significativo |

## Estrutura do Projeto

insertion-sort-seminario/
|---scr/
|   |---InsertionSort.java
|---README.md
|---.gitignore

## Como executar 

### Pré-requisito
Ter o JDK (Java Development Kit) instalado.

### Passo a passo

# 1. Compilar o código javac src/InsertionSort.java -d scr/
# 2. Executar java -cp scr InsertionSort

Demonstração do InsertionSort 
Antes de ordenar:[5,3,8,4,2,7,1,6]
Depois de ordenar: [1,2,3,4,5,6,7,8]


Análise de Desempenho
Cenário|Complexidade 
Melhor caso (já ordenado)|O(n)
Caso médio|O(n ao quadrado)
Pior caso (invertido)|O(n ao quadrado)
Espaço extra| O(1) - ordena no local

Como funciona o algoritmo
 
1. Considera que o primeiro elemento já está ordenado
​
2. Pega o próximo elemento da parte desordenada
​
3. Compara com os elementos da parte ordenada, empurrando os maiores para a frente
​
4. Insere o elemento na posição correta
​
5. Repete até que todos tenham sido inseridos
 
 
 
Vantagens e Limitações
 
Pontos Fortes
 
- Simples de entender e implementar
​
- Eficiente para conjuntos pequenos de dados
​
- Eficiente quando os dados já estão quase ordenados
​
- Ordena no local — gasta pouca memória
​
- É estável
 
Limitações
 
- Ineficiente para grandes volumes de dados — O(n²)
​
- Muitas operações de deslocamento no pior caso
 
 
 
Referências
 
- KNUTH, Donald E. The Art of Computer Programming — Volume 3: Sorting and Searching
​
- CORMEN, T. H. et al. Algoritmos e Estruturas de Dados
​
- Documentação oficial do Java — Interface Comparable
 
 
 
Farroupilha, 26 de outubro de 2026