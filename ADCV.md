# CV
## About me:
I'm a student of the best IT-university in the World (: - )) (Belarusian State University of Informatics and Radioelectronics). 
I'm actively learning Androig using programming languages Kotlin \ java and with a wide variety of android libraries.
I'm a 3nd year student at the university now. 
I use all learning methods for impoving my skills: textbooks, searching google, reading documentaion, watching video-guides on YouTube, a.o. 
All this, I practice everything, that i learnt.

## My skills:
* Basis knowledge: 


HTML + CSS
![image](https://user-images.githubusercontent.com/71211299/137466836-6bfdb406-68d0-4b1a-a54a-a00ecf024201.png)


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
## Contact info:
I'm [Dmitriy Korzhovnik](https://vk.com/dietmargrandarisingcosmosalexman)
- Discord: Dietmar Granda#5636
- [Github](https://github.com/8DietmarBarbarossa8)
- Telegram: Dietmar_Granda
- [LinkedIn](https://www.linkedin.com/in/dmitriy-korzhovnik-43a256210/)
