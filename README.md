<h4>
    
```kotlin
class Coder: Person(
    val firstName: String = "Isaac",
    val lastName: String = "Serrano",
    var age: Int = 22,
    val nationality: String = "Mexican",
) {
    
    fun shortBio(): String {
        val bio: String = "Hey, I just like to make some little projects to study for myself in this account. Android Dev with 2+ years of exp..."
    }
    
    fun languages(): Array<String> {
        return arrayOf<String>("Kotlin", "Java", "JavaScript", "HTML", "CSS")
    }

    fun tools(): Array<String> {
        return arrayOf<String>("Android", "React", "Spring Boot", "React Native", "SASS", "Bootstrap", "Styled-Components")
    }

    fun workingIn(): String {
        return "Globant"
    }
}
```
</h4>
