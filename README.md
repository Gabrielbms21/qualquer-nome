# qualquer-nome/**
 * You can edit, run, and share this code.
 * play.kotlinlang.org
 */
fun main() {
    //println("Hello, world!!!")
    //variaveis
//
//var - mutavel-seu valor pode ser alterado
//val - não mutavel - não é possivel altera o seu valor
//
//tipos variaveis
//
//boolean - verdadeiro ou falso ---> true ou false
//string - qualquer texto  de qualquer tamanho dentro de "" ---> ex: "Pizza"
//char - APENAS UM caractere dentro de '' ---> ex: 'g'
//Int - Número inteiros ---> ex: 6
// Double - números decimais (de forma arredondada) ---> ex 71.23
// long - números reais (de forma longa) ---> ex: 5000000000000000000
// Float - números decimais (de forma definitiva) ---> ex: 71.2314165646
// 
// Estrutura de uma variavel
// 
// var
// 
// var nomeDela = "valor"
// var nomeDela: String
// 

//Concatenação
var messiGoldenBall = 7

println("O Messi já ganhou" + messiGoldenBall + " vezes a Bola de Ouro")
println("O Messi já ganhou $messiGoldenBall vezes a Bola de Ouro")


---------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------






/**
 * You can edit, run, and share this code.
 * play.kotlinlang.org
 */
fun main() {
    println("Hello, world!!!")
    //
    //Operadores Relacionais
    //
    //são sinais que auxiliam em comparações entre valores
    //
    // = --> para definir valores
    // = --> comparação de igualdade
    // ! --> diferença 
    // > --> maior que...
    // < --> menor que...
    // 
    // Operadores matemático
    // + --> adição
    // - --> subtração
    // * --> multiplicação
    // / --> divisão
    // % --> módulo - o resto de uma divisão
    //++ --> adiciona 1 a um valor
    //-- --> subtrai 1 de um valor
    
    // Condições
    // if..else --> se.. senão
    // 
    // Estrutura do if..else simples
    // 
    // if(condição)
    // ação a ser executada
    // 
    
    var classificado = "Laker"
    
    if(classificado == "Lakers"){
        println ("Lakers classificado para a final, NBA")
    }else{
        println("Chicago bulls classificado para a final, infelizmente")
    }
    
    // if... else composto
    // 
    // estrtura:
    // if(condição)
    // ação
    // }else if (condição){
    // ação
    // }else{
    // ação
    // }
    
    
   var vidas = 5
   
   if (vidas >= 5){
       println("Vocé está excelente!! que vida boa!!")
     }else if (vidas == 4){
       println("vocé ta muito bem!! pode comer miojo :>)")
     }else if (vidas == 3){
       println("vocé ta ok, mas pode melhorar")
     }else if (vidas ==2){
       println("tá tudo bem ai??")
     }else if (vidas ==1){
       println("cé ta morrendo!! se cuida man")
     }else{
       println ("vocé não existe")
      
      // Exercício 1 - Faça um programa que verifique dois números e indique
      // no console, o maior entre eles
      
      //Exercíos 2 - faça um programa que indique no console, se um número
      //verificado é positivo ou negativo
      
      // .Nos exercícios, devem ser utilizadas pelo menos 1 variável
      // .Os exercícios devem ser feito com if...else
      // .Divirtam-se ><
      // 
      var sorvete = 3
      var chocolate = 7
      
      if (sorvete > chocolate){
        println("o número $sorvete é maior que $chocolate")
      }else{
          println("o número $chocolate é maior que $sorvete")
      }
       ---------------------------------------------------------------------------------------------------------------
       =------------------------------------------------------------------------------------------------------------
       -------------------------------------------------------------------------------------------
       fun main() {
    //
    /*
    var minecraft = 0
    
    if(minecraft > 0){
         println("O $minecraft é  um numero positivo")
    }else if(minecraft < 0){
         println("O $minecraft é um numero negativo")
    }else{
        println("O $minecraft não é nem positivo e nem negativo ")
    */ 
      
    
    
    // Operadores Lógicos
    // 
    // são usados para comparar mais de um valor na mesma condição
    // 
    // && --> e (SHIFT + 7) ><
    // || --> ou (SHIFT + A barrinha invertida  ao lado dele)(PIPELINE)
    // 
    // TABELA VERDADE
    // e... --> para que o resultado seja verdadeiro, todas as condições  precisam ser
    // verdadeiras
    // 
    // VV - V
    // VF - F
    // FV - F
    // FF - F
    // ou... --> para que o ressultado seja verdadeiro, pelo menos ma condição deve ser
    // verdadeira 
    // 
    // VV - V
    // VF - V
    // FV - V
    // FF - F
    //
    /*
    var coracoes = 9
    var vidas = 1
    if(vidas <= 0 && coracoes <= 0){
         println("Você vai para a tela de Game Over")
    }else{
         println("-----O jogo será reiniciado-----")

    */
    
    //When - Quando...
    //Quandoo um determinado valor for verdadeiro, uma determinada ação
    //será executado
    //
    //Estrutura do When
    //
    //when(var a ser comporada)
    //valor -->(ação)
    //valor -->(ação)
    //valor -->(ação)
    //else --> (ação)
    // }
    /*
    var mes = 11
    when(mes){
        1 -> {println("Janeiro")}
        2 -> {println("Fevereiro")}
        3 -> {println("Março")}
        4 -> {println("Abril")}
        5 -> {println("Maio")}
        6 -> {println("Junho")}
        7 -> {println("Julho")}
        8 -> {println("Agosto")}
        9 -> {println("Setembro")}
        10 ->{println("Outubro")}
        11 ->{println("Novembro")}
        12 ->{println("Dezembro")}
       else ->{println("Mês inválido")}
    */
    // Laços de repetição
    // 
    // While - Enquanto
    // do..While - faça... enquanto
    // for - para
    // repeat - repita
    // 
    //while -->enquanto uma condição verdadeira, uma determinada
    //ação é executada, até que não seja mais verdadeira
    //
    var bolo = 500
    
    while(bolo <= 520){
        println(bolo)
        bolo++
    }
    
    //do.. while --> ele vai executar uma determinada ação
    //enquanto uma condição for verdadeira
    println("")
    do{
        println(bolo)
        bolo++
    }while(bolo > 520)

}
    
------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------

fun main() {
    
/*
 //
 //exercício <3
 //
 //Exiba a porcentagem da bateria descarregando a cada linha no console
 //Quando a bateria chegar a 15%, deve ser exibida a porcentagem e também
 //O aviso de bateria descarregada,
 //Quando a bateria chegar a 0%, deve ser exibida a porcentagem e tambem
 //O aviso de celular desligando usando WHILE ou do..WHILE
 //
 //

 var bateria = 100

 while(bateria >= 0){
     println("${bateria}%")
  
    when(bateria){
        15 -> {println("Celular Descarregando, faça algo!")}
        0 -> {println("Celular Desligando, dando tchauzinho ")}
    }
      bateria-- 
 }
 */
  
 
  // for - para...
    
    for(churrasco in 0..10){
        println(churrasco)
    }



 // exercícios - Exibir uma tabuada de um escolhido(não pode ser a do 1,e do 2) utilizando
 // o laço for 5
 
 //☻
 

}
-----------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------

fun main() {
 /*   
   for(i in 1..10){
       println(i*50)
   }

*/
    // repeat -> repita
    //  
    // repetir uma determinada sequencia de ações, em determinada quantidade de vezes
    // 
    // repeat(vezes){
    // ação
    // }  
    /*
    repeat(20){
        println("Guts muito foda ☻")
    }
    */
    // exercício = exiba os números de 20 a 0 (nesta ordem) usando o laço repeat
    var Guts = 20
    repeat(21){
        println(Guts)
        Guts--
    }






}









      
      
      
    
   
       
     
   
    
    
    
    
    
    
    
    
    
    
    
    
   }
    }



   

}
