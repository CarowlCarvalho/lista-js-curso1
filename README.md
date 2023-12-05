#Programação é prática! Criamos mais uma lista de atividades (não obrigatórias) para você exercitar e reforçar ainda mais seu aprendizado.Bora praticar?

#### Desafios


Criando Variáveis:
1)Declare três variáveis diferentes (uma para cada tipo: string, número e booleano) e atribua valores a elas. Em seguida, exiba o tipo de cada variável no console.

```
let myString = "Olá, mundo!";
let myNumber = 42;
let myBoolean = true;

console.log(typeof myString); // String
console.log(typeof myNumber); // Number
console.log(typeof myBoolean); // Boolean
```

2)Concatenação de Strings:
Crie duas variáveis contendo seu primeiro e último nome. Em seguida, combine-as em uma terceira variável e imprima o resultado.

```
let firstName = "João";
let lastName = "Silva";
let fullName = firstName + " " + lastName;

console.log(fullName); // João Silva
```

3)Operações Aritméticas:
Crie duas variáveis numéricas e realize operações matemáticas básicas (adição, subtração, multiplicação, divisão e resto) entre elas. Imprima os resultados.

```
let num1 = 10;
let num2 = 5;

console.log(num1 + num2); // Soma: 15
console.log(num1 - num2); // Subtração: 5
console.log(num1 * num2); // Multiplicação: 50
console.log(num1 / num2); // Divisão: 2
console.log(num1 % num2); // Resto da divisão: 0
```

4)Função de Saudação:
Crie uma função que receba o nome de uma pessoa como argumento e retorne uma saudação personalizada. Em seguida, chame a função e exiba a saudação no console.

```
function greet(name) {
    return "Olá, " + name + "!";
}

console.log(greet("Ana")); // Olá, Ana!
```

5)Função para Verificar Maior Idade:
Crie uma função que receba a idade de uma pessoa e retorne se ela é maior de idade (idade >= 18). Imprima o resultado no console.
```
function checkAdultAge(age) {
    if (age >= 18) {
        return "É maior de idade.";
    } else {
        return "É menor de idade.";
    }
}

console.log(checkAdultAge(25)); // É maior de idade.
console.log(checkAdultAge(15)); // É menor de idade.

```

6)Manipulação de String:
Crie uma variável contendo uma frase. Em seguida, exiba no console o comprimento da frase e a mesma frase em letras maiúsculas.
```
let frase = "Esta é uma frase de exemplo.";
console.log(frase.length); // Comprimento da frase
console.log(frase.toUpperCase()); // Frase em letras maiúsculas

```

7)Operador Ternário:
Crie uma variável numérica com um valor. Utilize um operador ternário para verificar se esse valor é par ou ímpar. Exiba o resultado no console.
```
let numero = 7;
let resultado = numero % 2 === 0 ? "Par" : "Ímpar";
console.log(resultado); // Par ou Ímpar
```

8)Calculadora Simples:
Crie uma função que receba dois números e um operador (+, -, *, /). Realize a operação desejada e retorne o resultado. Imprima o resultado no console.

```
function calculadora(num1, num2, operador) {
    switch (operador) {
        case "+":
            return num1 + num2;
        case "-":
            return num1 - num2;
        case "*":
            return num1 * num2;
        case "/":
            return num1 / num2;
        default:
            return "Operação inválida.";
    }
}

console.log(calculadora(10, 5, "+")); // 15
console.log(calculadora(8, 4, "*")); // 32

```

9)Verificação de Palíndromo:

Crie uma função que receba uma string e verifique se é um palíndromo (uma palavra que é lida da mesma forma de trás para frente). Retorne true se for um palíndromo e false caso contrário. Imprima o resultado no console.

```
function verificaPalindromo(str) {
    const reversedStr = str.split('').reverse().join('');
    return str.toLowerCase() === reversedStr.toLowerCase();
}

console.log(verificaPalindromo("arara")); // true
console.log(verificaPalindromo("Frase")); // false
```

10)Maior Valor entre Números:
Crie uma função que receba três números como parâmetros e determine qual é o maior entre eles. Utilize estruturas condicionais (if, else) para comparar os valores e determinar o maior. Imprima o maior valor no console.
```
function encontraMaiorValor(num1, num2, num3) {
    let maior = num1; // Assumindo inicialmente que num1 é o maior

    if (num2 > maior) {
        maior = num2;
    }

    if (num3 > maior) {
        maior = num3;
    }

    return maior;
}

console.log(encontraMaiorValor(12, 56, 32)); // 56

```

