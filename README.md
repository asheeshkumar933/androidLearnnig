# androidLearnnig
# Q- what is kotlin -- kotlin is a statically type programming language developed by JetBrains , designed  fully interoprable with java . It offers modern features like - null safety , extension functions , and corutines , making Android developedment more concise and expressive.
# Q-- what are the main advantage of using kotlin over java .
Null Safety : Reduces the risk of NullPonterExceptions.
Conciseness : Kotlin code is often more compact and easier to read .
Corutines : Siplifies asynchronous programming .
Extension Functions : Allows you to add new functions to existing classes without modifying them.
# Q- Explain th concept of couroutines .
Answer: Coroutines are a Kotlin feature that allows you to write asynchronous, non-blocking code. They enable you to handle long-running tasks (like network calls) in a simpler way using suspend functions, which can be paused and resumed without blocking the thread.
# 5. What are extension functions?
Answer: Extension functions allow you to "add" new functions to existing classes without modifying their source code. This is useful for enhancing the functionality of libraries or framework classes.
#6. What is a sealed class?
A sealed class restricts class hierarchies to a limited set of types. It’s useful for representing a fixed number of types in a type-safe way, such as representing different states in a UI. Sealed classes can only be subclassed within the same file.
#7. How do you handle nullability in Kotlin?
 Kotlin distinguishes between nullable and non-nullable types. You can declare a variable as nullable by appending a question mark (?), and you can use the safe call operator (?.) to access properties or methods safely.

var name: String? = null
val length = name?.length // Safe call











