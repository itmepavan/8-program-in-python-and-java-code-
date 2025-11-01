✅ *Programming Basics – Part 8: Object-Oriented Programming (OOP)* 💻

✅ *What is Object-Oriented Programming?*  
OOP is a programming paradigm based on the concept of *objects*, which combine *data* (attributes) and *behavior* (methods) into a single unit.

➊ *Core Concepts of OOP*

- *Class* → Blueprint for creating objects  
- *Object* → Instance of a class  
- *Encapsulation* → Bundling data & methods  
- *Inheritance* → One class inherits from another  
- *Polymorphism* → Same method behaves differently  
- *Abstraction* → Hiding internal details

➋ *Create a Class & Object*

📍 *Python:*  
```python
class Car:
    def _init_(self, brand):
        self.brand = brand

car1 = Car("Tesla")
```

📍 *Java:*  
```java
class Car {
    String brand;
    Car(String b) { brand = b; }
}

Car car1 = new Car("Tesla");
``

Car car1("Tesla");
```

➌ *Encapsulation Example*

📍 *Python:*  
```python
class Person:
    def _init_(self, name):
        self.__name = name  # private
```

➍ *Inheritance Example*

📍 *Java:*  
```java
class Animal {
    void sound() { System.out.println("Sound"); }
}
class Dog extends Animal {
    void sound() { System.out.println("Bark"); }
}
```

➎ *Polymorphism Example*
📍 *Python:*  
```python
class Shape:
    def area(self): pass

class Circle(Shape):
    def area(self): return "πr²"
```

➏ *Why Use OOP?*

- Better code organization  
- Reusability via inheritance  
- Easier maintenance & testing  
- Real-world modeling

➐ *Real-World Use Cases*

- Game development  
- GUI applications  
- Data models (user, product, order, etc.)  
  
