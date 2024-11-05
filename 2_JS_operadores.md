# Operadores em JavaScript: Uma Visão Geral
## Operadores em JavaScript são símbolos especiais que executam operações em valores (operandos) e retornam um resultado. 
##Eles são essenciais para a manipulação de dados e a construção de lógica em seus programas.

### Tipos de Operadores
JavaScript oferece uma variedade de operadores para diferentes propósitos:

1. Operadores Aritméticos:
Adição: + (ex: 3 + 5)
Subtração: - (ex: 7 - 2)
Multiplicação: * (ex: 4 * 6)
Divisão: / (ex: 10 / 2)
Módulo: % (retorna o resto da divisão: ex: 11 % 3 = 2)
Incremento: ++ (adiciona 1: ex: x++)
Decremento: -- (subtrai 1: ex: y--)
Exponenciação: ** (ex: 2 ** 3 = 8)

2. Operadores de Atribuição:
Atribuição simples: = (ex: x = 5)
Atribuição com operação: +=, -=, *=, /=, %= (ex: x += 3 é o mesmo que x = x + 3)

3. Operadores de Comparação:
Igual: == (verifica se os valores são iguais)
Igualdade estrita: === (verifica se os valores e os tipos são iguais)
Diferente: != (verifica se os valores são diferentes)
Desigualdade estrita: !== (verifica se os valores e os tipos são diferentes)
Maior que: >
Menor que: <
Maior ou igual: >=
Menor ou igual: <=

4. Operadores Lógicos:
E lógico: && (ambas as condições devem ser verdadeiras)
Ou lógico: || (pelo menos uma condição deve ser verdadeira)
Negação: ! (inverte o valor booleano)

5. Operadores Bit a Bit:
Operam nos bits individuais de números inteiros (ex: AND (&), OR (|), NOT (~), XOR (^), <<, >>, >>>)

6. Operador Ternário:
Uma forma concisa de escrever uma expressão condicional:
JavaScript
condicao ? valorSeVerdadeiro : valorSeFalso
Use o código com cuidado.

7. Operador de String:
Concatenação: + (une duas strings: ex: "Olá" + " mundo")
Exemplos
JavaScript
let x = 10;
let y = 5;

// Operações aritméticas
let soma = x + y;
let subtracao = x - y;

// Operadores de comparação
let maior = x > y;

// Operador lógico
let eLogico = (x > 5) && (y < 10);

// Operador ternário
let resultado = (x % 2 === 0) ? "Par" : "Ímpar";

// Concatenação de strings
let mensagem = "O valor de x é: " + x;
Use o código com cuidado.

Precedência de Operadores
A ordem em que as operações são realizadas é definida pela precedência dos operadores. Por exemplo, a multiplicação tem precedência sobre a adição. Para controlar a ordem das operações, você pode usar parênteses.
