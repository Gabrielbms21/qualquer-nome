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
      
      
      
      
    
   
       
     
   
    
    
    
    
    
    
    
    
    
    
    
    
   }
    }



   

}
