# Resolução exercício Beecrowd1075

## Descrição do projeto
Leia um valor inteiro N. Apresente todos os números entre 1 e 10000 que divididos por N dão resto igual a 2.

## Como Funciona
1. O usuário insere o número divisor, que é armazenado na variável `num`.
2. Uma estrutura de repetição `for` inicia no número 1 (`i = 1`) e percorre de forma sequencial até o limite de 10000 (`i <= 10000`).
3. Dentro do loop, uma estrutura condicional `if (i % num == 2)` utiliza o operador de resto (`%`) para verificar a condição estabelecida.
4. Caso o resto da divisão do número atual `i` por `num` seja igual a 2, o programa imprime o valor de `i` no terminal (um por linha).