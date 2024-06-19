# Programación con JavaScript

El flujo de control, en programación, se refiere al orden en el que se ejecutan o evalúan las declaraciones, instrucciones o llamadas a funciones individuales. La secuencia de ejecución puede ser influenciada por estructuras de control, tales como:

. Ejecución Secuencial: Es el modo predeterminado donde las declaraciones se ejecutan una tras otra en el orden en que aparecen.

. Declaraciones Condicionales: Incluyen if, else if, y else, permitiendo al programa tomar decisiones y ejecutar código basado en ciertas condiciones.

. Bucles: Constructos como los bucles for, while, y do-while permiten la ejecución repetida de un bloque de código mientras una condición especificada sea verdadera.

. Llamadas a Funciones: Las funciones encapsulan un bloque de código que puede ser ejecutado cuando se llama, potencialmente múltiples veces dentro de un programa, permitiendo código modular y reutilizable.

. Declaraciones de Transferencia de Control: Instrucciones como break, continue y return pueden alterar el flujo normal saltando fuera de bucles, omitiendo iteraciones o saliendo de funciones anticipadamente.

Al utilizar estas estructuras, un programador puede crear rutas de ejecución complejas y dinámicas dentro de un programa.


# Responde

¿Qué es “Control Flow” (Control de Flujo)?

El "Control de Flujo" en programación es el mecanismo que determina el orden en que se ejecutan las instrucciones de un programa. Utiliza estructuras como declaraciones condicionales (if, else, switch), bucles (for, while, do...while), y sentencias de interrupción (break, continue).

¿Qué es una “function” (Función) de JavaScript?

Es un bloque de código que se puede definir una vez y ejecutar múltiples veces. Una función puede recibir parámetros y devolver un valor. Las funciones permiten modularizar el código, facilitando su reutilización y mantenimiento. Se definen utilizando la palabra clave function, seguida del nombre de la función, paréntesis con los parámetros (si los hay) y llaves que encierran el cuerpo de la función.

¿Qué significa “invoke” o “call” en una función?

Se refiere a ejecutar una función. Cuando invocas una función, estás diciéndole al programa que ejecute el bloque de código que define esa función. Esto se hace utilizando el nombre de la función seguido de paréntesis. Si la función acepta parámetros, estos se colocan dentro de los paréntesis.

¿Para qué sirven los paréntesis () cuando defines una función?

En JavaScript, los paréntesis () al definir una función sirven para:

Indicar parámetros: Los paréntesis pueden contener una lista de parámetros que la función acepta. Por ejemplo:

function sumar(a, b) {
  return a + b;
}

Diferenciar la definición de la invocación: Los paréntesis se usan tanto al definir la función como al invocarla, pero vacíos cuando no hay parámetros. Por ejemplo:

function saludar() {
  console.log("Hola");
}

saludar(); // Invoca la función
