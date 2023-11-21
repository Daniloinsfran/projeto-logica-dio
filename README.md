# projeto-logica-dio

let nomeNoCadastro = "Danilo Insfran"
let nickname = "Peh-De-Pano"
let sexo =("H")
let idade =("33")
let xp = "3500" 
let nivel;

if (xp <= 1000) {
    nivel = "Ferro";
} else if (xp <= 2000) {
    nivel = "Bronze";
} else if (xp <= 5000) {
    nivel = "Prata";
} else if (xp <= 7000) {
    nivel = "Ouro";
} else if (xp <= 8000) {
    nivel = "Platina";
} else if (xp <= 9000) {
    nivel = "Ascendente";
} else if (xp <= 10000) {
    nivel = "Imortal";
} else {
    nivel = "Radiante";
}


console.log("Bem vindo ")
console.log(nomeNoCadastro)



console.log("Você Entrou no servidor com o Herói:")

console.log(nickname)

console.log(sexo)

console.log(idade)

console.log("Level: " + nivel)
