# Teste Target 

1) //A resposta da primeira pergunta eh 13 para ambas as variaveis K e SOMA, ja que ambas foram instanciadas como 0 e alem do processamento ser SINCRONO
```
let K = 0;
let SOMA = 0;
let indicie = 13;
for (let i = 0; i < 13; i++) {
  K++;
  SOMA += K;
}
```


2) //Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores |
//(exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, 
//ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência.
```
function fibonacci(n) {
    if (n <= 1) {
        return n;
    }
    return fibonacci(n - 1) + fibonacci(n - 2);
}

function isFibonacci(n) {
    for (let i = 0; fibonacci(i) <= n; i++) {
        if (fibonacci(i) === n) {
            return true;
        }
    }
    return false;
}

let num = 13; // Número a ser verificado
if (isFibonacci(num)) {
    console.log("O número informado pertence à sequência de Fibonacci.");
} else {
    console.log("O número informado não pertence à sequência de Fibonacci.");
}
```
3)
a) 1, 3, 5, 7, 9

b) 2, 4, 8, 16, 32, 64, 128

c) 0, 1, 4, 9, 16, 25, 36, 49

d) 4, 16, 36, 64, 100

e) 1, 1, 2, 3, 5, 8, 13

f) 2,10, 12, 16, 17, 18, 19, 200


4) Na primeira ida para a sala das lampadas ligaria dois interruptores e dado isso eu saberia que o interruptor que esta desligado controla a unica lampada desligada .
   Na segunda ida para lampada, eu desligaria mais um interruptor alem do que eu ja soubera qual lampada ele controla e portanto eu saberia qual interruptor controla qual lampada.

6)
```
function inverterString(str) {
    let stringReversa = "";
    for (let i = str.length - 1; i >= 0; i--) {
        stringReversa += str[i];
    }
    return stringReversa;
}
```

