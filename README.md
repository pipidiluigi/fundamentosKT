# /*
fun main() {
   //Tipos de variáveis: 
    //
    //String - armazena valores de tipo texto - dentro de ""  ==> ex: "abóbora" 
    //Int - armazena números inteiros ==> 7042
    //Float - armazena números reais (no geral) - necessita de um f no valor ==>72.24f
    //Double - armazena números quebrados(de forma arredondada) ==> 7.15
    //Long - armazena números longos ==> 54564386546546.784486
    //Boolean - verdadeiro ou falso ==> true, false
    
    var cr7 = "Cristiano Ronaldo" 
    var numeroChampions = 5 
    var altura = 1.87
    
    //Concatenação
    
    print("O nome dele é " + cr7 + ", ele tem " + numeroChampions)
    println(" titúlos de Champions League e ele tem " + altura + " de altura SIIIIUU eu sou u miliorr")
    
    var laPulga = "Lionel Messi"
    var champions = 4
    var alturaDele = 1.02
    
    print("O nome dele é $laPulga, ele tem $champions títulos de chamions, ")
    println("e ele tem apenas $alturaDele de altura")
    
    //Faça uma apresentação de si mesmo, usando no mínimo 
    //5 variáveis e usando o método de concatenação
    
    val nome = "José"
    val sobrenome = "Nestor"
    val dia = 5 
    val mes = "junho"
    val ano = "1575 a.C." 
    
    println("Olá, meu jovem, meu nome é $nome  $sobrenome e eu nasci no dia $dia de $mes de $ano")
    
   
    //Operadores matemáticos
    //
    // + => adição
    // - => subtração
    // / => divisão
    // * => multiplicação
    // % => módulo - o resto de uma divisão
    
    //println(15 % 2) 
    //
    //Operadores Relacionais 
    //
    //
    // == => igual a...
    // != => diferente de...
    // > => maior que... 
    // < => menor que...
    // >= -> maior ou igual a...
    // <= -> menor ou igual a...
    
    
    
    
    
}

 //Desafio Calculadora: fazer um programa qe simule	uma calculadora
 // deve ter pelo menos 2 variaveis de tipo Int e pelo menos 4 println's
 // cada um obtendo um calculo diferente(adição, subtração, multiplicação
 // e divisão) que relacionam as duas variaveis neste cálculo  :)
 // 
 // 
 // 
 var n1 = 2
 var n2 = 4


println("  ************---------************")
println("**                               **")
println("**                               **")
println("**        minha Calculadora!!    **")
println("**                               **")
println("** Adição entre $n1 e $n2        **")
println("** O resultado da adição é:      **")
println("**                               **")

*/
...............................................................................................

fun main() {
    /*
     //Condições
     //
     //condições simples
     //
     // if--> se...
}    // else --> senão

     var lembreiDoChocolate = "sim"

     if(lembreiDoChocolate == "Sim"){
         println("Vou entregar o chocolate para você")
     }else{
         println("Chocolate pra todo mundo !!")
     }    
     //se a condição for verdadeira, a sua ação será executada, senão, outra ação será
     //executada
     // Exercício ---> Faça uma comparação, usando uma variàvel e o if...else, se essa
     // comparação for verdadeira, um resultado deverá ser impresso, senão, outro(resultado)
     // será impresso
     //
     //Condições composto
     
     var corações = 1
     if(corações == 5){
         println("Você está ótimo!! Bom pra vc")
     }else if(corações == 4){
         println("vc esta bem")
     }else if(corações == 3){
         println("ce ta ok, pode comer algo")
     }else if(corações == 2){  
         println("vai se cuidar URGENTE")
     }else if(corações == 1){
         println("voce esta morrendo!!")
     }else{
         println("parabéns você é o novo reforço do vascão")
     }
     */
     
     
fun main() {
    //Operadores Lógicos
    //
    //são usados quando queremos comparar mais de uma coisa na mesma condição
    //
    // && -> e
    // || -> ou (shift = barra invertida)
    // 
    // TABELA VERDADE (com E e OU)
    // 
    // && - a determinada ação só acontecerá se e somente se todas as 
    //  condição forem verdadeiras
    // 
    // VV -> verdadeiro
    // VF -> falso
    // FV -> falso
    // FF -> falso
    // 
    // || - a determinada ação sera executada se pelo menos uma das condições forem verdadeiras
    // 
    // VV -> verdadeiro
    // VF -> verdadeiro
    // FV -> verdadeiro
    // FF -> falso
    // 
    /*
    
    var idade = 14 
    var acompanhadoDosPais = true
    
    
    if(idade >= 14 && acompanhadoDosPais == true){
        println("pode entrar, curte ai")
    }else{
        println("vaza mlk de bar")
    }
    */
    //Exercício - A seleção brasileira esta correndo risco de ser eliminada na fase de grupos
    //da copa do mundo, o brasil, so pode classificar se a alemanha perder, e se o proprio brasil
    //ganhar. as partidas ja passaram quero saber se o brasil passou
    //
    
    var AlemanhaPerde = false
    var BrasilGanhou = false
    
    
    if(AlemanhaPerde >= true || BrasilGanhou == true){
        println("isso o Brasil se classificou")
    }else{
        println("poxa, o brasa perdeu")
    }  
}

     var idade = 18 
    
     if(idade <= 3){
         println("Você é um nenê")
     }else if(idade <= 12){
         println("tu é criança")
     }else if(idade <= 18){
         println("vc é jovem, aproveite a vida")
     }else if(idade <= 60){
         println("tu é um adulto")
     }else if(idade > 60){
         println("tu é véi")
     }else{
         println("vasco.")
