# TADS-043

// FLUXOGRAMA DE ALGORITMO

function verificarParOuImpar(numero) {
    if (numero % 2 === 0) {
        console.log("O número é par");
    } else {
        console.log("O número é ímpar");
    }
}
verificarParOuImpar(4); // Saída: O número é par
verificarParOuImpar(7); // Saída: O número é ímpar

// TIPOS PRIMITIVOS

// String
let primeiroNome = "Maria";
let segundoNome = "Silva";
let nomeCompleto = primeiroNome + " " + segundoNome;
console.log(nomeCompleto);
// Saída: Maria Silva

// Boolean
let Adulto = true;
if (Adulto) {
    console.log("É adulto");
} else {
    console.log("Não é adulto");
}

// ESTRUTURAS CONDICIONAIS

let idade = 20;

if (idade < 13) {
    console.log("Criança");
} else if (idade < 18) {
    console.log("Adolescente");
} else if (idade < 60) {
    console.log("Adulto");
} else {
    console.log("Idoso");
}

// ARRAY

let frutas = ["Maçã", "Banana", "Laranja"];
console.log(frutas[0]); // Saída: Maçã
console.log(frutas[1]); // Saída: Banana
console.log(frutas[2]); // Saída: Laranja

// FUNÇÕES

function saudacao(nome) {
    return `Olá, ${nome}!`;
}
console.log(saudacao("João")); // Saída: Olá, João!

// OBJETOS
let pessoa = {
    nome: "João",
    idade: 30,
    profissão: "Engenheiro"
};
console.log(pessoa);
// Saída: { nome: 'João', idade: 30, profissão: 'Engenheiro' }

