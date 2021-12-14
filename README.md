
``` kotlin
Irineu.kt
...

fun getAbout(): Developer {
    val name = "Irineu A. Silva"
    val contact = "mmmirinesilva@gmail.com"

    val skills = mapOf(
        "Java" to "2-3 years",
        "Kotlin" to "1-2 years",
        "C" to "only basic",
        "JavaScript" to "only basic",
        "English" to "only basic"
    )

    val frameworks = mapOf(
        "Spring Boot" to SpringBoot(
            "learning",
            listOf("PostgreSQL")
        ),
        "Android" to Android(
            "2-3 years",
            listOf("MVP", "MVVM", "Clean Architecture"),
            listOf("JetPack Components", "Achitecture Components")
        )
    )

    return Developer(name, contact, skills, frameworks)
}
...
```
``` kotlin
frameworks.kt
...

data class Android(
    val experience : String, 
    val architectures : List<String>, 
    val components : List<String>
) : Framework
...
```
``` java
SpringBoot.java

public class SpringBoot extends Framework {
    
    private final String experience;
    private final List<String> databases;

    public SpringBoot(
            String experience,
            List<String> databases
    ) {
        this.experience = experience;
        this.databases = databases;
    }

    public String getExperience() {
        return experience;
    }

    public List<String> getDatabases() {
        return databases;
    }
}
```

##

 [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/irineusilva333/)  
