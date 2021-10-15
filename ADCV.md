# CV
## About me:
I'm a student of the best IT-university in the World (: - )) (Belarusian State University of Informatics and Radioelectronics). 
I'm actively learning Androig using programming languages Kotlin \ java and with a wide variety of android libraries.
I'm a 3nd year student at the university now. 
I use all learning methods for impoving my skills: textbooks, searching google, reading documentaion, watching video-guides on YouTube, a.o. 
All this, I practice everything, that i learnt.

## My skills:
Basis knowledge (needed: Java, Kotlin, XML, SQL, Git) and optional: HTML, CSS, C++


<img src="https://user-images.githubusercontent.com/71211299/137467114-a9b19cdc-4a29-475d-97d1-0ce4e34e36c7.png" width="100" height="120"><img src="https://user-images.githubusercontent.com/71211299/137467160-f4d554ea-abaa-47c4-9158-41f37a63ac46.png" width="120" height="120"><img src="https://user-images.githubusercontent.com/71211299/137467208-35a9a79b-f33c-4658-895e-97f184163da2.png" width="120" height="120"><img src="https://user-images.githubusercontent.com/71211299/137467301-24296c1e-1ab3-405e-8123-8da0faebfb4b.png" width="120" height="120"><img src="https://user-images.githubusercontent.com/71211299/137466836-6bfdb406-68d0-4b1a-a54a-a00ecf024201.png" width="220" height="120"><img src="https://user-images.githubusercontent.com/71211299/137469882-610f92df-9232-4bca-95b7-3a250a0510c8.png" width="110" height="120"><img src="https://user-images.githubusercontent.com/71211299/137469903-89eabc8a-58eb-4017-b6ed-b79e56d112f6.png" width="120" height="120">

Advanced knowledge: 
* Android SDK
* Android-lifecycle
* Patterns (MVC, MVP, MVVM and others)
* Viewbinding
* Recyclerview
* Fragments
* Services
* Coruntines (Executor)
* Local (sqlite, room, cursor) and remote DB (firebase)
* Work with json (Glide and Coil)

This list may be expanded in this moment, because i always update (refresh) my knowledge and skills 

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
- [VK](https://vk.com/dietmargrandarisingcosmosalexman)
- Discord: Dietmar Granda#5636
- [Github](https://github.com/8DietmarBarbarossa8)
- Telegram: Dietmar_Granda
- [LinkedIn](https://www.linkedin.com/in/dmitriy-korzhovnik-43a256210/)
