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

Este implementa varias clases que en conjunción son capaces de crear objetos complejos desde un objeto fuente. El objeto fuente se compone de una variedad de partes que contribuyen individualmente a la creación de cada objeto complejo a través de un conjunto de llamadas a interfaces comunes de la clase Abstract Builder.
