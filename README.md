#Programação é prática! Criamos mais uma lista de atividades (não obrigatórias) para você exercitar e reforçar ainda mais seu aprendizado.Bora praticar?

1)Crie uma variável contendo uma frase. Em seguida, exiba no console o comprimento da frase e a mesma frase em letras maiúsculas.
```
let frase = "Esta é uma frase de exemplo.";
console.log(frase.length); // Comprimento da frase
console.log(frase.toUpperCase()); // Frase em letras maiúsculas
```

2)Declare uma variável booleana que informa se está chovendo e utilize-a em uma estrutura condicional (if) para exibir uma mensagem informando se é preciso levar um guarda-chuva ou não dependendo do valor da variável.
```
let estaChovendo = true;

if (estaChovendo) {
    console.log("É melhor levar um guarda-chuva!");
} else {
    console.log("O tempo está bom, sem necessidade de guarda-chuva.");
}
```
3)Declare duas variáveis, uma inicializada com valor null e outra que não recebe atribuição (resultando em undefined). Exiba os valores no console.
```
let valorNull = null;
let valorUndefined;

console.log("Valor de valorNull:", valorNull); // Saída: null
console.log("Valor de valorUndefined:", valorUndefined); // Saída: undefined
```

4)Crie uma variável numérica e uma string. Realize a conversão da variável numérica para string e da string para número. Exiba os tipos de dados resultantes no console.
```
let numero = 42;
let texto = "10";

let numeroConvertido = String(numero);
let textoConvertido = Number(texto);

console.log("Tipo de dado após conversão de número para string:", typeof numeroConvertido);
console.log("Tipo de dado após conversão de string para número:", typeof textoConvertido);
```

5)Crie uma variável com uma string e utilize métodos de manipulação de strings, como toUpperCase, toLowerCase e slice, para modificar a string original. Exiba os resultados finais no console.
```
let texto = "JavaScript é incrível!";

let maiusculas = texto.toUpperCase();
let minusculas = texto.toLowerCase();
let parteDaString = texto.slice(0, 10);

console.log("Texto em maiúsculas:", maiusculas);
console.log("Texto em minúsculas:", minusculas);
console.log("Parte da string:", parteDaString);
```
6) Crie 3 variáveis de tipos diferentes e depois utilize template strings para combinar diferentes tipos de dados (number, string, boolean) em uma única string e exiba o resultado no console.
```
let numero = 42;
let texto = " é a resposta.";
let booleano = true;

let combinacao = `${numero}${texto} É verdade? ${booleano}`;
console.log(combinacao);
```
