# Day 19: Classes Basics

## 📚 Topics Covered
- Class definition
- __init__ method
- Instance methods
- Instance vs class attributes

## 🔑 Key Concepts

### Defining Classes
```python
class Dog:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    
    def bark(self):
        return f"{self.name} says woof!"
```

### Creating Objects
```python
my_dog = Dog("Buddy", 3)
print(my_dog.name)
print(my_dog.bark())
```

### Class vs Instance Attributes
```python
class Dog:
    species = "Canis familiaris"  # Class attribute
    
    def __init__(self, name):
        self.name = name  # Instance attribute
```

## ✅ Remember
- Classes are blueprints
- Objects are instances
- __init__ is constructor
- self refers to instance
- Methods are functions in classes

## 📝 Practice Focus
- Creating classes
- Instance methods
- Object interaction
- Real-world modeling
