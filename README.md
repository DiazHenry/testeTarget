# Teste Target 

//A resposta da primeira pergunta eh 13 para ambas as variaveis K e SOMA, ja que ambas foram instanciadas como 0 e alem do processamento ser SINCRONO
"""let K = 0;
let SOMA = 0;
let indicie = 13;
for (let i = 0; i < 13; i++) {
  K++;
  SOMA += K;
}"""


//Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores |
//(exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, 
//ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência.

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

a) 1, 3, 5, 7, 9

b) 2, 4, 8, 16, 32, 64, 128

c) 0, 1, 4, 9, 16, 25, 36, 49

d) 4, 16, 36, 64, 100

e) 1, 1, 2, 3, 5, 8, 13

f) 2,10, 12, 16, 17, 18, 19, 200


4) Eu nao posso ver a lampada da sala em que estou mas imagino que eu a possa tocar. Ligaria dois interruptores e verificaria se a lampada da minha sala esquenta
se ela esquenta e na unica outra sala em que posso ir ela esta apagada, sei que o interruptor que sobrou liga aquela luz, 
voltando para minha sala, eu eliminaria o interruptor que ja sei
de qual sala eh e entao desligaria um interruptor e entao saberia qual controla a luz da minha sala.
PS: Nao sei se essa solucao seria possivel levando em consideracao a descricao do problema, ja que eu nao consigo ver a luz da minha sala e so posso ir duas vezes a uma das outras duas salas.

{function inverterString(str) {
    let stringReversa = "";
    for (let i = str.length - 1; i >= 0; i--) {
        stringReversa += str[i];
    }
    return stringReversa;
}
}
