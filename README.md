# Manipulação de Arquivo e Algoritmos de Ordenação e Busca

Este projeto em C oferece funções para gerar um arquivo de texto com números inteiros aleatórios, realizar buscas e ordenar números usando diferentes algoritmos.

## Funcionalidades

1. **Geração de Arquivo**:
   - `gerar_arquivo_numeros(char *nome_arquivo, int quantidade)`: Gera um arquivo com uma quantidade especificada de números inteiros aleatórios.

2. **Algoritmos de Busca**:
   - `busca_linear(int numero, char *nome_arquivo)`: Busca um número no arquivo usando busca linear.
   - `busca_sentinela(int numero, char *nome_arquivo)`: Busca um número no arquivo usando busca sentinela.
   - `busca_binaria(int numero, char *nome_arquivo)`: Busca um número no arquivo usando busca binária (requere que o arquivo seja ordenado).

3. **Algoritmos de Ordenação**:
   - `insertion_sort(int *numeros, int tamanho)`: Ordena um array de números usando o algoritmo de Insertion Sort.
   - `bubble_sort(int *numeros, int tamanho)`: Ordena um array de números usando o algoritmo de Bubble Sort.
   - `quick_sort(int *numeros, int baixo, int alto)`: Ordena um array de números usando o algoritmo de Quick Sort.

## Como Usar

1. **Compilar o Código**:
   ```sh
   gcc -o manipulacao_arquivo main.c
