<div style="text-align: center">
<h1><code>Welcome</code></h1>
<h4>
    
```kotlin
​
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
​
```
</h4>