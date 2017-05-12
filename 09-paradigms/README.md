# 09. Paradigmas de programación

Los **Paradigmas de Programación** (_Programming Paradigms_) son formas diferentes
de pensar en cómo se organiza un programa basado en una serie de principios, los
cuales resultan en estilos muy distintos y lenguages muy diversos.

**JavaScript** es un leguage _híbrido_, por decirlo de alguna forma, y contiene
elementos propios de lenguages funcionales (por ejemplo funciones como objetos
de primera clase, lambdas, ...) pero no estamos limitados al paradigma
funcional, si no que en su dinamismo y rareza, **JavaScript nos permite programar
de forma _funcional_, _orientado a objetos_, _orientado a eventos_,
_por procedimientos_, ...**

Como desarrollador **Full Stack JS** es esencial entender los distintos
paradigmas de programación y cómo se traducen al mundo real en proyectos de
JavaScript.

Históricamente, el paradigma orientado a objetos (OOP) ha sido el predominante,
pero recientemente, y en particular en la comunidad de JavaScript, hay un
resurgir del paradigma funcional y sus bondades. **JavaScript es un lenguage de
corazón funcional**, así que conocer el paradigma, y cómo se compara a la
programación orientada a objetos, no sólo te hará una mejor coder, si no que
podrás entender cómo se pueden enfrentar los mismos problemas con enfoques
distintos, e identificar y adaptarse a bases de código existentes.

En este curso formarás parte de un equipo responsable de extender la
funcionalidad de un juego de dos dimensiones escrito en JavaScript. **Tu equipo
tendrá que dividir tareas, trabajar en parejas y en parelalo y hacer code
reviews**. Todo el flujo de trabajo será a través de un repositorio alojado en
GitHub. Durante la primera semana tu equipo tendrá que extender el juego
_heredando_ del prototipo de un contructor ya implementado, mientras que en la
segunda semana tendrán que refactorizar el código de la primera semana usando
el paradigma funcional.

## Aprenderás

* Qué son los **paradigmas de programación**
* Qué son **FP**, **OOP**, **EOP** y **PP** y cómo se comparan
* A entender las diferencias y entre el estilo **imperativo vs declarativo**
* Las diferencias entre **constructores** y **factories**
* Cómo implementar **herencia prototipal**
* Los principios básicos de la **programación funcional**
* A usar **composición** como alternativa la _herencia_
* A **trabajar sobre una base de código existente**
* A trabajar haciendo **pair programming**
* A sacarle el jugo a git y GitHub usando **issues**, **milestones**,
  **branches**, **forks** y **pull requests**

## Detalles logísticos

* Self-paced: 4 hrs
* Presencial: 10 hrs
* Total horas: 14

## Producto

El _producto_ en el que trabajarás es un
[videojuego de ejemplo](https://laboratoria.github.io/game-oop/), con una
[base de código](https://github.com/Laboratoria/game-oop) existente y que
funciona. La idea es que un jefe ficticio le ha pedido a tu equipo que añada
una serie de _personajes_ y _niveles_ nuevos.

Participar en el proyecto involucra lo siguiente:

* Tener una cuenta en **GitHub**
* Hacer un **fork** del repo _upstream_
* **Mapear y dividir el trabajo** con tu equipo
* Setear **milestones**
* Implementar nuevos personajes y mapas usando **herencia**
* Implementar nuevos personajes y mapas usando **composición**
* Enviar **pull requests**
* Hacer **code review** y **merges**
* Presentar el trabajo final al resto del grupo con una **demo**

El juego está inspirado en el ejemplo de
[js-tiles de mozdevs](https://github.com/mozdevs/gamedev-js-tiles).

***

## Syllabus

### Lesson 1: [Introducción a Paradigmas de Programación](01-intro)

1h (self-paced)

En esta lección aprenderás las características y diferencias entre los
paradigmas más relevantes para JavaScript: imperativo, por procedimientos,
orientado a objetos (OOP) y funcional (FP).

#### Lesson plan

| Orden |  Tipo      | Duración | Descripción
|-------|------------|----------|------------
|   1   | video      |    2min  | ¿Qué son los paradigmas de programación?
|   2   | video      |    3min  | Declarativo vs Imperativo
|   3   | video      |    3min  | Comparativa de paradigmas
|   4   | video      |    4min  | Por procedimientos
|   5   | code       |   10min  | Ejericio por procedimientos
|   6   | video      |    4min  | Orientado a objetos
|   7   | code       |   10min  | Ejericio OOP
|   8   | video      |    4min  | Funcional
|   9   | code       |   10min  | Ejericio funcional
|  10   | quiz       |   10min  | Prueba tu conocimiento

### Lesson 2: [OOP y herencia prototipal](03-oop)

1h (self-paced)

Después de haber completado la introducción a paradigmas, te introdicirás en los
detalles de cómo usar contructores y prototipos para crear jerarquías de
herencia.

#### Lesson plan

| Orden |  Tipo      | Duración | Descripción
|-------|------------|----------|------------
|   1   | video      |   10min  | Propiedades de instancia vs prototipo
|   2   | code       |   10min  | Ejercicios de instancia vs prototipo
|   3   | video      |   10min  | Herencia prototipal
|   4   | code       |   10min  | Ejercicios de herencia prototipal
|   5   | quiz       |   10min  | Prueba tu conocimiento

### Lesson 3: [Ejercicios guiados, ayudantías, charlas](02-guided-exercises)

1h (presencial)

Ahora que ya has tenido un primer acercamiento a los paradigmas en general, OOP
en particular y herencia prototipal, en esta lección nos concentraremos en hacer
ejercicios todos juntos con la ayuda del profe y los TAs.

#### Lesson plan

| Orden |  Tipo      | Duración | Descripción
|-------|------------|----------|------------
|   1   | ejercicios |   30min  | Herencia prototipal
|   2   | challenge  |   30min  | Ejercicios de herencia prototipal

### Lesson 4: [Entorno y metodología de trabajo](#)

1h (presencial)

...

| Orden |  Tipo      | Duración | Descripción
|-------|------------|----------|------------
|   1   | charla     |   30min  | Kick-off: Entorno y metodología de trabajo
|   2   | reunión    |   30min  | Identificar tareas, dividir trabajo

### Lesson 5: [Proyecto (implementación OOP)](04-oop-project)

3h (presencial)

...

| Orden |  Tipo      | Duración | Descripción
|-------|------------|----------|------------
|   1   | code       |   2h     | Hacking...
|   2   | review     |   30min  | Code review

### Lesson 6: [Demos de proyectos OOP](05-oop-demos)

1h (presencial)

Cada equipo (dos alumnas) tendrá 5 minutos para presentar su demo.

### Lesson 7: [Object factories and composition](06-composition)

1h (self-paced)

...

| Orden |  Tipo      | Duración | Descripción
|-------|------------|----------|------------
|   1   | video      |   10min  | Introducción a la programación funcional
|   2   | video      |   10min  | Estado compartido y cómo evitarlo
|   3   | video      |   10min  | Composition over inheritance
|   4   | code       |   10min  | Ejercicios de composición
|   5   | quiz       |   10min  | Prueba tu conocimiento

### Lesson 8: [Proyecto (implementación FP)](07-fp-project)

3h (presencial)

...

| Orden |  Tipo      | Duración | Descripción
|-------|------------|----------|------------
|   1   | qa         |   15min  | Kick-off: Open questions
|   2   | reunión    |   15min  | Re-cap
|   3   | code       |   2h     | Hacking...
|   4   | review     |   30min  | Code review

### Lesson 9: [Demos de proyectos FP](08-fp-demos)

1h (presencial)

Cada equipo (dos alumnas) tendrá 5 minutos para presentar su demo.

* * *

## Contributors

* Lupo Montero (autor)
* Bianca Gandolfo
* Mariano Crowe
* ...

## Libros (mínimo 4)

* [Object-Oriented vs. Functional Programming]( http://www.oreilly.com/programming/free/object-oriented-vs-functional-programming.csp),
  Richard Warburton, O'Reilly Media
* [Eloquent JavaScript](http://eloquentjavascript.net/), Marijn Haverbeke, 2014
* [You Don't Know JS: this & Object Prototypes](https://github.com/getify/You-Dont-Know-JS/tree/master/this%20%26%20object%20prototypes),
  Kyle Simpson, O'Reilly Media, Jul 2014
* [Programming Paradigms for Dummies: What Every Programmer Should Know](https://www.info.ucl.ac.be/~pvr/VanRoyChapter.pdf),
  Peter Van Roy, Université Catholique de Louvain, Bélgica, circa 2010.

## Benchmarks

Cursos similares que sirven como referencia:

* [Object-Oriented JavaScript](https://www.udacity.com/course/object-oriented-javascript--ud015),
  Hack Reactor en Udacity
* [Ejercicio de ejemplo del curso de Hack Reactor](https://github.com/madbernard/blinky-dance-party)
* [Overview of the four main programming paradigms](http://people.cs.aau.dk/~normark/prog3-03/html/notes/paradigms_themes-paradigm-overview-section.html), Kurt Nørmarks, Aalborg University, Dinamarca.

## Referencias

Capítulos de libros:

* [Eloquent JavaScript - Chapter 3: Functions](http://eloquentjavascript.net/03_functions.html)
* [Eloquent JavaScript - Chapter 5: Higher-Order Functions](http://eloquentjavascript.net/05_higher_order.html)
* [Eloquent JavaScript - Chapter 6: The Secret Life of Objects](http://eloquentjavascript.net/06_object.html)

Blog posts:

* [Six programming paradigms that will change how you think about coding](http://www.ybrikman.com/writing/2014/04/09/six-programming-paradigms-that-will/),
  Yevgeniy Brikman, Apr 09, 2014
* [Why Learn Functional Programming in JavaScript? (Composing Software)]( https://medium.com/javascript-scene/why-learn-functional-programming-in-javascript-composing-software-ea13afc7a257),
  Eric Elliott en Medium, Feb 20 2017
* [JavaScript and Functional Programming](https://bethallchurch.github.io/JavaScript-and-Functional-Programming/),
  Beth Allchurch, 29 of June, 2016
* [An introduction to functional programming](https://codewords.recurse.com/issues/one/an-introduction-to-functional-programming),
  Mary Rose Cook

Videos:

* [Anjana Vakil: Learning Functional Programming with JavaScript](https://www.youtube.com/watch?v=e-5obm1G_FY),
  JSUnconf 2016
* [Programming Paradigms - Computerphile](https://www.youtube.com/watch?v=sqV3pL5x8PI),
  30 Aug 2013

Otros recursos:

* [Definición de Programming_paradigm en Wikipedia](https://en.wikipedia.org/wiki/Programming_paradigm)
* [Comparativa de paradigmas de programación en Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_programming_paradigms)

***

## Lesson plan for LIM20171

* Duración: 2 semanas
* Horas por semana: 7 hrs

### Week 1

#### Jueves

* Lesson 1: [Introducción a Paradigmas de Programación](01-intro)
  1h (self-paced)
* Lesson 2: [OOP and Prototypal inheritance](03-oop) 1h (self-paced)
* Lesson 3: [Ejercicios guiados, ayudantías, charlas](02-guided-exercises)
  1h (presencial)

#### Sábado

* Lesson 4: [Entorno y metodología de trabajo](#) 1h (presencial)
* Lesson 5: [Proyecto (implementación OOP)](04-oop-project) 3h (presencial)

### Week 2

#### Jueves

* Lesson 6: [Demos de proyectos OOP](05-oop-demos) 1h (presencial)
* Lesson 7: [Object factories and composition](06-composition) 1h (self-paced)

#### Sábado

* Lesson 8: [Proyecto (implementación FP)](07-fp-project) 3h (presencial)
* Lesson 9: [Demos de proyectos FP](08-fp-demos) 1h (presencial)