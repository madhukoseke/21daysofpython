# Day 20: Classes Practice

## 📚 Topics Covered
- Inheritance
- Method overriding
- super() function
- Real-world examples

## 🔑 Key Concepts

### Inheritance
```python
class Animal:
    def __init__(self, name):
        self.name = name

class Dog(Animal):
    def bark(self):
        return "Woof!"
```

### Method Overriding
```python
class Dog(Animal):
    def speak(self):
        return "Woof!"

class Cat(Animal):
    def speak(self):
        return "Meow!"
```

### Using super()
```python
class Dog(Animal):
    def __init__(self, name, breed):
        super().__init__(name)
        self.breed = breed
```

## ✅ Remember
- Inheritance promotes code reuse
- Child classes extend parent classes
- super() calls parent methods
- Polymorphism through inheritance
- Encapsulation with private attributes

## 📝 Practice Focus
- Building class hierarchies
- Real-world modeling
- Method overriding
- Complex object interactions
