Variables y operaciones
1️⃣ Responde las siguientes preguntas en la sección de comentarios:
¿Qué es una variable y para qué sirve?

    Es un espacio en memoria para la recoleccion de datos, existen tres formas para la recoleccion de estos datos: VAR LET CONST el uso de cada una de estas dependera del tipo de dato que se quiera almacenar y las mas utilizadas son let y conts.

¿Cuál es la diferencia entre declarar e inicializar una variable?

    Declarar se refiere a darle un nombre y tipo a una variable, pero cuando hablamos de inicializar es cuando ya se le da un valor a esa variable.

¿Cuál es la diferencia entre sumar números y concatenar strings?

    Al sumar estaremos recibiendo el resultado de la operacion, por otro lado al concatenar estaremos uniendo los valores que estemos concatenando y se mostraran en el orden en que hayan sido enviados.

¿Cuál operador me permite sumar o concatenar?

    El signo mas (+) es el valor que nos permitira hacer estos procesos.

2️⃣ Determina el nombre y tipo de dato para almacenar en variables la siguiente información:

    > Nombre "String"
    > Apellido "String"
    > Nombre de usuario en Platzi "String"
    > Edad "Number"
    > Correo electrónico "String"
    > Mayor de edad "Boolean"
    > Dinero ahorrado "Number"
    > Deudas "Number"

3️⃣ Traduce a código JavaScript las variables del ejemplo anterior y deja tu código en los comentarios.

    Este punto se encuentra desarrollado en el archivo test.js

4️⃣ Calcula e imprime las siguientes variables a partir de las variables del ejemplo anterior:
Nombre completo (nombre y apellido)
Dinero real (dinero ahorrado menos deudas)
Funciones
1️⃣ Responde las siguientes preguntas en la sección de comentarios:
¿Qué es una función?
¿Cuándo me sirve usar una función en mi código?
¿Cuál es la diferencia entre parámetros y argumentos de una función?
2️⃣ Convierte el siguiente código en una función, pero, cambiando cuando sea necesario las variables constantes por parámetros y argumentos en una función:
const name = "Juan David";
const lastname = "Castro Gallego";
const completeName = name + lastname;
const nickname = "juandc";

console.log("Mi nombre es " + completeName + ", pero prefiero que me digas " + nickname + ".");
Condicionales
1️⃣ Responde las siguientes preguntas en la sección de comentarios:
¿Qué es un condicional?
¿Qué tipos de condicionales existen en JavaScript y cuáles son sus diferencias?
¿Puedo combinar funciones y condicionales?
2️⃣ Replica el comportamiento del siguiente código que usa la sentencia switch utilizando if, else y else if:
const tipoDeSuscripcion = "Basic";

switch (tipoDeSuscripcion) {
   case "Free":
       console.log("Solo puedes tomar los cursos gratis");
       break;
   case "Basic":
       console.log("Puedes tomar casi todos los cursos de Platzi durante un mes");
       break;
   case "Expert":
       console.log("Puedes tomar casi todos los cursos de Platzi durante un año");
       break;
   case "ExpertPlus":
       console.log("Tú y alguien más pueden tomar TODOS los cursos de Platzi durante un año");
       break;
}
3️⃣ Replica el comportamiento de tu condicional anterior con if, else y else if, pero ahora solo con if (sin else ni else if).
💡 Bonus: si ya eres una experta o experto en el lenguaje, te desafío a comentar cómo replicar este comportamiento con arrays u objetos y un solo condicional. 😏

Ciclos
1️⃣ Responde las siguientes preguntas en la sección de comentarios:
¿Qué es un ciclo?
¿Qué tipos de ciclos existen en JavaScript?
¿Qué es un ciclo infinito y por qué es un problema?
¿Puedo mezclar ciclos y condicionales?
2️⃣ Replica el comportamiento de los siguientes ciclos for utilizando ciclos while:
for (let i = 0; i < 5; i++) {
    console.log("El valor de i es: " + i);
}

for (let i = 10; i >= 2; i--) {
    console.log("El valor de i es: " + i);
}
3️⃣ Escribe un código en JavaScript que le pregunte a los usuarios cuánto es 2 + 2. Si responden bien, mostramos un mensaje de felicitaciones, pero si responden mal, volvemos a empezar.
💡 Pista: puedes usar la función prompt de JavaScript.

Listas
1️⃣ Responde las siguientes preguntas en la sección de comentarios:
¿Qué es un array?
¿Qué es un objeto?
¿Cuándo es mejor usar objetos o arrays?
¿Puedo mezclar arrays con objetos o incluso objetos con arrays?
2️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima su primer elemento.
3️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el array completo).
4️⃣ Crea una función que pueda recibir cualquier objeto como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el objeto completo).