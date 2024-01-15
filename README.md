# JS-DIO_Potencia_TechI_IFood-Programa-o_do_Zero
Criando uma variável para armazenar o nome e a quantidade de experiência (XP), utilizando uma estrutura de decisão para apresentar.

// Variáveis para armazenar o nome e XP do herói (substitua os valores conforme necessário)
const nomeDoHeroi = "Seu Heroi";
const xpDoHeroi = 7000;

// Utilizando uma estrutura de decisão para determinar o nível do herói
let nivelDoHeroi;

if (xpDoHeroi < 1000) {
    nivelDoHeroi = "Ferro";
} else if (xpDoHeroi <= 2000) {
    nivelDoHeroi = "Bronze";
} else if (xpDoHeroi <= 5000) {
    nivelDoHeroi = "Prata";
} else if (xpDoHeroi <= 7000) {
    nivelDoHeroi = "Ouro";
} else if (xpDoHeroi <= 8000) {
    nivelDoHeroi = "Platina";
} else if (xpDoHeroi <= 9000) {
    nivelDoHeroi = "Ascendente";
} else if (xpDoHeroi <= 10000) {
    nivelDoHeroi = "Imortal";
} else {
    nivelDoHeroi = "Radiante";
}

// Imprime a mensagem final
console.log("O Herói de nome " + nomeDoHeroi + " está no nível de " + nivelDoHeroi);
