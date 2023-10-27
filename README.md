# desafio-2
//calculadora de partidas rankeadas

let vitoria = 28
let derrota = 10
let saldo = vitoria - derrota
let nivel =" "
function resultado (saldo){
    if (vitoria < 10){
        nivel = 'Ferro'
    }else if (vitoria >= 11 <= 20){
        nivel = 'Bronze'
    }else if (vitoria >= 21 <= 50){
        nivel = 'Prata'
    }else if (vitoria >= 51 <= 80){
        nivel = 'Ouro'
    }else if (vitoria >= 81 <= 90){
        nivel = 'Diamante'
    }else if (vitoria >= 91 <= 100){
        nivel = 'Lendário'
    }else if (vitoria > = 101){
        nivel = 'Imortal'
    }
}
console.log('O Herói tem o saldo de {} está no nível {}.' + saldo, nivel)
