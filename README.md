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
# Class#3
    Variables vs. Objetos
        * En Kotlin variables vs. objetos significa otra cosa en comparación a otros lenguajes de programación.
        * Una variable es un espacio en memoria que nosotros reservamos para almacenar un solo dato.
        * Un objeto es un espacio en memoria que es más complejo que una variable, se va a componer de otras variables y otros objetos, acciones, métodos y funcionalidades.
        * En Kotlin todo será un objeto, evitaremos el tipo de datos variables, simples o sencillos (tipos primitivos). No debemos declarar valores primitivos (si podríamos pero no debemos), pero son definidos cuando no los usamos como objetos.
        * Ejemplo de dato primitivo:
            var i = 10
            i = i * 2
            println(i)
        * Kotlin utiliza wrappers (clases envoltorio) para los números, esto se llama boxing.
        * En los operadores de Kotlin debemos tratar todo como si fuera un objeto:
            Expresión	 Función	        Se traduce a
                a + b	    plus	            a.plus(b)
                a - b	    minus               a.minus(b)
                a * b	    times               a.times(b)
                a / b	    div	                a.div(b)
                a % b	    mod	                a.mod(b)
                a += b	    a = a + b	        a.plusAssign(b)
                a -= b	    a = a - b	        a.minusAssign(b)
                a *= b	    a = a * b	        a.timesAssign(b)
                a /= b	    a = a / b	        a.divAssign(b)
                a %= b	    a = a % b	        a.modAssign(b)
            Operador     Significado        Expresión       Se traduce a
                +	        Suma unaria	        +a	            a.unaryPlus()
                -	        Resta unaria        -a	            a.unaryMinus()
                !	        Negación	        !a	            a.not()
                ++	        Incremento	        ++a	            a.inc()
                --	        Decremento	        --a	            a.dec()
# Links
    Try kotlinlang:
        https://try.kotlinlang.org/#/Examples/Hello,%20world!/Simplest%20version/Simplest%20version.kt