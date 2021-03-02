const val MIN_AGE = 16
const val MAX_AGE = 68
//Operadores lógicos e operadores In e Range
fun main(){
        
    /*val bingo = listOf(8, 6, 34, 13)
    var number = (1..34).random() //O radom vai selecionar um numero aleatório e vai atribuir a number.
    
    println(number)
    println(number in bingo)*/
    
    var age = (10..100).random()
    println(age)
    println(age in MIN_AGE..MAX_AGE)
    println(age >= MIN_AGE && age <= MAX_AGE)
}