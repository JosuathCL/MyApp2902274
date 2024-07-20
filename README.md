#¿Qué es Kotlin?

Kotlin es un lenguaje de programación moderno que es integrado con Java y es muy conocido por su simplicidad, su seguridad de tipos y capacidades multiplataforma. Es popular por su sintaxis clara, características de programación funcionales y compatibilidad con el ecosistema Java.

#¿Cuál es la definición de variables en Kotlin?

En Kotlin, las variables son depósitores que almacenan datos que pueden cambiar o no durante la ejecución del programa:

Variables mutables (var): se definen mediante la palabra clave var y permiten cambiar su valor después de la inicialización.

Variables inmutables (val): Se definen con la palabra clave val y su valor no se puede cambiar después de la inicialización, actuando como constantes.

#Manejos de nulos 

En Kotlin, el manejo de valores nulos se realiza de forma segura para evitar errores comunes como NullPointerException. Las características principales son:

Tipos de datos que aceptan valores NULL: los tipos ordinarios no admiten directamente valores nulos. Para permitir valores nulos, utilice? después del tipo (por ejemplo, ¿Cadena?).

Operador de seguridad:

?.: Le permite acceder a propiedades o llamar a métodos de un objeto que acepta valores NULL sin generar una excepción.
?: (Operador de Elvis): proporciona un valor predeterminado cuando la expresión es nula.
Conversiones seguras: funciones como toIntOrNull() pueden convertir fácilmente valores potencialmente nulos sin generar una excepción.

Estas características hacen que Kotlin sea más seguro y menos propenso a errores relacionados con nulos que otros lenguajes como Java.

#¿Cuáles son las opciones en Kotlin?

En Kotlin, un valor opcional es un tipo de datos que puede contener valores normales o nulos. Esto le permite manejar de forma segura situaciones en las que el valor puede no existir o ser desconocido durante la ejecución del programa.

#Comentario 

En Kotlin, las anotaciones se hacen así:

Comentarios de una línea: comience con //.

Comentarios de varias líneas: comienzan con /* y terminan con */.

Estos formatos le permiten documentar su código de manera eficiente y explicar cómo funciona sin que el compilador los interprete como parte de un programa ejecutable.

