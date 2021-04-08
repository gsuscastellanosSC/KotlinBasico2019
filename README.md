# KotlinBasico2019
    https://platzi.com/clases/kotlin-2019/
# Class#1
    ¿Por qué debo aprender Kotlin?            
        Kotlin es uno de los lenguajes oficiales que Google ha adoptado como parte de la familia de lenguajes de programación para desarrollar con Android. Kotlin fue desarrollado desde el año 2010 gracias a JetBrains y su primera versión fue liberada en el año 2016.
        Kotlin es:
            * Conciso: reduce código a diferencia de Java.
            * Seguro: Kotlin tiene un método para evitar las excepciones así como para manejar las NullPointerException.
            * Interoperable: Kotlin al ser creado por JetBrains lo decidieron hacer basado en la máquina virtual de Java, es decir puedes trabajar con Java y Kotlin en una aplicación ya que comparten la misma máquina virtual.
            * Versátil: podemos aplicarlo en diferentes tipos de aplicaciones. Del lado del servidor con Kotlin Server Side - Ktor, del lado Mobile Android y del lado web con KotlinJS.
            * Java usa javac y Kotlin usa kotlinc ambos al ser compilado se transforman en código ByteCode que es el código que lee la máquina virtual de Java (Java Virtual Machine)
# Class#2    
    Mi primer programa en Kotlin
        Para empezar a configurar nuestro entorno de desarrollo necesitaremos varias herramientas:
            * El SDK de Java ya que Kotlin está basado en Java
            * IntelliJ IDEA el cual será nuestro editor de código el cual ya tiene un compilador de código.
        A continuación te presentamos un Hola Mundo en Kotlin:
            fun main (args: Array<String>) {  
                println("Hola Platzi")  
            }
# Links
    Try kotlinlang:
        https://try.kotlinlang.org/#/Examples/Hello,%20world!/Simplest%20version/Simplest%20version.kt