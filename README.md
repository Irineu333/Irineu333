``` kotlin
fun getAbout() : Developer {
    val name = "Irineu A. Silva"
    val contact = "mmmirinesilva@gmail.com"

    val skills = mapOf(
        "Java" to "2-3 years",
        "Kotlin" to "1-2 years",
        "Android" to "2-3 years",
        "C" to "only basic".
        "JavaScript" to "only basic",
        "English" to "Basic Technical English"
    )
    
    return Developer(name, contact, skills)
}
```
