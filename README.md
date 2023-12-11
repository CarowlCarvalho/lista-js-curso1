#Programação é prática! Criamos mais uma lista de atividades (não obrigatórias) para você exercitar e reforçar ainda mais seu aprendizado.Bora praticar?

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
Crie duas variáveis, uma contendo seu primeiro nome e outra contendo seu último nome. Em seguida, combine-as em uma terceira variável usando tanto o operador + quanto template strings. Por fim, imprima o resultado obtido.

```
let primeiroNome = "SeuPrimeiroNome";
let ultimoNome = "SeuUltimoNome";

// Usando o operador +
let nomeCompleto= primeiroNome + " " + ultimoNome ;
console.log("Usando operador +:", nomeCompleto);

// Usando template strings
let nomeCompleto= `${primeiroNome } ${ultimoNome }`;
console.log("Usando template strings:", nomeCompleto);
```

3)Declare duas variáveis, uma contendo um número e outra contendo uma string. Em seguida, combine-as em uma terceira variável usando template strings e exiba o resultado no console.

```
let numeroVar = 42;
let stringVar = "OpenAI";

let juncaoVar = `${numeroVar } é o número da resposta da ${stringVar}`;
console.log(juncaoVar );
```
4)Crie uma variável inicializada com um valor e, em seguida, reatribua um novo valor a essa variável. Depois, imprima ambos os valores no console.
```
let minhaVariavel= "Primeiro valor";
console.log(minhaVariavel);

minhaVariavel= "Novo valor";
console.log(minhaVariavel);
```

5)Declare uma variável fora de um bloco de código (por exemplo, if, for, while) e outra dentro desse bloco. Tente acessar essas variáveis dentro e fora do bloco e exiba seus valores no console.
```
let outsideBlock = "Fora do bloco";

if (true) {
    let insideBlock = "Dentro do bloco";
    console.log(outsideBlock); // Acesso à variável fora do bloco dentro do bloco
    console.log(insideBlock); // Acesso à variável dentro do bloco dentro do bloco
}

console.log(outsideBlock); // Acesso à variável fora do bloco fora do bloco
// console.log(insideBlock); // Tentativa de acesso à variável dentro do bloco fora do bloco gera um erro
```


