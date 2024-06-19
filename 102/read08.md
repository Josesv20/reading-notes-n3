# Operadores y bucles

. Expresiones

Una expresión es cualquier unidad de código que se evalúa y produce un valor. Las expresiones pueden ser:

Literales: Valores directamente escritos en el código, como números (123), cadenas ('Hola'), o booleanos (true).

Identificadores: Variables y constantes que hacen referencia a valores almacenados.

Expresiones combinadas: Uso de operadores para combinar otras expresiones y producir un nuevo valor.

. Operadores

Los operadores permiten realizar operaciones sobre valores y variables. Algunos de los principales tipos de operadores incluyen:

Aritméticos: Para realizar operaciones matemáticas básicas (+, -, *, /, %).

Asignación: Para asignar valores a variables (=, +=, -=, *=, /=, %=).

Comparación: Para comparar valores (==, ===, !=, !==, >, <, >=, <=).

Lógicos: Para realizar operaciones lógicas (&&, ||, !).

Bit a bit: Para operar a nivel de bits (&, |, ^, ~, <<, >>, >>>).

Especiales: Incluyen el operador ternario (? :), operadores de desestructuración, y el operador de propagación (...).

. Precedencia de Operadores

La precedencia determina el orden en el que se evalúan las partes de una expresión. Los operadores con mayor precedencia se evalúan antes que los de menor precedencia. Por ejemplo, la multiplicación (*) tiene mayor precedencia que la suma (+), por lo que en la expresión 2 + 3 * 4, primero se evalúa 3 * 4, resultando en 12, y luego 2 + 12, dando 14.

. Encadenamiento Opcional y Nullish Coalescing

Encadenamiento opcional (?.): Permite acceder a propiedades profundamente anidadas sin necesidad de verificar cada nivel.

Nullish Coalescing (??): Proporciona un valor predeterminado cuando una expresión es null o undefined.

. Declaración for

El ciclo for en JavaScript se repite hasta que una condición especificada se evalúe como falsa. Es similar al bucle for en lenguajes como Java y C. La sintaxis básica es:

for ([expresiónInicial]; [expresiónCondicional]; [expresiónDeActualización])
  instrucción

Funcionamiento:
1. Expresión Inicial: Se ejecuta una vez al comienzo del bucle. Se utiliza generalmente para inicializar uno o más contadores de bucle.

2. Expresión Condicional: Se evalúa antes de cada iteración. Si es verdadera, se ejecutan las instrucciones del bucle. Si es falsa, el bucle termina.

3. Instrucción: Se ejecuta si la expresión condicional es verdadera.

4. Expresión de Actualización: Se ejecuta después de cada iteración del bucle.

5. Repetición: El control regresa a la evaluación de la expresión condicional.

. Declaración while

El ciclo while se repite mientras una condición especificada sea verdadera. Su estructura es:

while (condición) {
  // expresión
}

Características:

. Evalúa la condición antes de cada iteración.

. Si la condición es verdadera, ejecuta la expresión del bucle.


# Responde

¿Qué es una “expresión” en JavaScript?

Una expresión en JavaScript es cualquier fragmento de código que se evalúa y produce un valor. Las expresiones son fundamentales en el lenguaje porque se utilizan en todas partes, desde asignaciones y condiciones hasta argumentos de funciones y más.

¿Por qué usaríamos un bucle en nuestro código?

Usariamos bucle en codigo por las siguientes razones:

1. Automatización de Tareas Repetitivas
Los bucles permiten automatizar la ejecución de un bloque de código múltiples veces sin necesidad de escribir el mismo código repetidamente. Esto es especialmente útil cuando se trabaja con conjuntos de datos o cuando se necesita repetir una operación hasta que se cumpla una condición específica.

2. Procesamiento de Colecciones de Datos
Cuando se trabaja con arrays o listas, los bucles permiten iterar sobre cada elemento de la colección para realizar operaciones como búsqueda, filtrado, transformación, o agregación de datos.

3. Ejecución Condicional hasta Cumplir una Condición
Los bucles pueden ejecutar una serie de instrucciones hasta que se cumpla una condición específica, lo que es útil para realizar operaciones donde no se conoce de antemano el número de iteraciones necesarias.

4. Manejo de Eventos Asíncronos y Estructuras de Control
En el manejo de eventos asíncronos o estructuras de control más complejas, los bucles ayudan a simplificar la lógica y hacer que el código sea más legible y mantenible.

5. Optimización y Eficiencia
Los bucles permiten optimizar y hacer más eficiente el código al reducir la redundancia. Al utilizar bucles, se puede evitar la duplicación de código y gestionar operaciones repetitivas de manera estructurada y eficiente.

¿Cuándo deja de ejecutarse un bucle for?

Un bucle for en JavaScript deja de ejecutarse cuando su expresión condicional se evalúa como falsa.

¿Cuántas veces se ejecutará un bucle “ while “?

Un bucle while en JavaScript se ejecutará tantas veces como sea necesario hasta que la condición especificada se evalúe como falsa.