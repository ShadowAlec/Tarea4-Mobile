#Tarea 4 Aplicaciones móviles.

## Luis Trinidad Ortiz Cisneros

---
##1 .- Patrón de diseño de software.

Aunque fue en 1987 cuando apareció el primer artículo que hablaba de patrones del lenguaje en programas orientados a objetos, no fue probablemente hasta 1990 cuando comenzaron a ser conocidos extensamente por la comunidad de desarrolladores. Ese año se publicaba el libro “Design Patterns”, escrito por el grupo Gang of Four, el cual estaba compuesto por Erich Gamma, Richard Helm, Ralph Johnson y John Vlisides. En este famosísimo libro, a menudo referenciado como GoF, los autores recogían 23 patrones comunes en el diseño de software, explicando al detalle en qué consistían y describiendo las soluciones adoptadas típicamente para cada problema. Toda una enciclopedia sobre diseño de software para el programador.

Un patrón de diseño debe cumplir al menos dos requisitos para considerarse como tal: Debe ser efectivo, de modo que se haya podido comprobar su éxito resolviendo problemas anteriores; y debe ser reutilizable, es decir, podemos aplicarlo a problemas que se hallan en circunstancias similares a las descritas por el patrón.

Los patrones descritos en GoF se dividen en tres tipos: Creacionales, estructurales, y de comportamiento. Su conocimiento y estudio permiten reconocer los problemas más típicos de forma rápida y efectiva, resolviéndolos en tiempos récord sin sacrificar demasiado la extensibilidad. Y sobre todo, permite mantener un lenguaje común entre programadores a la hora de referenciar un problema.

## 2.- Patrón de diseño Singleton.

El patrón Singleton es un patrón de diseño en el que una clase solo puede tener una única instancia de sí misma. para ello se utilizan los modificadores de acceso (Como private y protected). En conjunción con un método específico y público que se encarga de llamar al constructor. 

## 3.- Patrón de diseño Factory. 

Implementa una clase creadora abstracta que puede ser capaz de crear varios tipos de objetos distintos, según se llame al método fabricante. 

## 4.- Patrón de diseño Builder

Este implementa varias clases que en conjunción son capaces de crear objetos complejos desde un objeto fuente. El objeto fuente se compone de una variedad de partes que contribuyen individualmente a la creación de cada objeto complejo a través de un conjunto de llamadas a interfaces comunes de la clase Abstract Builder
.

## 5.- ADB de Android.

ADB (Por sus siglas en inglés "Android Debug Bridge") Es una herramienta que permite interactuar al usuario con el software de nuestro smartphone que tenga android como sistema operativo desde un ordenador. Básicamente, ADB es la manera de cambiar profundamente el software del smartphone. ADB Es una parte fundamental de android studio.

## 6.- "final" En Java.

El operador final hace que a un objeto o variable se le pueda hacer una y sólo una asignación. Si se intenta hacer otra asignación, el compilador arrojará un error.

## 7.- Lenguajes que soportan Sobrecarga de operadores

* C++
* C#
* Ada
* Ceylon
* D
* Dart
* FreeBASIC
* Groovie
* Lua
* MATLAB
* Object Pascal
* PHP
* Perl
* Pyhton
* Ruby
* Rust
* Visual Basic .NET

## 8.- ¿Para qué sirve Gradle?

Gradle es una herramienta para automatizar la construcción de nuestros proyectos, por ejemplo las tareas de compilación, testing, empaquetado y el despliegue de los mismos. Es muy flexible para la configuración, pero además ya tiene armadas las tareas para las mayoría de los proyectos por default. Esta herramienta es usado por grandes proyecto “Open Source” como “Spring”, “Hibernate”, y “Grails”. (También lo usan empresas como “LinkedIn” para sus proyectos)

## 9.- inyección de dependencias en desarrollo de software.

En informática, inyección de dependencias (en inglés Dependency Injection, DI) es un patrón de diseño orientado a objetos, en el que se suministran objetos a una clase en lugar de ser la propia clase quien cree el objeto. El término fue acuñado por primera vez por Martin Fowler.
La forma habitual de implementar este patrón es mediante un "Contenedor DI" y objetos planos o simples por ejemplo los llamados POJO en java (Plain Old Java Object, es una sigla utilizada por programadores Java para enfatizar el uso de clases simples y que no dependen de un framework en especial.). El contenedor inyecta a cada objeto los objetos necesarios según las relaciones plasmadas en un fichero de configuración.

Típicamente este contenedor es implementado por un framework externo a la aplicación (como Spring entre otros), por lo cual en la aplicación también se utilizará inversión de control al ser el contenedor (almacenado en una biblioteca) quien invoque el código de la aplicación. Ésta es la razón por la que los términos de inversión de control e inyección de dependencias se confunden habitualmente entre sí.
