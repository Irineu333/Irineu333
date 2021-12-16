
``` kotlin
fun getAbout(): Developer {
    val name = "Irineu A. Silva"
    val contact = "mmmirinesilva@gmail.com"

    val skills = mapOf(
        "Java" to "2-3 years, JDK 7 ~ 11",
        "Kotlin" to "1-2 years",
        "C/C++" to "only basic",
        "JavaScript" to "only basic",
        "English" to "only basic"
    )

    val frameworks = mapOf(
        "Spring Boot" to SpringBoot(
            "learning",
            listOf("PostgreSQL")
        ),
        "Android" to Android(
            "2-3 years, SDK 19 ~ 31",
            listOf("MVP", "MVVM", "Clean Architecture"),
            listOf("JetPack Components", "Architecture Components")
        )
    )

    return Developer(name, contact, skills, frameworks)
}
```

##

 [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/irineusilva333/)  
