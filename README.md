<h3>
    
```kotlin
class Coder: Person(
    val firstName: String = "Isaac",
    val lastName: String = "Serrano",
    var age: Int = 22,
    val nationality: String = "Mexican",
) {
    
    private fun languages(): Array<String> {
        return arrayOf<String>("Kotlin", "Java", "JavaScript", "HTML", "CSS")
    }

    private fun tools(): Array<String> {
        return arrayOf<String>("Android", "React", "Spring Boot", "React Native", "SASS", "Bootstrap", "Styled-Components", "Photoshop", "Illustrator")
    }

    private fun education(): Array<String> {
        return arrayOf<String>("Polytechnic University of Sinaloa", "CubicCoding", "Wizeline Academy", "Hackademy")
    }

    private fun workingIn(): String {
        return "Ivy Mobility"
    }
}
```
</h3>
