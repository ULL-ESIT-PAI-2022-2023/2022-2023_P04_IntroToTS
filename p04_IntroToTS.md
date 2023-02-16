# Práctica 4. Introducción a TypeScript. Unit testing con Jest.
### Factor de ponderación: 4

### Objetivos
Los objetivos de esta práctica son:
* Configurar el entorno de trabajo en la máquina virtual Linux de la asignatura para ejecutar programas en TypeScript.
* Ser capaz de desarrollar programas simples en TypeScript en el entorno Linux de la VM de la asignatura usando
  `ts-node`
* Ser capaz de desarrollar y ejecutar test unitarios utilizando Jest
[Jest](https://jestjs.io/)


### Rúbrica de evaluacion del ejercicio
Se señalan a continuación los aspectos más relevantes (la lista no es exhaustiva)
que se tendrán en cuenta a la hora de evaluar esta práctica:
* Se valorará la realización de las diferentes tareas que se proponen
* El alumnado debe ser capaz de subir la solución a un problema de Exercism a esa plataforma
* El alumnado ha de acreditar que es capaz de desarrollar y ejecutar programas simples de la plataforma Jutge
* Se comprobará que el código que el alumnado escribe se adhiere a las reglas de la Guía de Estilo de Google
  para Javascript
* Todas las prácticas realizadas hasta la fecha, incluída la que se presenta para su evaluación, se encuentran alojadas en repositorios privados de GitHub.
* El alumnado ha de acreditar que es capaz de editar ficheros de forma remota en su VM usando Visual Studio
  Code (VSC)

## Introducción a TypeScript
TypeScript es un superconjunto de JavaScript. 
No se trata de un lenguaje de programación completamente nuevo, sino que ha sido diseñado 
partiendo de JavaScript, tomándolo como base y añadiéndole nuevas características y funcionalidades, 
lo que permite desarrollar código de un modo más sencillo, limpio y libre de errores.

TypeScript no es solo un lenguaje de programación, sino un traductor que permite generar código fuente 
en JavaScript a partir de código fuente escrito en TypeScript. 
Como su nombre indica, TypeScript permite utilizar tipos de datos estáticos. 
lo cual es muy relevante, puesto que los tipos de datos estáticos permiten detectar errores en el código 
en fases más tempranas del desarrollo del software y no, por ejemplo, en tiempo de ejecución, cuando el 
software ya se encuentra en producción.

### Ejercicios de Exercism en TypeScript
Siga a continuación con el conocido problema
[Two Fer](https://exercism.org/tracks/javascript/exercises/two-fer)
(*Two for one*).
En este caso la función que hay que codificar es una
[arrow function](https://javascript.info/arrow-functions-basics):
```js
export const twoFer = () => {
  throw new Error('Remove this statement and implement this function');
};
```

La plantilla que proporciona Exercism para esta función, lanza un error utilizando el operador
[Throw](https://javascript.info/try-catch#throw-operator).
Esta primera versión puede ser útil para aprender cómo lanzar una excepción en un programa Javascript, que
sería la forma más adecuada de abortar su ejecución ante una situación de error.

[Collatz Conjecture](https://exercism.org/tracks/javascript/exercises/collatz-conjecture)
es otro ejercicio que no debiera costarle resolver puesto que ya lo ha resuelto en Jutge.

[Esta página](https://exercism.org/tracks/javascript/concepts) 
de Exercism muestra un posible itinerario de aprendizaje que podría Ud. seguir para ganar experiencia con
Javascript.
Los diferentes programas de la plataforma se van desbloqueando conforme va Ud. resolviendo problemas cada vez
más complejos.

Para cubrir los objetivos de esta práctica, resuelva al menos **5 problemas de la plataforma** aparte de los
anteriores y a partir de ese punto, desarrolle todos los ejercicios de Exercism que sea capaz.

## Ejercicios de Jutge
Desarrolle programas que solucionen los siguientes problemas:

1. [P11916](https://jutge.org/problems/P11916_en) Approximation of e
2. [P67268](https://jutge.org/problems/P67268_en) Reverse of sequences
3. [P50497](https://jutge.org/problems/P50497_en) Is Palindrome
4. [P76024](https://jutge.org/problems/P76024_en) Sum of fractions
5. [P17179](https://jutge.org/problems/P17179_en) Statistical measures

## Referencias
* [Exercism](https://exercism.io/)
* [JavaScript Fundamentals](https://javascript.info/first-steps)
* [PAI Code Examples](https://github.com/ULL-ESIT-PAI-2022-2023/PAI-class-code-examples.git)
* [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)
* [Jutge web site](https://jutge.org/)
