## Explica los siguentes conceptos con tus propias palabras. (no más de tres líneas por respuesta).

* Estructura de Datos:
Es un sistema de vinculacion de datos, existen varios tipos de estructuras de datos y todas tienen propositos distintos, estan hechas para la mejor eficiencia para el proposito que están hechas. Te permiten almacenar y buscar datos de forma muy rapida.
* Lista Enlazada:
Una lista enlazada es una estructura de datos lineal, donde cada dato, se enlaza con el siguiente. Es decir, se crea
un objeto que tenga el valor y el link hacia el siguiente 
* Árbol: Un arbol es un tipo de estructura de datos compuesta por nodos con el valor y dos punteros que señalan hacia donde van los datos. Esto tiene multiples ventajas. Aplicando una regla de division(puede ser menor o mayor), se pueden llegar a los datos con muchos menos pasos que con un arreglo lineal.

* Closures:
Clousure es una herramienta que te permite tener variables que no pueden ser modificadas. Lo que se hace es utilizar lexical envioroment de las funciones. El lexical envioroment de las funciones aparece cada vez que la funcion es invocada, pero si vos utilizas un clousure, podes volver a ese valor re invocando la funcion, pero sin poder manipular variables
* Contexto de Ejecución:
El contexto de ejecucion es algo similar a un espacio dentro del programa. Pensemoslo como una playa. Las funciones, serian las carpas, donde vos podes abrirlas y meterte adentro para hacer algo y volver a desarmarlas cuando no las uses. Mientras que el edificio de administracion no. El contexto global es el contexto donde todo se ejecuta y no se pueede desarmar mientras que el contexto de ejecucion especifico serian las carpas que van apareciendo y desapareciendo
* Variable THIS:
La variable this siempre refiere al objeto padre más cercano qeu tiene. Supongamos que la usamos en una clase, this se referiria a esa clase. Mientras que invocar this sin estar dentro de algun objeto, se referiria al objeto más grande, que es el DOM, por como esta armado Javascript.

* Hoisting: Es una caracteristica de javascript, el lenguaje lee dos veces el codigo. la primera es para llevar cualquier variable declarada, sin importar donde este declarada en el codigo, a su ambito de ejecucion.

* Pasar por valor y por referencia:
Cuanod pasas una variable por referencia, lo que sucede es que esa variable puede modificarse en una funcion, y cuando se pasa por valor, no. lo que sucede es que la variable por referencia apunta hacia el mismo lugar de memoria que la variable, mientras que cuando es una referencia, no. Entonces las variables pasadas por referencia no se modifican. 

* Algoritmo: Un algoritmo es una serie de pasos a seguir para desarrollar una tarea. Ejemplos sencillos pueden ser los programas o las recetas de comida. Todo lo que involucre una serie de pasos repetibles para desarrollar una tarea es un algoritmo. No necesariamente tienen que ser eficientes pero es una cualidad deseada para el mejor funcionamiento de los mismos

* Big O notation: Es una notacion matematica utilizada para clasificar algoritmos. Lo que se hace es utilizar una referencia para entender el orden y el impacto de tu algoritmo en una funcion. Si vos empezas a tener tareas que son poco eficientes, la funcion puede convertirse en exponencial y cada paso lleva muchisimo más tiempo para realizarse

* Inmediatly Invoked Function Expression (IIFF): son funciones que se invocan inmediatamente despues de ser declaradas. Tambien se llaman funciones autoejecutables, sirven para que ciertos datos sean inaccesibles para el resto del codigo. En caso de necesitar que un dato sea inamobible por todo el codigo, es una buena opcion.
