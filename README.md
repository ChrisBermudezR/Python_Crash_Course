# Python Crash Course

## Programación Orientada a Objetos (POO)

La programación orientada a objetos (POO) es un paradigma de programación que utiliza “objetos” como base. Estos objetos contienen información en forma de campos (también referidos como atributos o propiedades) y código en forma de métodos. Los objetos pueden interactuar y modificar los valores contenidos en sus campos o atributos (estado) a través de sus métodos (comportamiento).

Algunas características clave de la programación orientada a objetos son la herencia, cohesión, abstracción, polimorfismo, acoplamiento y encapsulamiento. La programación orientada a objetos se popularizó a principios de la década de 1990 y en la actualidad, existe una gran variedad de lenguajes de programación que soportan la orientación a objetos.

En la programación orientada a objetos, primero se definen los objetos o estructuras para posteriormente solicitar la ejecución de sus métodos. Esto difiere de la programación estructurada tradicional, en la que los datos y los procedimientos están separados y sin relación.


La programación orientada a objetos es uno de los enfoques más efectivos para escribir software. En la programación orientada a objetos, escribes clases que representan cosas y situaciones del mundo real, y creas objetos basados en estas clases. Cuando escribes una clase, defines el comportamiento general que puede tener toda una categoría de objetos.



```python
class Dog:
    """A simple attempt to model a dog."""
 def __init__(self, name, age):
    """Initialize name and age attributes."""
    self.name = name
    self.age = age
 def sit(self):
    """Simulate a dog sitting in response to a command."""
    print(f"{self.name} is now sitting.")
def roll_over(self):
    """Simulate rolling over in response"""
```