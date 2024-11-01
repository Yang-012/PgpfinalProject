```mermaid
classDiagram
    class Animal {
      +String name
      +int age
      +makeSound()
    }

    class Dog {
      +String breed
      +bark()
    }

    Animal <|-- Dog
```