let victori= 100
let derrota = 55
let name = " isaque "
//puxando a
contadorDeVitoria (  victori ,derrota)

//funsão 1 .

function contadorDeVitoria( victori , derrota){
    
   let contador = victori - derrota
    let elo ;
    
    
    if (contador === 10){
         elo = "ferro"
        
    }
    else if (contador <=20  ){
        elo = "Bronze"
    }
    else if (contador <= 50  ){
        
        elo = "Prata"
    }
    else if (contador <=80  ){
        elo = "Ouro"
    }
    
    else if (contador <=90  ){
        elo = "Diamante"
        
    }
    else if (contador <=100  ){
        elo = "Lendario"
    }
    else if (contador >= 101)
    
    elo = "Imortal"
    
    
    console.log("O heroi de nome " + name , " tem um saldo de vitoria de " + contador , " e está no nivel " + elo , "." )
    
    return contador , elo
}



