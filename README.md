<div style="text-align: center !important;">
    <h1>Hi there!</h1>
</div>

<h3>
    
```kotlin
class Coder: Person(
    val firstName: String = "Isaac",
    val lastName: String = "Serrano",
    var age: Int = 21,
    val nationality: String = "Mexican",
) {
    
    private fun languages(): Array<String> {
        return arrayOf<String>("Kotlin", "Java", "JavaScript", "HTML", "CSS")
    }

    private fun tools(): Array<String> {
        return arrayOf<String>("Android Studio", "React", "React Native", "SASS", "Bootstrap", "Styled-Components", "Photoshop", "Illustrator")
    }

    private fun education(): Array<String> {
        return arrayOf<String>("Polytechnic University of Sinaloa", "CubicCoding", "Hackademy")
    }

    private fun workingIn(): String {
        return "Accenture & CubicCoding"
    }
}
```
</h3>
