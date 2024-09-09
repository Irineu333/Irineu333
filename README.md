```kotlin
fun getAbout(): Developer {

    val name = "Irineu A. Silva"
    
    val contacts = mapOf(
        "email" to "mmmirinesilva@gmail.com",
        "linkedin" to "irineu333"
    )

    val languages = mapOf(
        "Java" to "2019~Today, JDK 7 ~ 17",
        "Kotlin" to "2020~Today",
        "C/C++" to "basic"
    )

    val frameworks = mapOf(
        "Spring Boot" to Framework(
            experience = "basic",
            architectures = listOf("MVC")
        ),
        "Android" to Framework(
            experience = "2019~Today, SDK 19 ~ 33",
            architectures = listOf("MVP", "MVVM", "Clean Architecture", "MVI"),
            ui = listOf("view/xml", "JetPack Compose")
        )
    )

    return Developer(name, contacts, languages, frameworks)
}
```

If you're looking for my projects, check out [my serious projects](PROJECTS.md).
