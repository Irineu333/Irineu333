``` kotlin
fun getAboutMe() : Developer {
    val name = "Irineu A. Silva"
    val contact = "mmmirinesilva@gmail.com"

    val skills = mapOf(
        "Java" to "2-3 years",
        "Kotlin" to "1-2 years",
        "Android" to "2-3 years",
        "C" to "basic"
    )
    
    return Developer(name, contact, skills)
}
```
