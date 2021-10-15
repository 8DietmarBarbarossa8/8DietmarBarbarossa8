# CV
## Contact info:
I'm [Dmitriy Korzhovnik](https://vk.com/dietmargrandarisingcosmosalexman)
- Discord: Dietmar Granda#5636
- [Github](https://github.com/8DietmarBarbarossa8)
- Telegram: Dietmar_Granda
- [LinkedIn](https://www.linkedin.com/in/dmitriy-korzhovnik-43a256210/)

## Short bio:
I'm a student of the best it-university in the World and like Android-development. 
I want to learn Android with active using programming language Kotlin. I try to combine the qualities of independent and team work.
I'm a 2nd year student at the university. 4 months of studying java \ kotlin and 2 months of working with Andoid Studio.
In free time self-study programming language from textbooks, searching google, reading documentaion and practice

## My skills:
PL Java and Kotlin
Gook knowledge on VCS Git, Algorithm, Data Structure, 
IDE Intelllij Idea and Android Studio, OOP, Lambda, JVM, Design patterns, etc.
My english level about A2-B1. I can read and understand documentation.

## Example of solved task from Codewars (4 kyu)
```kotlin
object SumSquaredDivisors {
    fun listSquared(m: Long, n: Long): String {
        val result = mutableListOf<String>()
        for (i in m..n){
            val square = findAllDivisorsInSquare(i).sum()
            if ((kotlin.math.sqrt(square.toDouble()) * 10 % 10) == 0.0)
                result.add("[$i, ${square}]")
        }
        return result.joinToString( prefix = "[", postfix = "]")
    }

    private fun findAllDivisorsInSquare(n: Long): Set<Long> {
        val set: MutableSet<Long> = mutableSetOf(1, n * n)
        for (i in 2 until kotlin.math.sqrt(n.toDouble()).toLong() + 1)
            if (n % i == 0L){
                set.add(i * i)
                val buf = (n.toDouble() / i).toLong()
                set.add(buf * buf)
            }
        return set
    }
}
```




