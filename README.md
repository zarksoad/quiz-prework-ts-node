# quiz-prework-ts-node  



    JavaScript Básico:
        Describe qué es una función en JavaScript y cómo se declara. 
        LA funcion en Javascript  es una porcion de codigo que puede ser llamada indenterminadas veces  
        function suma(a,b){
          return a + b
        }
        suma(2,3)

    Manipulación del DOM:
        Explica cómo seleccionar un elemento del DOM y cambiar su contenido.
        const element = document.getElemnetbyID("element")
        element.innherHtml = "Setence"

    Programación Orientada a Objetos (OOP):
        ¿Qué es una clase en JavaScript y cómo se define una?
        class name {
          name:name 
        
        }

    Eventos en JavaScript:
        ¿Cómo se agrega un evento de clic a un botón en JavaScript?
        const button = document.getElementById("button")
        buttib.addEventListener("Click",()=>{
          alert("Hola soy el boton")
        } )

    Variables y Tipos de Datos:
        Explica las diferencias entre var, let, y const en JavaScript.
        Const es el tipo de variable no puede modificada mientras let y var si pueden ser modificados 
        la diferencia entre let y var es de entorno global y el scope no la afecta si no esta encerrado en un bloque

    Control de Flujo:
        ¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript? 
        For , While , y metodos de array con Find,map,some,every

    Funciones de Flecha:
        Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.
        funcion flecha 
        nombre = (a,b) =>{
      
        return a + b
        }
        La diferencia a una funcion normal es que esta no es afectada por el scope , no puede ser llamada antes de declararse

    JSON:
        ¿Qué es JSON y cómo se utiliza en JavaScript?
        Es un formato en el que me trae informacion , y me permite leer datos desde otro lenguaje de programacion

    Promesas:
        Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.
        la promesas son aquellas en las que pueden tener dos valores un reject y un resolve , dependiendo la promesa puede darme una respuesta si cumple la codicion puedo hacer que fujo vaya continuando

    Depuración:
        ¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?
        Motor v8 de google chrome  

    Preguntas de Selección Múltiple (20)

    ¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?

    A) var myVariable;
    B) variable myVariable;
    C) let myVariable;
    D) A y C son correctas. 
    Respuesta : D , aunque usar var no es muy recomendable
 
    ¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?

    A) push()
    B) pop()
    C) shift()
    D) unshift() 
     Respuesta : A

    ¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?

    A) ==
    B) ===
    C) !=
    D) !==
    Repuesta B 
    ¿Cuál es la salida del siguiente código?

console.log(typeof null);

    A) null
    B) undefined
    C) object
    D) number
    Repuesta : B
    ¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?

    A) forEach()
    B) map()
    C) filter()
    D) Todas las anteriores
    Todas las anteriores
    ¿Qué se entiende por “hoisting” en JavaScript?

    A) Declaraciones de variables y funciones se mueven al principio de su ámbito.
    B) Es un término para describir la eliminación de variables.
    C) Es un método para agrupar varias funciones.
    D) Ninguna de las anteriores.
    Respuesta A

    ¿Cuál es la diferencia entre null y undefined en JavaScript?

    A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado.
    B) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor.
    C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor.
    D) No hay diferencia.
    Respuesta : A

    ¿Cuál es el propósito del método Array.prototype.map()?

    A) Modificar el array original.
    B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original.
    C) Filtrar los elementos de un array.
    D) Encontrar un elemento en un array.
    Respuesta:B
    ¿Qué es el Event Loop en JavaScript?

    A) Un ciclo que controla las llamadas recursivas.
    B) Un proceso que permite a JavaScript realizar operaciones asincrónicas.
    C) Un método para iterar sobre arrays.
    D) Ninguna de las anteriores.
    Respuesta B
    ¿Cuál es la salida del siguiente código?

    console.log(0.1 + 0.2 === 0.3);

    A) true
    B) false
    C) undefined
    D) NaN 
    Respuesta es False

¿Qué se entiende por strict mode en JavaScript?

    A) Un modo que permite utilizar características experimentales.
    B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
    C) Un método para validar datos.
    D) Ninguna de las anteriores.
    Opcion : B

¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

    A) let obj = {};
    B) let obj = Object.create();
    C) let obj = new Object();
    D) A y C son correctas.
    Opcion:D
¿Qué es un callback en JavaScript?

    A) Una función que se pasa como argumento a otra función.
    B) Un tipo de variable especial.
    C) Un método para declarar funciones.
    D) Ninguna de las anteriores.
    Opcion = A

¿Cuál es el propósito de async y await en JavaScript?

    A) Ejecutar funciones síncronas.
    B) Manejar operaciones asincrónicas de manera más simple y legible.
    C) Declarar variables globales.
    D) Ninguna de las anteriores.
    Opcion:B

¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

    A) Arrays
    B) Strings
    C) Objetos
    D) Ninguna de las anteriores.
    Opcion A

¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

    A) JSON.parse()
    B) JSON.stringify()
    C) toString()
    D) parseInt()
  opcion: B
¿Qué es un Promise en JavaScript?

    A) Una función que se ejecuta inmediatamente.
    B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
    C) Un método para declarar variables.
    D) Ninguna de las anteriores.
    Opcion:B

¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

    A) push()
    B) pop()
    C) shift()
    D) unshift()
    Opcion: unshift

¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

    A) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
    B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente.
    C) No hay diferencia entre ellos.
    D) Ambos almacenan datos solo durante la sesión del navegador.
    Opcion D

¿Qué método se utiliza para detener la propagación de un evento en el DOM?

    A) event.stopPropagation()
    B) event.preventDefault()
    C) event.stop()
    D) event.cancel()
    Opcion B


