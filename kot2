fun main() {
    var count = 0
    var sum = 0
    var number: Int
    println("Введите числа (для завршения введите 0):")
    do{
        number = readln().toInt()
        if (number != 0) {
            sum += number
            count++
        }
    } while (number != 0)
    if (count > 0) {
        val average = sum.toDouble() / count
        println("Количество введенных чисел: $count")
        println("Общая сумма чисел: $sum")
        println("Среднее арифметическое: $average")
    } else {
        println("Вы не ввели ни одного числа")
    }
}
