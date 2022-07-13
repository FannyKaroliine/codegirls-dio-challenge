# Análise de Códigos

Análises feitas pelo compilador ao inserirmos um programa fonte para ser traduzido em um programa objeto

**Análise Léxica**

- Realiza um scanner, uma leitura do programa fonte e agrupa caracteres em lexemas

- Produz uma sequência de símbolos léxicos (denominados tokens)

- Etapas: Particionar > Classificar > Eliminar 

**Análise Sintática**

- Análise da forma

- Verificação da estrutura gramatical do código inserido

- Validação da sequência de tokens de acordo com a linguagem de programação

**Análise Semântica**

- Analisa o significado dos comandos inseridos

- É possível haver erro de semântica mesmo que não haja o sintático

- == e = estão sintaticamente corretos, ou seja, podem ser lidos pela linguagem de programação, mas possuem significados distintos, ações diferentes

- Um erro semântico tende a ser mais difícil de encontrar no código, uma vez que passa pela análise sintática, mas não executa a função corretamente


