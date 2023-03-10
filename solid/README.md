# Principios SOLID
En este repositorio se encuentran ejemplos de los principios SOLID, los cuales se encuentran explicados en el siguiente [artículo](https://www.freecodecamp.org/espanol/news/los-principios-solid-explicados-en-espanol/).

En el código se encuentran los siguientes ejemplos:
- **Single Responsibility Principle**: La clase `Dog` tiene una única responsabilidad, que es representar un perro con un nombre y una edad, y definir cómo se mueve el perro.
- **Open-Closed Principle**: La clase `Dog` está abierta a la extensión, ya que se puede extender para agregar nuevas funcionalidades, pero cerrada a la modificación, ya que no se debe modificar la clase para agregar nuevas funcionalidades.
- **Liskov Substitution Principle**: La clase `Dog` es una subclase de la clase `Animal`, y por lo tanto, se puede usar en cualquier lugar donde se requiera una clase `Animal`. La clase `Dog` no rompe el principio de sustitución de Liskov, ya que sigue cumpliendo con el contrato de la clase `Animal`.
- **Interface Segregation Principle**: La interfaz `IAnimal` es pequeña y específica, y se enfoca en definir cómo se mueve un animal. La clase `Dog` implementa sólo los métodos relevantes para su funcionalidad, en lugar de tener que implementar una interfaz grande y compleja que no es relevante para su funcionalidad.
- **Dependency Inversion Principle**: La clase `Dog` depende de la interfaz `IAnimal` en lugar de una clase concreta, lo que permite una mayor flexibilidad y escalabilidad en el código.