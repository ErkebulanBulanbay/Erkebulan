Task 1
//This is example show extension function Int:pow raise to exponent.
fun Int.pow(exponent:Int):Int{
//According math rules any numbers raise to exponent 0 equal 1.
if (exponent ==0) return 1
//Pow принимает Int как степень возвращает результат числа в степень,
если степень равна 0, функция возвращает 1, так как любое число в степени 0 равно 1
Task 2
//PowAndThen is extension function for the Int.resultLambda function reciving and returning to Unit 
fun Int.PowAndThen(exponent:Int,
resultLambda:(Int)->Unit) {