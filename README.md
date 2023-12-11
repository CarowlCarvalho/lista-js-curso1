#Programação é prática! Criamos mais uma lista de atividades (não obrigatórias) para você exercitar e reforçar ainda mais seu aprendizado.Bora praticar?

1)Crie uma função que receba o nome de uma pessoa como argumento e retorne uma saudação personalizada. Em seguida, chame a função e exiba a saudação no console.
```
function saudacaoPersonalizada(nome) {
    return `Olá, ${nome}! Como vai?`;
}

const nomeDaPessoa = "Ana";
const saudacao = saudacaoPersonalizada(nomeDaPessoa);

console.log(saudacao); // Saída: Olá, Ana! Como vai?
```

2)Função para Verificar Maior Idade:
Crie uma função que receba a idade de uma pessoa e retorne se ela é maior de idade (idade >= 18). Imprima o resultado no console.

```
function adulto(idade) {
    if (idade >= 18) {
        return "É maior de idade.";
    } else {
        return "É menor de idade.";
    }
}

console.log(adulto(25)); // É maior de idade.
console.log(adulto(15)); // É menor de idade.

```
3)Crie uma função que receba uma string e verifique se é um palíndromo (uma palavra que é lida da mesma forma de trás para frente). Retorne true se for um palíndromo e false caso contrário. Imprima o resultado no console.

```
function verificaPalindromo(str) {
    const reversedStr = str.split('').reverse().join('');
    return str.toLowerCase() === reversedStr.toLowerCase();
}

console.log(verificaPalindromo("arara")); // true
console.log(verificaPalindromo("Frase")); // false
```

4)Crie uma função `calculadora` que receba dois números e um operador (+, -, *, /). Realize a operação desejada e retorne o resultado. Imprima o resultado no console.

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

5)Crie uma função que receba três números como parâmetros e determine qual é o maior entre eles. Utilize estruturas condicionais (if, else) para comparar os valores e determinar o maior. Imprima o maior valor no console.
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

6)Crie uma arrow function chamada `calcularPotencia` que receba dois parâmetros: a base e o expoente. A função deve calcular a potência da base elevada ao expoente e retornar o resultado.

```
const calcularPotencia = (base, expoente) => {
    return Math.pow(base, expoente);
};

const base = 2;
const expoente = 3;

const resultado = calcularPotencia(base, expoente);
console.log(`O resultado de ${base} elevado a ${expoente} é: ${resultado}`); // Saída: O resultado de 2 elevado a 3 é: 8
```
