# SOLID


El principio [SOLID](https://es.wikipedia.org/wiki/SOLID) es un conjunto de cinco principios de diseño de software que fueron introducidos por el ingeniero de software Robert C. Martin, también conocido como "Uncle Bob". Estos principios están destinados a guiar a los desarrolladores hacia prácticas de diseño de software más limpias, mantenibles y extensibles.

<img src="images/solid.png" alt="Descripción de la imagen" width="500">



Los principios SOLID son los siguientes:

1. **S - Principio de Responsabilidad Única (Single Responsibility Principle - SRP):** Este principio establece que una clase debe tener una sola razón para cambiar, es decir, debe tener una sola responsabilidad. Si una clase tiene más de una responsabilidad, se debe dividir en clases más pequeñas, cada una con una única responsabilidad.

2. **O - Principio de Abierto/Cerrado (Open/Closed Principle - OCP):** Este principio establece que las entidades de software (clases, módulos, funciones, etc.) deben estar abiertas para su extensión pero cerradas para su modificación. Esto significa que el comportamiento de una entidad debe poder ser extendido sin cambiar su implementación existente.

3. **L - Principio de Sustitución de Liskov (Liskov Substitution Principle - LSP):** Este principio establece que los objetos de un programa deberían ser reemplazables por instancias de sus subtipos sin afectar la corrección del programa. En otras palabras, una subclase debe poder sustituir a su clase base sin cambiar el comportamiento esperado del programa.

4. **I - Principio de Segregación de Interfaces (Interface Segregation Principle - ISP):** Este principio establece que una clase no debe ser forzada a depender de métodos que no utiliza. En lugar de tener interfaces grandes que contienen métodos para diferentes casos de uso, se deben tener varias interfaces más pequeñas y específicas que satisfagan las necesidades de cada cliente.

5. **D - Principio de Inversión de Dependencias (Dependency Inversion Principle - DIP):** Este principio establece que las clases de alto nivel no deben depender de las clases de bajo nivel, sino de abstracciones. Las abstracciones no deben depender de detalles concretos; los detalles concretos deben depender de abstracciones. Esto fomenta el desacoplamiento entre las clases de alto nivel y las clases de bajo nivel.

Estos principios SOLID proporcionan una guía valiosa para el diseño de software que es fácil de entender, mantener y extender. Fomentan la modularidad, el desacoplamiento, la reutilización y la claridad en el diseño de software.
